#### Test 5065027881383b1_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3521): !@Sync 4
,--------- beginning of main
D/AndroidRuntime(11654): 
D/AndroidRuntime(11654): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11654): CheckJNI is OFF
D/AndroidRuntime(11654): readGMSProperty: start
D/AndroidRuntime(11654): readGMSProperty: already setted!!
D/AndroidRuntime(11654): readGMSProperty: end
D/AndroidRuntime(11654): addProductProperty: start
D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 283, CUR = 47
E/AffinityControl(11654): AffinityControl: registerfunction enter
D/AndroidRuntime(11654): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3521): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3521): mDVFSHelper.acquire()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (11678): MountEmulatedStorage()
E/Zygote  (11678): v2
I/libpersona(11678): KNOX_SDCARD checking this for 10480
I/libpersona(11678): KNOX_SDCARD not a persona
I/SELinux (11678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11678 uid=10480 gids={50480, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime(11654): Shutting down VM
E/SELinux (11678): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(11678): TimaSignature is unavailable
D/ActivityThread(11678): Added TimaKeyStore provider
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11678): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6258): updateVisibility : ActivityRecord{2e8ccff3 token=android.os.BinderProxy@305e86c4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:66, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
D/BatteryService( 3521): stay LED for fully charged
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/WebViewFactory(11678): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11678): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11678): Loading: webviewchromium
I/LibraryLoader(11678): Time to load native libraries: 4 ms (timestamps 4318-4322)
I/LibraryLoader(11678): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11678): Binding Chromium to main looper Looper (main, tid 1) {1ca53c72}
I/LibraryLoader(11678): Expected native library version number "",actual native library version number ""
I/chromium(11678): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11678): Initializing chromium process, renderers=0
W/art     (11678): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11678): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11678): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11678): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11678): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11678): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11678): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11678): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11678): CordovaWebView is running on device made by: samsung
W/art     (11678): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11678): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11678): performCreate Call secproduct feature valuefalse
D/Activity(11678): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11678): Render dirty regions requested: true
D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11678): Initialized EGL, version 1.4
I/OpenGLRenderer(11678): HWUI protection enabled for context ,  &this =0xaf845060 ,&mEglDisplay = 1 , &mEglConfig = -1279725296 
D/OpenGLRenderer(11678): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11678): Enabling debug mode 0
D/mali_winsys(11678): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11678): updateVisibility : ActivityRecord{561a622 token=android.os.BinderProxy@e2b6641 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{df16dbc u0 com.test.thalitest/.MainActivity t26} time:134666
W/IInputConnectionWrapper(11678): showStatusIcon on inactive InputConnection
I/Timeline(11678): Timeline: Activity_idle id: android.os.BinderProxy@e2b6641 time:134675
I/chromium(11678): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11678): 
D/JsMessageQueue(11678): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(11678): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1260403840
D/JX-Cordova(11678): jxcore cordova android initializing
,W/jxcore-log(11678): Initializing JXcore engine
W/jxcore-log(11678): JXcore engine is ready
,W/jxcore-log(11678): Starting JXcore engine
,E/auditd  ( 4608): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3521): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3521): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11678): Platform android
W/jxcore-log(11678): 
W/jxcore-log(11678): Process ARCH arm
W/jxcore-log(11678): 
,I/jxcore-log(11678): JXcore Cordova bridge is ready!
I/jxcore-log(11678): 
W/jxcore-log(11678): JXcore engine is started
,I/jxcore-log(11678): Toggling radios to true
I/jxcore-log(11678): 
,D/BluetoothAdapter(11678): enable()
,D/BluetoothAdapter(11678): enable(): BT is already enabled..!
,D/WifiService( 3521): New client listening to asynchronous messages
,I/WifiManager(11678): packageName : com.test.thalitest
,D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/WifiService( 3521): setWifiEnabled: true pid=11678, uid=10480
E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=11678, uid=10480 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3521): Failed getting userId using ActivityManagerNative
W/WifiService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11678, uid=10480 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3521): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3521): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3521): name = wifi_on
,I/WifiService( 3521): disconnect: pid=11678, uid=10480
,I/wpa_supplicant( 3829): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3829): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3829): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3521): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3829): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): Disconnected - do not scan
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3521): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11678): Radios toggled
I/jxcore-log(11678): 
,I/jxcore-log(11678): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11678): 
,I/jxcore-log(11678): Perf Test app loaded loaded
I/jxcore-log(11678): 
,I/jxcore-log(11678): check test folder
I/jxcore-log(11678): 
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,I/jxcore-log(11678): found test : ./testFindPeers.js
I/jxcore-log(11678): 
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,I/jxcore-log(11678): found test : ./testSendData.js
I/jxcore-log(11678): 
,E/WifiStateMachine( 3521): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 3521): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,I/Hs20UtilService( 4103): Starting #8
,I/Hs20UtilService( 4103): Message received 5007
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/NearbySettings( 8847): MountReceiver.onReceive - Create HandlerThread
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
D/NearbySettings( 8847): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8847): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8847): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8847): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3521): New client listening to asynchronous messages
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8847): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8847): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3521): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1449752997113
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/ConnectivityService( 3521): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3521): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3521): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityManager.CallbackHandler( 6651): CM callback handler got msg 524292
,I/wpa_supplicant( 3829): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3829): First Scan Start
D/TelephonyNetworkFactory( 3978): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/wpa_supplicant( 3829): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3521): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/ConnectivityService( 3521): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering( 3521): MasterInitialState.processMessage what=3
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): updateIfacesLocked()
V/NetworkStats( 3521): performPollLocked(flags=0x1)
,I/Choreographer(11678): Skipped 48 frames!  The application may be doing too much work on its main thread.
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,V/NetworkStats( 3521): performPollLocked() took 7ms
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
I/chromium(11678): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Hs20UtilService( 4103): Starting #9
I/Hs20UtilService( 4103): Message received 5007
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NearbySettings( 8847): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8847): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8847): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8847): MountReceiver.mPrefHandler - 7002
I/chromium(11678): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3521): updateDataUsageMap
,I/ApplicationPolicy( 3521): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3521): No Active Data Connection
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11794): MountEmulatedStorage()
,E/Zygote  (11794): v2
,I/libpersona(11794): KNOX_SDCARD checking this for 10110
,I/libpersona(11794): KNOX_SDCARD not a persona
,I/SELinux (11794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11794 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/DBG_DM  ( 6258): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SELinux (11794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11794): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6258): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider(11794): TimaSignature is unavailable
,D/ActivityThread(11794): Added TimaKeyStore provider
,D/ResourcesManager(11794): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11794): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11794): not using cross-dex optimization: ART in use
,I/art     (11794): Thread[1,tid=11794,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11794): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11794): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(11794): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11794): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11794): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11794): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11794): loading pre-built fallback odex files
V/MultiDexClassLoader(11794): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11794): released odex store lock
,D/DexLibLoader(11794): DexLibLoader.loadAll took 34 ms
,W/ca      (11794): Verify
,W/LightSharedPreferencesImpl(11794): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11794): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11794): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11794): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11794): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11794): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11794): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11794): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11794): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11794): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11794): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11794): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11794): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11794): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11794): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11794): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11794): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11794): 	... 10 more
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11826): MountEmulatedStorage()
E/Zygote  (11826): v2
I/libpersona(11826): KNOX_SDCARD checking this for 1000
I/libpersona(11826): KNOX_SDCARD not a persona
,I/SELinux (11826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11826 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11826): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 9796:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11794): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/wpa_supplicant( 3829): nl80211: Received scan results (10 BSSes)
,I/wpa_supplicant( 3829): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3829): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3829): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3521): [1,449,752,998,231 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2343ef sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3521): setDetailed state send new extra info
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 3521): mCursor = null
,D/TimaKeyStoreProvider(11826): TimaSignature is unavailable
,D/ActivityThread(11826): Added TimaKeyStore provider
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3829): Associated with C0.AA.48
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
W/appmanager(:<default>):b(11794): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/ResourcesManager(11826): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3829): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3829): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3829): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3829): Blacklist: Clear (temp) 
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): Network connection established
,D/WifiNative-HAL( 3521): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3521): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3521): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3521): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/PCWCLIENTTRACE_LOG(11826): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11826): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11826): new DMDBOpenHelper instance
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3521): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/PCWCLIENTTRACE_PushUtil(11826): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11826): sales region : global
I/PCWCLIENTTRACE_PushUtil(11826): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11826): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11826): noConnectivity : true
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/appmanager(:<default>):QuickExperimentControllerImpl(11794): Exposure of experiment com.facebook.common.network.l@3d0fe4db occurred when no user was logged in
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11864): MountEmulatedStorage()
E/Zygote  (11864): v2
I/libpersona(11864): KNOX_SDCARD checking this for 10135
I/libpersona(11864): KNOX_SDCARD not a persona
,I/SELinux (11864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11864 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11864): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{20ca311 u0 ReceiverList{a6d9738 11794 com.facebook.appmanager/10110/u0 remote:afcb79b}}
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{20ca311 u0 ReceiverList{a6d9738 11794 com.facebook.appmanager/10110/u0 remote:afcb79b}}
,I/ActivityManager( 3521): Killing 10964:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11864): TimaSignature is unavailable
,D/ActivityThread(11864): Added TimaKeyStore provider
,D/ResourcesManager(11864): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend false
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{310e2b05 u0 ReceiverList{1529367c 11794 com.facebook.appmanager/10110/u0 remote:1259f96f}}
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,I/MusicStore(11864): Database version: 104
,D/ResourcesManager(11864): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11864): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11864): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11864): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15db8aa6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11864): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11864): GMSCore installation verified
,I/ConfigStore(11864): Config Database version: 1
,E/dhcpcd  (11896): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11896): version 5.5.6 starting
,E/dhcpcd  (11896): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11864): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/dhcpcd  (11896): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11896): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11896): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11896): bssid match
I/dhcpcd  (11896): wlan0: rebinding lease of 192.168.1.124
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11864): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11864): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3521): getStreamVolume 3 index 0
,I/MediaRouter(11864): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11905): MountEmulatedStorage()
E/Zygote  (11905): v2
I/libpersona(11905): KNOX_SDCARD checking this for 10002
I/libpersona(11905): KNOX_SDCARD not a persona
,I/SELinux (11905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11905 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11794): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11794): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/TimaKeyStoreProvider(11905): TimaSignature is unavailable
,D/ActivityThread(11905): Added TimaKeyStore provider
,I/NetworkMonitor(11864): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3521): Killing 10981:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(11905): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11794): Exposure of experiment com.facebook.imagepipeline.a.g@2ae63036 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11794): Exposure of experiment com.facebook.imagepipeline.a.d@280943d3 occurred when no user was logged in
,I/ActivityManager( 3521): Killing 10997:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/art     (11794): Explicit concurrent mark sweep GC freed 45712(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 2.130ms total 49.517ms
,W/appmanager(:<default>):m(11794): No feature status reporters found; is this dead code?
,E/Zygote  (11926): MountEmulatedStorage()
E/Zygote  (11926): v2
I/libpersona(11926): KNOX_SDCARD checking this for 1000
I/libpersona(11926): KNOX_SDCARD not a persona
,I/SELinux (11926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11926 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11926): TimaSignature is unavailable
,D/ActivityThread(11926): Added TimaKeyStore provider
,D/ResourcesManager(11926): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/dhcpcd  (11896): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/DIAGMON_AGENT(11926): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/dhcpcd  (11896): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/DIAGMON_AGENT(11926): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11926): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11926): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11926): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11958): MountEmulatedStorage()
,E/Zygote  (11958): v2
I/libpersona(11958): KNOX_SDCARD checking this for 10012
I/libpersona(11958): KNOX_SDCARD not a persona
,I/SELinux (11958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11958): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11958 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11958): TimaSignature is unavailable
,D/ActivityThread(11958): Added TimaKeyStore provider
,D/ResourcesManager(11958): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3521): Killing 11036:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(11958): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11958): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11958): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11981): MountEmulatedStorage()
E/Zygote  (11981): v2
I/libpersona(11981): KNOX_SDCARD checking this for 10021
I/libpersona(11981): KNOX_SDCARD not a persona
,I/SELinux (11981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend true
,I/SELinux (11981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11981 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
I/ActivityManager( 3521): Killing 11020:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/WifiStateMachine( 3521): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3521): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3521): Not connected state, yet.
E/WifiStateMachine( 3521): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3521): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3521): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3521): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3521): updateNetworkInfo()
D/TimaKeyStoreProvider(11981): TimaSignature is unavailable
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 919us total 37.096ms
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3521): Adding iface wlan0 to network 503
D/ActivityThread(11981): Added TimaKeyStore provider
,D/WifiWatchdogStateMachine( 3521): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3521): Now, connected state.
E/WifiStateMachine( 3521): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 629us total 21.424ms
,E/WifiStateMachine( 3521): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/ConnectivityService( 3521): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3521): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3521): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3521): Unexpected mtu value: 0, wlan0
,D/ResourcesManager(11981): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
V/        ( 2844): QcRouteController
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3521): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 942us total 17.442ms
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3521): callSECApiVoid - ID [212]
E/WifiStateMachine( 3521): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        ( 2844): QcRouteController
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,I/KLMS-2.4.521: (11981): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 14:09:59 GMT+01:00 2015
,I/KLMS-2.4.521: (11981): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11981): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11981): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,V/        ( 2844): QcRouteController
,I/KLMS-2.4.521: (11981): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11981): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11981): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController
,I/KLMS-2.4.521: (11981): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11981): StateImplV2(): networkChangeListener().END
,E/Zygote  (12008): MountEmulatedStorage()
E/Zygote  (12008): v2
I/libpersona(12008): KNOX_SDCARD checking this for 10038
I/libpersona(12008): KNOX_SDCARD not a persona
,I/SELinux (12008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,V/        ( 2844): QcRouteController
,I/SELinux (12008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12008 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (12008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11981): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3521): Killing 11054:com.wsomacp/u0a28 (adj 15): bgCount ##31
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,D/TimaKeyStoreProvider(12008): TimaSignature is unavailable
,D/ActivityThread(12008): Added TimaKeyStore provider
,V/        ( 2844): QcRouteController
,D/ResourcesManager(12008): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/ConnectivityService( 3521): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3521): LTETest block dns file not exists
,D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3521): updateNetworkInfo()
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3521): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Checking http://clients3.google.com/generate_204 on "NG700"
,E/JavaBinder( 3521): !!! FAILED BINDER TRANSACTION !!!
,D/ConnectivityService( 3521):    accepting network in place of null
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 3521): Failed to clear dns cache for: com.wsomacp
,D/TelephonyNetworkFactory( 3978): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
,E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 3521): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering( 3521): MasterInitialState.processMessage what=3
,I/SO_AGENT(12008): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
D/ConnectivityService( 3521): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkStats( 3521): updateIfacesLocked()
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
V/NetworkStats( 3521): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
V/NetworkStats( 3521): performPollLocked() took 11ms
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/ConnectivityManager.CallbackHandler( 6651): CM callback handler got msg 524290
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,E/Zygote  (12031): MountEmulatedStorage()
E/Zygote  (12031): v2
I/libpersona(12031): KNOX_SDCARD checking this for 1000
I/libpersona(12031): KNOX_SDCARD not a persona
,I/SELinux (12031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12031 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12031): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10847:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider(12031): TimaSignature is unavailable
,D/ActivityThread(12031): Added TimaKeyStore provider
,I/System.out( 3521): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ResourcesManager(12031): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:09:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449752999858], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449752999843]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Validated
D/ConnectivityService( 3521): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6651): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12051): MountEmulatedStorage()
E/Zygote  (12051): v2
,I/libpersona(12051): KNOX_SDCARD checking this for 10039
I/libpersona(12051): KNOX_SDCARD not a persona
,I/SELinux (12051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12051 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12051): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11075:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12051): TimaSignature is unavailable
,D/ActivityThread(12051): Added TimaKeyStore provider
,D/ResourcesManager(12051): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,V/AlarmManager( 3521): waitForAlarm result :8
,E/SPPClientService(12051): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12051): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12051): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12051): PushLog.txt file is not deleted.
D/SPPClientService(12051): PushLog.txt file is not deleted.
D/SPPClientService(12051): ============PushLog. stop!
,I/SA      (11160): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11160): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11160): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11160): [SLFUCHKMGR] constructor called
,E/SPPClientService(12051): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11160): [OR] == isSIMCardReady false ==
,I/SA      (11160): [SCU] == networkStateCheck == true
,I/SA      (11160): [DM] getCountryCodeFromCSC : PL
I/SA      (11160): isChinaCountryCode : false
I/SA      (11160): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11160): [OR] == networkStateCheck true ==
I/SA      (11160): [OR] GetMyCountryZoneTask
,I/SA      (11160): [OR] onReceive END
,I/SA      (11160): [SRS] prepareGetMyCountryZone
,I/ActivityManager( 3521): Killing 11094:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,V/DownloadManager( 5718): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11160): [SSP] query invoked
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12075): MountEmulatedStorage()
,E/Zygote  (12075): v2
I/libpersona(12075): KNOX_SDCARD checking this for 10067
I/libpersona(12075): KNOX_SDCARD not a persona
,I/SELinux (12075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12075 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12075): TimaSignature is unavailable
,D/ActivityThread(12075): Added TimaKeyStore provider
,D/ResourcesManager(12075): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 73196(3MB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 49MB/65MB, paused 2.223ms total 150.651ms
,I/sCloudBackupApp(12075): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SA      (11160): [TPMU] GetMccFromDB : null
I/SA      (11160): [SCU] getMccFromPreferece mcc = 260
I/SCloudBackupReceiver(12075): Other Intent
I/SA      (11160): [TPM] isNoProxy(default) : true
,I/ActivityManager( 3521): Killing 11140:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5125): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3521): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 18
,I/DBG_DM  ( 6258): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6258): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11864): type=WIFI subType= reason=null isConnected=true
,D/accuweather( 5125): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5125): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5125): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
W/ResourceType( 5352): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5352): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/accuweather( 5125): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12092): MountEmulatedStorage()
,E/Zygote  (12092): v2
I/libpersona(12092): KNOX_SDCARD checking this for 1000
I/libpersona(12092): KNOX_SDCARD not a persona
,I/SELinux (12092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,D/TimaKeyStoreProvider(12092): TimaSignature is unavailable
,D/ActivityThread(12092): Added TimaKeyStore provider
,D/ResourcesManager(12092): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12092): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12092): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12092): premStatus:2
,I/KnoxUsageLogPro(12092): isEulaShown : false
I/KnoxUsageLogPro(12092): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12107): MountEmulatedStorage()
E/Zygote  (12107): v2
I/libpersona(12107): KNOX_SDCARD checking this for 10090
I/libpersona(12107): KNOX_SDCARD not a persona
,I/SELinux (12107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12107 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12107): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 11113:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12107): TimaSignature is unavailable
,D/ActivityThread(12107): Added TimaKeyStore provider
,D/ResourcesManager(12107): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12123): MountEmulatedStorage()
E/Zygote  (12123): v2
I/libpersona(12123): KNOX_SDCARD checking this for 10127
I/libpersona(12123): KNOX_SDCARD not a persona
,I/SELinux (12123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12123 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12123): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11230:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12123): TimaSignature is unavailable
,D/ActivityThread(12123): Added TimaKeyStore provider
,D/ResourcesManager(12123): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,I/SA      (11160): [RC New] Execute method=[GET] start
,D/KeyguardWallpaperUpdator(12123): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12123): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12123): stopCheckCategoryVersion
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/SA      (11160): [RC New] Security=[true]
,I/System.out(11160): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11160): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11160): Thread-1540(ApacheHTTPLog):isShipBuild true
I/System.out(11160): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,E/Zygote  (12140): MountEmulatedStorage()
,E/Zygote  (12140): v2
I/libpersona(12140): KNOX_SDCARD checking this for 10136
I/libpersona(12140): KNOX_SDCARD not a persona
,I/SELinux (12140): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12140 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11247:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/SELinux (12140): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12140): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12140): TimaSignature is unavailable
,D/ActivityThread(12140): Added TimaKeyStore provider
,D/ResourcesManager(12140): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ConnectivityService( 3521): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12140): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12140): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12140): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2828): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2828): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12140): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12140): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12140): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12140): Loading: webviewchromium
,I/LibraryLoader(12140): Time to load native libraries: 16 ms (timestamps 983-999)
I/LibraryLoader(12140): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12140): Binding Chromium to main looper Looper (main, tid 1) {196f6200}
,I/LibraryLoader(12140): Expected native library version number "",actual native library version number ""
,I/chromium(12140): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12140): Initializing chromium process, renderers=0
,W/art     (12140): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12140): Requires BLUETOOTH permission
,W/chromium(12140): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12140): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12140): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12140): Starting up...
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12216): MountEmulatedStorage()
E/Zygote  (12216): v2
I/libpersona(12216): KNOX_SDCARD checking this for 10150
I/libpersona(12216): KNOX_SDCARD not a persona
,I/SELinux (12216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12216): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12216 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11214:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/SA      (11160): [RC New] [v2liruge] api execute + 619
I/SA      (11160): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11160): AsyncTask #1 calls detatch()
,I/SA      (11160): [TPMU] getNetworkMcc : 
,I/SA      (11160): [SCU] saveMccToPreferece Start
I/SA      (11160): [SCU] RegionMCC : 260
I/SA      (11160): [SSP] query invoked
,I/SA      (11160): [TPMU] GetMccFromDB : null
I/SA      (11160): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11160): [SCU] saveMccToPreferece End
,D/TimaKeyStoreProvider(12216): TimaSignature is unavailable
I/SA      (11160): [RC New] executeRequest [v2liruge] end. 655
I/SA      (11160): [RC New] Execute end
,I/SA      (11160): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11160): [OR] GetMyCountryZoneTask Success
D/ActivityThread(12216): Added TimaKeyStore provider
,D/ResourcesManager(12216): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12216): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12216): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12216): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12216): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12216): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12231): MountEmulatedStorage()
E/Zygote  (12231): v2
I/libpersona(12231): KNOX_SDCARD checking this for 10178
I/libpersona(12231): KNOX_SDCARD not a persona
,I/SELinux (12231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12231 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (12231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11263:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12231): TimaSignature is unavailable
,D/ActivityThread(12231): Added TimaKeyStore provider
,D/ResourcesManager(12231): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12231): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12231): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12231): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12231): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12231): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12231): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/Zygote  (12254): MountEmulatedStorage()
E/Zygote  (12254): v2
I/libpersona(12254): KNOX_SDCARD checking this for 10082
I/libpersona(12254): KNOX_SDCARD not a persona
,I/SELinux (12254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12254 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/SELinux (12254): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 973us total 26.560ms
,D/TimaKeyStoreProvider(12254): TimaSignature is unavailable
,D/ActivityThread(12254): Added TimaKeyStore provider
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 771us total 17.925ms
,I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 372us total 13.988ms
,E/Zygote  (12271): MountEmulatedStorage()
I/libpersona(12271): KNOX_SDCARD checking this for 1000
E/Zygote  (12271): v2
I/libpersona(12271): KNOX_SDCARD not a persona
,I/SELinux (12271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12271 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 11279:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 11334:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12271): TimaSignature is unavailable
,D/ActivityThread(12271): Added TimaKeyStore provider
,D/ResourcesManager(12254): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager(12271): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12254): onCreate
,D/BadgeProvider(12254): DatabaseHelper
,I/ActivityManager( 3521): Killing 11352:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12254): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12254): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12254): sendNotify, [notify] : null
D/BadgeProvider(12254): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12254): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12254): update, [UpdateCount] : 1
D/Launcher.Model( 3997): reloadBadges entered.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12288): MountEmulatedStorage()
E/Zygote  (12288): v2
I/libpersona(12288): KNOX_SDCARD checking this for 10013
I/libpersona(12288): KNOX_SDCARD not a persona
,I/SELinux (12288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12288 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12288): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12288): TimaSignature is unavailable
,D/ActivityThread(12288): Added TimaKeyStore provider
,D/ResourcesManager(12288): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12288): notifyNetworkActivated
,W/ContextImpl(12288): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3521): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log(11678): BLE supported!!
I/jxcore-log(11678): 
,D/hcjo    (12288): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12288): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12288): exit::IDLE
D/InitializeManagerStateMachine(12288): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12288): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12288): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12288): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12288): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12288): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12288): entry::SUCCESS
D/hcjo    (12288): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 4103): Starting #10
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8847): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8847): DMSUtil.isNetworkConnected - flag-null, state-null
,D/hcjo    (12288): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12288): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine(12288): exit::SUCCESS
D/InitializeManagerStateMachine(12288): entry::IDLE
,I/NearbySettings( 8847): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8847): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,I/ActivityManager( 3521): Killing 11370:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4103): Starting #11
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8847): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8847): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4103): Starting #12
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8847): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8847): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8847): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8847): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8847): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4103): Starting #13
,I/Hs20UtilService( 4103): Message received 5007
,D/NearbySettings( 8847): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8847): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3521): callSECApi what=220
D/WifiStateMachine( 3521): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11314): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11826): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11826): sales region : global
I/PCWCLIENTTRACE_PushUtil(11826): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11826): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2848): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT(11926): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11926): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(11958): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11958): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11958): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11981): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 14:10:02 GMT+01:00 2015
,I/KLMS-2.4.521: (11981): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11981): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11981): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11981): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (11981): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (11981): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11981): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(12008): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11981): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11981): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11981): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11981): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11981): KLMSIntentService(): onDestroy()
,E/SPPClientService(12051): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11160): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11160): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11160): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11160): [OR] == isSIMCardReady false ==
,I/SA      (11160): [SCU] == networkStateCheck == true
I/SA      (11160): [DM] getCountryCodeFromCSC : PL
I/SA      (11160): isChinaCountryCode : false
I/SA      (11160): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11160): [OR] == networkStateCheck true ==
I/SA      (11160): [OR] GetMyCountryZoneTask
,I/SA      (11160): [OR] onReceive END
,I/SA      (11160): [SRS] prepareGetMyCountryZone
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11160): [SSP] query invoked
,V/DownloadManager( 5718): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11160): [TPMU] GetMccFromDB : null
I/SA      (11160): [SCU] getMccFromPreferece mcc = 260
I/SA      (11160): [TPM] isNoProxy(default) : true
I/SA      (11160): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver(12075): Other Intent
,D/accuweather( 5125): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5125): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5125): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5125): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5125): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12092): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12092): premStatus:2
,I/KnoxUsageLogPro(12092): isEulaShown : false
I/KnoxUsageLogPro(12092): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      (11160): [RC New] Security=[true]
,D/KeyguardWallpaperUpdator(12123): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12123): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12123): stopCheckCategoryVersion
,D/QuickConnect(12216): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12216): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12216): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/hcjo    (12288): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12288): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12288): exit::IDLE
D/InitializeManagerStateMachine(12288): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12288): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12288): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12288): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12288): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12288): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12288): entry::SUCCESS
D/hcjo    (12288): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12288): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12288): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12288): exit::SUCCESS
D/InitializeManagerStateMachine(12288): entry::IDLE
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3521): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  (11896): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (11896): wlan0: sendmsg: Cannot assign requested address
,I/SA      (11160): [RC New] [v2liruge] api execute + 661
,I/SA      (11160): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11160): AsyncTask #2 calls detatch()
,I/SA      (11160): [TPMU] getNetworkMcc : 
,I/SA      (11160): [SCU] saveMccToPreferece Start
,I/SA      (11160): [SCU] RegionMCC : 260
I/SA      (11160): [SSP] query invoked
,I/SA      (11160): [TPMU] GetMccFromDB : null
I/SA      (11160): [SCU] getMccFromPreferece mcc = 260
I/SA      (11160): [SCU] saveMccToPreferece End
,I/SA      (11160): [RC New] executeRequest [v2liruge] end. 724
I/SA      (11160): [RC New] Execute end
I/SA      (11160): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11160): [OR] GetMyCountryZoneTask Success
,D/SSRM:n  ( 3521): SIOP:: AP = 280, PST = 281, CUR = 66
,D/WearableService( 4650): callingUid 10014, callindPid: 4650
,D/ResourcesManager(11864): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11864): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11864): Conditions not met for autocaching.
I/MusicLeanback(11864): Stop autocaching.
D/WearableClient(11864): WearableClientImpl.onPostInitHandler: done
,D/PackageManager( 3521): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/WearableClient(11864): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11864): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11864): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11864): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11864): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11864): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@21d70ec0 that was originally bound here
E/ActivityThread(11864): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@21d70ec0 that was originally bound here
E/ActivityThread(11864): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11864): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11864): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11864): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11864): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11864): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11864): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11864): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11864): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11864): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11864): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11864): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11864): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11864): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11864): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11864): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11864): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11864): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11864): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11864): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11864): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11864): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11864): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11864): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11864): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2844): QcRouteController
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,V/        ( 2844): QcRouteController
,W/NetworkManagementService( 3521): route cmd failed: 
W/NetworkManagementService( 3521): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3521): '
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3521): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3521): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3521): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6651): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6651): CM callback handler got msg 524295
,I/PowerManagerService( 3521): [PWL] Off : 50s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:76
D/BatteryService( 3521): stay LED for fully charged
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 145693
,D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
,D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{10060}) (elapsedTime=3485)
,I/GAV4    (12140): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11896): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver(11826): mConnectivityHandler : connected
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/PCWCLIENTTRACE_AccountUtil(11826): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11826): ================================================
,I/CSTORAGE(11826):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11826): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11826): [GetString-S]
,E/art     (11826): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11826): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11826): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11826): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11826): sales region : global
I/PCWCLIENTTRACE_PushUtil(11826): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11826): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11896): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11896): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12288): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12288): exit::IDLE
D/PreloadUpdateManagerStateMachine(12288): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12288): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12288): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12288): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12288): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12288): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12288): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12288): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12288): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12288): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12288): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12288): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12288): entry::IDLE
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 278, CUR = 33
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{f19ef0f u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3521): !@Sync 5
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 276, CUR = 56
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 75s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 275, CUR = 61
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4650): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 274, CUR = 59
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 6
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 271, CUR = 56
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 105s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 266, CUR = 52
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 264, CUR = 51
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3521): !@Sync 7
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 263, CUR = 49
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged,
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 260, CUR = 47
,I/PowerManagerService( 3521): [PWL] Off : 140s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 259, CUR = 45,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 8
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 258, CUR = 43
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3521): waitForAlarm result :8
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 257, CUR = 43,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 180s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 255, CUR = 41
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 9
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 254, CUR = 40,

```
