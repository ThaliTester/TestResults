#### Test 54968200254eab2_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3524): !@Sync 4
D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 246, CUR = 38
D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
D/BatteryService( 3524): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11865): 
D/AndroidRuntime(11865): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11865): CheckJNI is OFF
D/AndroidRuntime(11865): readGMSProperty: start
D/AndroidRuntime(11865): readGMSProperty: already setted!!
D/AndroidRuntime(11865): readGMSProperty: end
D/AndroidRuntime(11865): addProductProperty: start
E/AffinityControl(11865): AffinityControl: registerfunction enter
D/AndroidRuntime(11865): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3524): mDVFSHelper.acquire()
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (11883): MountEmulatedStorage()
E/Zygote  (11883): v2
I/libpersona(11883): KNOX_SDCARD checking this for 10531
I/libpersona(11883): KNOX_SDCARD not a persona
I/SELinux (11883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11883 uid=10531 gids={50531, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11883): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11865): Shutting down VM
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11883): TimaSignature is unavailable
D/ActivityThread(11883): Added TimaKeyStore provider
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11883): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6309): updateVisibility : ActivityRecord{1474e2d5 token=android.os.BinderProxy@177b495e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11883): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11883): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11883): Loading: webviewchromium
I/LibraryLoader(11883): Time to load native libraries: 4 ms (timestamps 5125-5129)
I/LibraryLoader(11883): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11883): Binding Chromium to main looper Looper (main, tid 1) {d2bf91c}
I/LibraryLoader(11883): Expected native library version number "",actual native library version number ""
I/chromium(11883): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11883): Initializing chromium process, renderers=0
,W/art     (11883): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11883): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11883): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11883): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11883): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11883): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11883): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11883): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11883): CordovaWebView is running on device made by: samsung
,W/art     (11883): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11883): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11883): performCreate Call secproduct feature valuefalse
D/Activity(11883): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11883): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer(11883): Initialized EGL, version 1.4
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11883): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1279692528 
,D/OpenGLRenderer(11883): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11883): Enabling debug mode 0
,D/mali_winsys(11883): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11883): updateVisibility : ActivityRecord{166de14c token=android.os.BinderProxy@3ec1d633 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{18fb928c u0 com.test.thalitest/.MainActivity t26} time:135490
,W/IInputConnectionWrapper(11883): showStatusIcon on inactive InputConnection
,I/Timeline(11883): Timeline: Activity_idle id: android.os.BinderProxy@3ec1d633 time:135501
,D/JsMessageQueue(11883): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11883): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11883): 
,D/jxcore_app_log(11883): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361611008
D/JX-Cordova(11883): jxcore cordova android initializing
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11883): Initializing JXcore engine
W/jxcore-log(11883): JXcore engine is ready
,W/jxcore-log(11883): Starting JXcore engine
,E/auditd  ( 4618): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11883): Platform android
W/jxcore-log(11883): 
W/jxcore-log(11883): Process ARCH arm
W/jxcore-log(11883): 
,I/jxcore-log(11883): JXcore Cordova bridge is ready!
I/jxcore-log(11883): 
W/jxcore-log(11883): JXcore engine is started
,I/jxcore-log(11883): Toggling radios to true
I/jxcore-log(11883): 
,D/BluetoothAdapter(11883): enable()
,D/BluetoothAdapter(11883): enable(): BT is already enabled..!
,D/WifiService( 3524): New client listening to asynchronous messages
,I/WifiManager(11883): packageName : com.test.thalitest
D/SecContentProvider( 3524): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3524): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3524): mCursor = null
D/WifiService( 3524): setWifiEnabled: true pid=11883, uid=10531
E/WifiService( 3524): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3524): Permission Denial: getCurrentUser() from pid=11883, uid=10531 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3524): Failed getting userId using ActivityManagerNative
W/WifiService( 3524): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11883, uid=10531 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3524): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3524): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3524): name = wifi_on
,I/WifiService( 3524): disconnect: pid=11883, uid=10531
,I/wpa_supplicant( 3837): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3837): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3837): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3837): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3524): WifiStateMachine: Leaving Connected state
I/jxcore-log(11883): Radios toggled
I/jxcore-log(11883): 
I/wpa_supplicant( 3837): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3837): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3837): Disconnected - do not scan
I/wpa_supplicant( 3837): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3524): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log(11883): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11883): 
I/jxcore-log(11883): Perf Test app loaded loaded
I/jxcore-log(11883): 
I/jxcore-log(11883): check test folder
I/jxcore-log(11883): 
E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
I/jxcore-log(11883): found test : ./testFindPeers.js
I/jxcore-log(11883): 
D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
D/CommandListener( 2846): Clearing all IP addresses on wlan0
E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3524): updateNetworkInfo()
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
I/jxcore-log(11883): found test : ./testSendData.js
I/jxcore-log(11883): 
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
I/Hs20UtilService( 4075): Starting #8
,I/Hs20UtilService( 4075): Message received 5007
,D/NearbySettings( 8873): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8873): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8873): MountReceiver.onReceive - Create mPrefHandler
E/WifiStateMachine( 3524): Start Disconnecting Watchdog 1
D/NearbySettings( 8873): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3524): ConnectModeState: Network connection lost 
V/NearbySettings( 8873): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3524): New client listening to asynchronous messages
,I/NearbySettings( 8873): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8873): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8873): MountReceiver.mPrefHandler - 7002
D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11493): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3524): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524292
,E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3524): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3524): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - currTime: 1451954456807
D/CSLegacyTypeTracker( 3524): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3986): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/wpa_supplicant( 3837): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3837): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3837): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3837): First Scan Start
I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/ConnectivityManager.CallbackHandler( 6730): CM callback handler got msg 524292
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/wpa_supplicant( 3837): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3524): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3524): MasterInitialState.processMessage what=3
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
,D/ConnectivityService( 3524): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
V/NetworkStats( 3524): updateIfacesLocked()
V/NetworkStats( 3524): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3524): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
V/NetworkStats( 3524): performPollLocked() took 4ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,I/Hs20UtilService( 4075): Starting #9
D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
I/Hs20UtilService( 4075): Message received 5007
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/NearbySettings( 8873): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8873): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8873): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8873): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8873): MountReceiver.mPrefHandler - 7002
,I/chromium(11883): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SignOutReceiver(11493): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
I/chromium(11883): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3524): updateDataUsageMap
,I/ApplicationPolicy( 3524): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11978): MountEmulatedStorage()
,E/Zygote  (11978): v2
I/libpersona(11978): KNOX_SDCARD checking this for 10110
I/libpersona(11978): KNOX_SDCARD not a persona
,I/SELinux (11978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11978 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11978): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/SLocation( 3524): No Active Data Connection
,I/DBG_DM  ( 6309): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6309): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider(11978): TimaSignature is unavailable
,D/ActivityThread(11978): Added TimaKeyStore provider
,D/ResourcesManager(11978): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11978): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11978): not using cross-dex optimization: ART in use
,I/art     (11978): Thread[1,tid=11978,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11978): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11978): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(11978): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11978): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
,D/DexLibLoader(11978): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11978): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11978): loading pre-built fallback odex files
V/MultiDexClassLoader(11978): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11978): released odex store lock
,D/DexLibLoader(11978): DexLibLoader.loadAll took 43 ms
,W/ca      (11978): Verify
,W/LightSharedPreferencesImpl(11978): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11978): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11978): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11978): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11978): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11978): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11978): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11978): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11978): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11978): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11978): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11978): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11978): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11978): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11978): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11978): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11978): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11978): 	... 10 more
,W/appmanager(:<default>):b(11978): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3837): nl80211: Received scan results (12 BSSes)
,I/wpa_supplicant( 3837): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3837): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3837): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3524): [1,451,954,457,897 ms] noteScanEnd no scan source
,E/Zygote  (12020): MountEmulatedStorage()
E/Zygote  (12020): v2
I/libpersona(12020): KNOX_SDCARD checking this for 1000
I/libpersona(12020): KNOX_SDCARD not a persona
,I/SELinux (12020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12020): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12020 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 11079:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/WifiStateMachine( 3524): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3db46df1 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 867us total 22.909ms
,W/appmanager(:<default>):b(11978): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12020): TimaSignature is unavailable
,D/ActivityThread(12020): Added TimaKeyStore provider
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.027ms total 18.749ms
,D/ResourcesManager(12020): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 943us total 21.361ms
,I/wpa_supplicant( 3837): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3837): Associated with C0.AA.48
,E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/PCWCLIENTTRACE_LOG(12020): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12020): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12020): new DMDBOpenHelper instance
,I/wpa_supplicant( 3837): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/wpa_supplicant( 3837): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3837): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3837): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3837): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3837): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3837): Blacklist: Clear (temp) 
I/wpa_supplicant( 3837): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): Network connection established
,D/WifiNative-HAL( 3524): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3524): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3524): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3524): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3524): updateNetworkInfo()
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,I/PCWCLIENTTRACE_PushUtil(12020): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12020): sales region : global
I/PCWCLIENTTRACE_PushUtil(12020): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12020): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine( 3524): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3524): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/PCWCLIENTTRACE_SYSTEMReceiver(12020): noConnectivity : true
,W/appmanager(:<default>):QuickExperimentControllerImpl(11978): Exposure of experiment com.facebook.common.network.l@18b76e40 occurred when no user was logged in
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{250a74a1 u0 ReceiverList{29007508 11978 com.facebook.appmanager/10110/u0 remote:17dc2aab}}
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{250a74a1 u0 ReceiverList{29007508 11978 com.facebook.appmanager/10110/u0 remote:17dc2aab}}
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/CommandListener( 2846): Setting iface cfg
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3524): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,E/Zygote  (12047): MountEmulatedStorage()
,E/Zygote  (12047): v2
I/libpersona(12047): KNOX_SDCARD checking this for 10135
I/libpersona(12047): KNOX_SDCARD not a persona
,I/SELinux (12047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12047): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12047 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11096:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12047): TimaSignature is unavailable
,D/ActivityThread(12047): Added TimaKeyStore provider
,D/ResourcesManager(12047): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3a9e4795 u0 ReceiverList{294cab4c 11978 com.facebook.appmanager/10110/u0 remote:1ae1ff7f}}
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  ( 3524): do suspend false
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/MusicStore(12047): Database version: 104
,D/ResourcesManager(12047): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12047): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(12047): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12047): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12047): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12047): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@60b0ab0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12047): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12047): GMSCore installation verified
,I/ConfigStore(12047): Config Database version: 1
,E/dhcpcd  (12079): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12079): version 5.5.6 starting
,E/dhcpcd  (12079): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12047): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11978): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11978): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/dhcpcd  (12079): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12079): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12079): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12079): bssid match
,I/dhcpcd  (12079): wlan0: rebinding lease of 192.168.1.124
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12047): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12047): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11978): Exposure of experiment com.facebook.imagepipeline.a.g@38fdf543 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11978): Exposure of experiment com.facebook.imagepipeline.a.d@f4bdfec occurred when no user was logged in
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3524): getStreamVolume 3 index 0
,I/MediaRouter(12047): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12088): MountEmulatedStorage()
E/Zygote  (12088): v2
I/libpersona(12088): KNOX_SDCARD checking this for 10002
I/libpersona(12088): KNOX_SDCARD not a persona
,I/SELinux (12088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12088 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (11978): Explicit concurrent mark sweep GC freed 50051(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.565ms total 60.404ms
,W/appmanager(:<default>):m(11978): No feature status reporters found; is this dead code?
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(12047): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12088): TimaSignature is unavailable
,I/ActivityManager( 3524): Killing 11111:com.policydm/1000 (adj 15): bgCount ##31
D/ActivityThread(12088): Added TimaKeyStore provider
,D/ResourcesManager(12088): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3524): Killing 11126:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12109): MountEmulatedStorage()
I/libpersona(12109): KNOX_SDCARD checking this for 1000
E/Zygote  (12109): v2
I/libpersona(12109): KNOX_SDCARD not a persona
,I/SELinux (12109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12109): TimaSignature is unavailable
,D/ActivityThread(12109): Added TimaKeyStore provider
,D/ResourcesManager(12109): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 61147(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 1.996ms total 154.800ms
,I/DIAGMON_AGENT(12109): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12109): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12109): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12109): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12109): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12127): MountEmulatedStorage()
E/Zygote  (12127): v2
I/libpersona(12127): KNOX_SDCARD checking this for 10012
I/libpersona(12127): KNOX_SDCARD not a persona
,I/SELinux (12127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12127): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12127 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12127): TimaSignature is unavailable
,D/ActivityThread(12127): Added TimaKeyStore provider
,D/ResourcesManager(12127): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3524): Killing 11159:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(12127): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/dhcpcd  (12079): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/FOTA_Client(12127): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12127): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/dhcpcd  (12079): wlan0: leased 192.168.1.124 for 86400 seconds
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Zygote  (12145): MountEmulatedStorage()
E/Zygote  (12145): v2
I/libpersona(12145): KNOX_SDCARD checking this for 10021
I/libpersona(12145): KNOX_SDCARD not a persona
,I/SELinux (12145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12145 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 10960:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/10960/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12145): TimaSignature is unavailable
,D/ActivityThread(12145): Added TimaKeyStore provider
,D/ResourcesManager(12145): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12145): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:40:59 GMT+01:00 2016
,I/KLMS-2.4.521: (12145): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12145): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12145): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12145): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  (12170): MountEmulatedStorage()
E/Zygote  (12170): v2
I/libpersona(12170): KNOX_SDCARD checking this for 10038
I/libpersona(12170): KNOX_SDCARD not a persona
,I/SELinux (12170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12145): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 3524): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12170 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12170): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12145): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3524): Killing 11147:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12170): TimaSignature is unavailable
,D/ActivityThread(12170): Added TimaKeyStore provider
,D/ResourcesManager(12170): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12170): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12193): MountEmulatedStorage()
,E/Zygote  (12193): v2
I/libpersona(12193): KNOX_SDCARD checking this for 1000
I/libpersona(12193): KNOX_SDCARD not a persona
,I/SELinux (12193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12193 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12193): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11205:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12193): TimaSignature is unavailable
,D/ActivityThread(12193): Added TimaKeyStore provider
,D/ResourcesManager(12193): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend true
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3524): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3524): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3524): Not connected state, yet.
E/WifiStateMachine( 3524): VerifyingLinkState enter
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/WifiStateMachine( 3524): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3524): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3524): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3524): callSECApiInt - ID [210]
,E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3524): updateNetworkInfo()
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3524): Adding iface wlan0 to network 503
,E/Zygote  (12216): MountEmulatedStorage()
E/Zygote  (12216): v2
I/libpersona(12216): KNOX_SDCARD checking this for 10039
I/libpersona(12216): KNOX_SDCARD not a persona
,I/SELinux (12216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12216 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12216): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11239:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/WifiWatchdogStateMachine( 3524): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3524): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3524): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3524): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/WifiStateMachine( 3524): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3524): Now, connected state.
E/WifiStateMachine( 3524): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/ConnectivityService( 3524): Unexpected mtu value: 0, wlan0
E/WifiStateMachine( 3524): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,V/        ( 2846): QcRouteController
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3524): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiNative-HAL( 3524): callSECApiVoid - ID [212]
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3524): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider(12216): TimaSignature is unavailable
,D/ActivityThread(12216): Added TimaKeyStore provider
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,V/        ( 2846): QcRouteController
,D/ResourcesManager(12216): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,D/ConnectivityService( 3524): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3524): LTETest block dns file not exists
,D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3524): updateNetworkInfo()
E/ConnectivityService( 3524): updateNetworkInfo()
,D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3524): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,E/SPPClientService(12216): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12216): [PushClientApplication] Push log off : This is Ship build version
,D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Checking http://clients3.google.com/generate_204 on "NG700"
,D/SPPClientService(12216): PushLog.txt file is not deleted.
D/SPPClientService(12216): PushLog.txt file is not deleted.
D/SPPClientService(12216): ============PushLog. stop!
,D/ConnectivityService( 3524):    accepting network in place of null
E/SPPClientService(12216): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/TelephonyNetworkFactory( 3986): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3524): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3524): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3524): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,I/SA      (11298): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,D/ConnectivityService( 3524): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3524): MasterInitialState.processMessage what=3
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
E/SPPClientService(12216): [[SystemStateMonitorService]] No Active Internet
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,V/NetworkStats( 3524): updateIfacesLocked()
V/NetworkStats( 3524): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,I/SA      (11298): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      (11298): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/NetworkStatsFactory( 3524): UpdateStatsForKnox
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/SA      (11298): [SLFUCHKMGR] constructor called
,V/NetworkStats( 3524): performPollLocked() took 8ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 6730): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,I/SA      (11298): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11298): [OR] == isSIMCardReady false ==
,I/SA      (11298): [SCU] == networkStateCheck == true
,I/SA      (11298): [DM] getCountryCodeFromCSC : PL
I/SA      (11298): isChinaCountryCode : false
I/SA      (11298): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11298): [OR] == networkStateCheck true ==
,I/SA      (11298): [OR] GetMyCountryZoneTask
I/SA      (11298): [OR] onReceive END
,I/SA      (11298): [SRS] prepareGetMyCountryZone
,I/ActivityManager( 3524): Killing 11219:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,V/DownloadManager( 5747): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11298): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11298): [SSP] query invoked
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/SA      (11298): [TPMU] GetMccFromDB : null
I/SA      (11298): [SCU] getMccFromPreferece mcc = 260
I/SA      (11298): [TPM] isNoProxy(default) : true
,E/Zygote  (12257): MountEmulatedStorage()
,E/Zygote  (12257): v2
I/libpersona(12257): KNOX_SDCARD checking this for 10067
I/libpersona(12257): KNOX_SDCARD not a persona
,I/SELinux (12257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12257 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/System.out( 3524): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/SELinux (12257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12257): TimaSignature is unavailable
,D/ActivityThread(12257): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:40:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954459902], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954459884]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Validated
D/ConnectivityService( 3524): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6730): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/ResourcesManager(12257): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/sCloudBackupApp(12257): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12257): Other Intent
,I/ActivityManager( 3524): Killing 11262:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11262/oom_score_adj; errno=22
,D/accuweather( 5210): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5210): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5210): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5210): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5210): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5210): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5210): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,V/AlarmManager( 3524): waitForAlarm result :8
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12274): MountEmulatedStorage()
I/libpersona(12274): KNOX_SDCARD checking this for 1000
E/Zygote  (12274): v2
I/libpersona(12274): KNOX_SDCARD not a persona
,I/SELinux (12274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12274): TimaSignature is unavailable
,D/ActivityThread(12274): Added TimaKeyStore provider
,D/ResourcesManager(12274): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12274): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12274): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12274): premStatus:2
,I/KnoxUsageLogPro(12274): isEulaShown : false
I/KnoxUsageLogPro(12274): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12289): MountEmulatedStorage()
E/Zygote  (12289): v2
I/libpersona(12289): KNOX_SDCARD checking this for 10090
,I/libpersona(12289): KNOX_SDCARD not a persona
I/SELinux (12289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12289 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12289): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11187:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 856us total 21.990ms
,D/TimaKeyStoreProvider(12289): TimaSignature is unavailable
,D/ActivityThread(12289): Added TimaKeyStore provider
,D/ResourcesManager(12289): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 830us total 18.505ms
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 312us total 9.480ms
,I/SA      (11298): [RC New] Execute method=[GET] start
,I/SA      (11298): [RC New] Security=[true]
,I/System.out(11298): Thread-1560(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11298): Thread-1560(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11298): Thread-1560(ApacheHTTPLog):isShipBuild true
I/System.out(11298): Thread-1560(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12306): MountEmulatedStorage()
E/Zygote  (12306): v2
I/libpersona(12306): KNOX_SDCARD checking this for 10127
I/libpersona(12306): KNOX_SDCARD not a persona
,I/SELinux (12306): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12306 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12306): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Killing 11354:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
E/SELinux (12306): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12306): TimaSignature is unavailable
,D/ActivityThread(12306): Added TimaKeyStore provider
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager(12306): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3524): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3524): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6309): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6309): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 5337): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5337): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(12047): type=WIFI subType= reason=null isConnected=true
,D/KeyguardWallpaperUpdator(12306): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12306): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12306): stopCheckCategoryVersion
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12323): MountEmulatedStorage()
E/Zygote  (12323): v2
I/libpersona(12323): KNOX_SDCARD checking this for 10136
I/libpersona(12323): KNOX_SDCARD not a persona
,I/SELinux (12323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12323 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12323): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,I/ActivityManager( 3524): Killing 11339:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12323): TimaSignature is unavailable
,D/ActivityThread(12323): Added TimaKeyStore provider
,D/ResourcesManager(12323): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12323): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12323): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12323): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12323): Loading: webviewchromium
,I/LibraryLoader(12323): Time to load native libraries: 4 ms (timestamps 1606-1610)
I/LibraryLoader(12323): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12323): Binding Chromium to main looper Looper (main, tid 1) {22be51ba}
,I/LibraryLoader(12323): Expected native library version number "",actual native library version number ""
I/chromium(12323): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12323): Initializing chromium process, renderers=0
,W/art     (12323): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12323): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12323): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12323): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12323): Requires BLUETOOTH permission
,D/ConnectivityService( 3524): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/NSApplication(12323): Starting up...
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12390): MountEmulatedStorage()
E/Zygote  (12390): v2
I/libpersona(12390): KNOX_SDCARD checking this for 10150
I/libpersona(12390): KNOX_SDCARD not a persona
,I/SELinux (12390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12390 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11374:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12390): TimaSignature is unavailable
,D/ActivityThread(12390): Added TimaKeyStore provider
,D/ResourcesManager(12390): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12390): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12390): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12390): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12390): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12390): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12405): MountEmulatedStorage()
E/Zygote  (12405): v2
I/libpersona(12405): KNOX_SDCARD checking this for 10178
I/libpersona(12405): KNOX_SDCARD not a persona
,I/SELinux (12405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12405 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (12405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11390:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12405): TimaSignature is unavailable
,D/ActivityThread(12405): Added TimaKeyStore provider
,D/ResourcesManager(12405): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12405): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12405): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12405): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12405): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12405): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12405): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SA      (11298): [RC New] [v2liruge] api execute + 946
I/SA      (11298): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11298): AsyncTask #1 calls detatch()
,I/SA      (11298): [TPMU] getNetworkMcc : 
,I/SA      (11298): [SCU] saveMccToPreferece Start
I/SA      (11298): [SCU] RegionMCC : 260
I/SA      (11298): [SSP] query invoked
,I/SA      (11298): [TPMU] GetMccFromDB : null
I/SA      (11298): [SCU] getMccFromPreferece mcc = 260
I/SA      (11298): [SCU] saveMccToPreferece End
,I/SA      (11298): [RC New] executeRequest [v2liruge] end. 975
I/SA      (11298): [RC New] Execute end
I/SA      (11298): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11298): [OR] GetMyCountryZoneTask Success
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/Zygote  (12428): MountEmulatedStorage()
E/Zygote  (12428): v2
I/libpersona(12428): KNOX_SDCARD checking this for 10082
I/libpersona(12428): KNOX_SDCARD not a persona
,I/SELinux (12428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12428 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/SELinux (12428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12428): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12442): MountEmulatedStorage()
I/libpersona(12442): KNOX_SDCARD checking this for 1000
E/Zygote  (12442): v2
I/libpersona(12442): KNOX_SDCARD not a persona
I/SELinux (12442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Killing 11407:com.samsung.helphub/1000 (adj 13): bgCount ##31
E/SELinux (12442): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12428): TimaSignature is unavailable
,D/ActivityThread(12428): Added TimaKeyStore provider
,I/ActivityManager( 3524): Killing 11513:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12442): TimaSignature is unavailable
,D/ActivityThread(12442): Added TimaKeyStore provider
,D/ResourcesManager(12428): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12442): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12428): onCreate
D/BadgeProvider(12428): DatabaseHelper
,I/ActivityManager( 3524): Killing 11531:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12428): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 3524): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12428): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12428): sendNotify, [notify] : null
D/BadgeProvider(12428): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12428): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12428): update, [UpdateCount] : 1
D/Launcher.Model( 4004): reloadBadges entered.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12461): MountEmulatedStorage()
I/libpersona(12461): KNOX_SDCARD checking this for 10013
E/Zygote  (12461): v2
I/libpersona(12461): KNOX_SDCARD not a persona
,I/SELinux (12461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12461 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12461): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12461): TimaSignature is unavailable
,D/ActivityThread(12461): Added TimaKeyStore provider
,D/ResourcesManager(12461): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12461): notifyNetworkActivated
,W/ContextImpl(12461): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3524): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12461): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12461): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12461): exit::IDLE
D/InitializeManagerStateMachine(12461): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12461): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12461): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12461): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12461): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12461): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12461): entry::SUCCESS
D/hcjo    (12461): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12461): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12461): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12461): exit::SUCCESS
D/InitializeManagerStateMachine(12461): entry::IDLE
,I/Hs20UtilService( 4075): Starting #10
,I/Hs20UtilService( 4075): Message received 5007
,I/ActivityManager( 3524): Killing 11548:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/NearbySettings( 8873): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8873): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8873): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8873): MountReceiver.onReceive - Keep current state
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11883): BLE supported!!
I/jxcore-log(11883): 
,I/SignOutReceiver(11493): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4075): Starting #11
,I/Hs20UtilService( 4075): Message received 5007
,D/NearbySettings( 8873): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8873): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11493): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4075): Starting #12
,I/Hs20UtilService( 4075): Message received 5007
,D/NearbySettings( 8873): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8873): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8873): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8873): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8873): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11493): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4075): Starting #13
,I/Hs20UtilService( 4075): Message received 5007
,D/NearbySettings( 8873): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8873): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3524): callSECApi what=220
D/WifiStateMachine( 3524): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11493): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(12020): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12020): sales region : global
I/PCWCLIENTTRACE_PushUtil(12020): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12020): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2850): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3524): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524
,I/DIAGMON_AGENT(12109): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12109): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/mali_winsys( 3690): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(12127): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12127): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12127): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12145): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:41:01 GMT+01:00 2016
,I/KLMS-2.4.521: (12145): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12145): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12145): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12145): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(12170): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12145): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12145): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12145): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12145): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12145): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onDestroy()
,E/SPPClientService(12216): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11298): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11298): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11298): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11298): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11298): [OR] == isSIMCardReady false ==
,I/SA      (11298): [SCU] == networkStateCheck == true
I/SA      (11298): [DM] getCountryCodeFromCSC : PL
I/SA      (11298): isChinaCountryCode : false
I/SA      (11298): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11298): [OR] == networkStateCheck true ==
I/SA      (11298): [OR] GetMyCountryZoneTask
,I/SA      (11298): [OR] onReceive END
,I/SA      (11298): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5747): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11298): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11298): [SSP] query invoked
,I/SCloudBackupReceiver(12257): Other Intent
,I/SA      (11298): [TPMU] GetMccFromDB : null
I/SA      (11298): [SCU] getMccFromPreferece mcc = 260
I/SA      (11298): [TPM] isNoProxy(default) : true
,I/SA      (11298): [RC New] Execute method=[GET] start
,D/accuweather( 5210): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5210): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5210): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5210): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5210): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5210): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5210): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12274): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12274): premStatus:2
,I/KnoxUsageLogPro(12274): isEulaShown : false
I/KnoxUsageLogPro(12274): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12306): cancelUpdateWallpaper
,I/SA      (11298): [RC New] Security=[true]
,D/KeyguardWallpaperUpdator(12306): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12306): stopCheckCategoryVersion
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/QuickConnect(12390): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12390): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12390): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/hcjo    (12461): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12461): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine(12461): exit::IDLE
D/InitializeManagerStateMachine(12461): entry::NETWORK_CHECK
D/InitializeManagerStateMachine(12461): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12461): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12461): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12461): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12461): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12461): entry::SUCCESS
D/hcjo    (12461): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12461): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12461): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12461): exit::SUCCESS
,D/InitializeManagerStateMachine(12461): entry::IDLE
,I/dhcpcd  (12079): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12079): wlan0: sendmsg: Cannot assign requested address
,I/SA      (11298): [RC New] [v2liruge] api execute + 660
,I/SA      (11298): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11298): AsyncTask #2 calls detatch()
,I/SA      (11298): [TPMU] getNetworkMcc : 
,I/SA      (11298): [SCU] saveMccToPreferece Start
,I/SA      (11298): [SCU] RegionMCC : 260
,I/SA      (11298): [SSP] query invoked
,I/SA      (11298): [TPMU] GetMccFromDB : null
,I/SA      (11298): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11298): [SCU] saveMccToPreferece End
,I/SA      (11298): [RC New] executeRequest [v2liruge] end. 779
,I/SA      (11298): [RC New] Execute end
,I/SA      (11298): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11298): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3524): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 244, CUR = 58
,I/PowerManagerService( 3524): [PWL] Off : 50s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 218, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3524): route cmd failed: 
W/NetworkManagementService( 3524): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3524): '
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3524): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6730): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6730): CM callback handler got msg 524295
,D/WearableService( 4668): callingUid 10014, callindPid: 4668
,D/ResourcesManager(12047): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12047): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(12047): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12047): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12047): Conditions not met for autocaching.
,I/MusicLeanback(12047): Stop autocaching.
,D/WearableClient(12047): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12047): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12047): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12047): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12047): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12047): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12047): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@779487a that was originally bound here
E/ActivityThread(12047): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@779487a that was originally bound here
E/ActivityThread(12047): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12047): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12047): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12047): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12047): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12047): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12047): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12047): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12047): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12047): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12047): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12047): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12047): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12047): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12047): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12047): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12047): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12047): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12047): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12047): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12047): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12047): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12047): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12047): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12047): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager( 3524): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3524): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3524) eventTime = 146283
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524 (0x0)
,D/PowerManagerService( 3524): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3524, ws=WorkSource{10060}) (elapsedTime=3506)
,I/GAV4    (12323): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 51167(3MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 48MB/64MB, paused 3.465ms total 244.543ms
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (12079): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver(12020): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(12020): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(12020): ================================================
I/CSTORAGE(12020):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12020): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12020): [GetString-S]
E/art     (12020): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(12020): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12020): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12020): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12020): sales region : global
I/PCWCLIENTTRACE_PushUtil(12020): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12020): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12079): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12079): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12461): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12461): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12461): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12461): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12461): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12461): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12461): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12461): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12461): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12461): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12461): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12461): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12461): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12461): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12461): entry::IDLE
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 241, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 5
,D/SSRM:n  ( 3524): SIOP:: AP = 220, PST = 238, CUR = 49
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 75s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 220, PST = 236, CUR = 54
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4668): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3524): SIOP:: AP = 220, PST = 235, CUR = 53
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 6
,D/SSRM:n  ( 3524): SIOP:: AP = 220, PST = 230, CUR = 50
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 105s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 225, CUR = 47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 222, CUR = 43
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 219, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3524): !@Sync 7
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 220, CUR = 41
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 140s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 217, CUR = 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 215, CUR = 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 8
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 214, CUR = 37
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 213, CUR = 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 180s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 212, CUR = 34
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 9
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 211, CUR = 33
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11883): Connected to the server!
I/jxcore-log(11883): 
,I/chromium(11883): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 211, CUR = 33
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 32
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 3524): initializing...
,I/TLC_TIMA_PKM_initialize( 3524): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3524): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3524): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3524): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3524): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3524): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 3524): device_id = 0x0
I/TZ: mc_tlc_communication( 3524): tlc_open() was called
,I/TZ: mc_tlc_communication( 3524): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3524): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3524): Opening the session
,I/TZ: mc_tlc_communication( 3524): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3524): Trustlet response is completed
,E/Watchdog( 3524): !@Sync 10
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 31
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 225s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 11
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 29
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 29
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 210, PST = 210, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 275s ago
,E/Watchdog( 3524): !@Sync 12
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 209, CUR = 27
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 209, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 207, CUR = 28
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 13
,I/jxcore-log(11883): --- start :testFindPeers.js---
I/jxcore-log(11883): 
,I/jxcore-log(11883): testFindPeers created [object Object]
I/jxcore-log(11883): 
,I/jxcore-log(11883): serverPort is 8876
I/jxcore-log(11883): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT706
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11883): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11883): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11883): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/BluetoothSocket(11883): bindListen(), new LocalSocket 
D/BluetoothSocket(11883): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11883): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21d81cf3
,D/BluetoothSocket(11883): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): start: OK
,I/io.jxcore.node.ConnectionHelper(11883): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT706
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11883): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11883): bind: Binding a new listener
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 207, CUR = 27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11883): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11883): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3524): InactiveState{ what=139292 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3524): P2pEnabledState add service
,D/WifiP2pService( 3524): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(11883): start: OK
,D/WifiP2pService( 3524): InactiveState{ what=139265 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139265 }
,I/jxcore-log(11883): StartBroadcasting started ok
I/jxcore-log(11883): 
D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,I/io.jxcore.node.ConnectionHelper(11883): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onWifiStateChanged: State changed to 2
,I/io.jxcore.node.ConnectionHelper(11883): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11883): Local service added successfully
D/WifiP2pService( 3524): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: STARTED
I/chromium(11883): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3524): P2pEnabledState discover services
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-5 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 206, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true,
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 330s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 206, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 14
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 205, CUR = 27
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: RESTARTING,
,D/WifiP2pService( 3524): InactiveState{ what=139268 }
,I/wpa_supplicant( 3837): P2P-FIND-STOPPED 
,D/WifiP2pService( 3524): InactiveState{ what=147493 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3524): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,V/AlarmManager( 3524): waitForAlarm result :8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): Start timer timeout, starting now...
,D/WifiP2pService( 3524): InactiveState{ what=139265 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139265 }
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: STARTED
,D/WifiP2pService( 3524): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 8 device(s) discovered
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 3524): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 3524): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager(11883): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 205, CUR = 26,
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3837): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/wpa_supplicant( 3837): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3837): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 ,
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1,
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 },
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] is available
,I/jxcore-log(11883): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT818","peerAvailable":true}]
I/jxcore-log(11883): 
,I/jxcore-log(11883): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(11883): 
,I/jxcore-log(11883): weAreDoneNow
I/jxcore-log(11883): 
,I/jxcore-log(11883): done, now sending data to server
I/jxcore-log(11883): 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 },
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] is available
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3524): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] is available
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 204, CUR = 27
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] is available
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
D/WifiP2pManager(11883): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1,
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] is available
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] is available
,E/Watchdog( 3524): !@Sync 15
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 204, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3524): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiP2pManager(11883): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-5 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147494 },
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 203, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3524): P2pEnabledState receive service response
D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiP2pService( 3524): InactiveState{ what=139283 }
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 3524): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) e,e:1f:72:18:8b:78
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiP2pService( 3524): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 3524): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/PowerManagerService( 3524): [PWL] Off : 390s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 203, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-5 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] is available
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] already in the list, will not add again
,D/WifiP2pService( 3524): InactiveState{ what=147494 },
D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3524): P2pEnabledState receive service response,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78,
D/WifiP2pService( 3524): InactiveState{ what=147494 }
,W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again
,E/Watchdog( 3524): !@Sync 16
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 202, CUR = 22
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.,
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 3524): InactiveState{ what=139307 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3524): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 202, CUR = 23
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc,
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 201, CUR = 25
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper(11883): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] is available
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 17
,I/jxcore-log(11883): teardown
I/jxcore-log(11883): 
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 201, CUR = 24
,I/jxcore-log(11883): testFindPeers stopped
I/jxcore-log(11883): 
,I/io.jxcore.node.ConnectionHelper(11883): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11883): shutdown
,D/BluetoothSocket(11883): close() in, this: android.bluetooth.BluetoothSocket@23cd954f, channel: 6, state: LISTENING
,D/BluetoothSocket(11883): close() this: android.bluetooth.BluetoothSocket@23cd954f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21d81cf3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c20d4dcmSocket: android.net.LocalSocket@8fdd9e5 impl:android.net.LocalSocketImpl@1897bcba fd:FileDescriptor[115]
,D/BluetoothSocket(11883): Closing mSocket: android.net.LocalSocket@8fdd9e5 impl:android.net.LocalSocketImpl@1897bcba fd:FileDescriptor[115]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11883): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): stop: Stopping services
,D/WifiP2pService( 3524): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3524): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3524): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11883): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setState: NOT_STARTED
,I/jxcore-log(11883): StopBroadcasting went ok
I/jxcore-log(11883): 
,D/WifiP2pService( 3524): InactiveState{ what=139268 }
,I/wpa_supplicant( 3837): P2P-FIND-STOPPED 
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState clear service request
,I/io.jxcore.node.ConnectionHelper(11883): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper(11883): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11883): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery stopped successfully
,D/WifiP2pService( 3524): remove channel information from framework
,D/WifiP2pService( 3524): InactiveState{ what=147493 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3524): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service requests cleared successfully
,I/chromium(11883): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log(11883): --- start :testSendData.js---
I/jxcore-log(11883): 
,I/jxcore-log(11883): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log(11883): 
,I/jxcore-log(11883): daya100000
I/jxcore-log(11883): 
,I/jxcore-log(11883): check server
I/jxcore-log(11883): 
I/jxcore-log(11883): serverPort is 35267
I/jxcore-log(11883): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT706
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): initialize: My bluetooth address is E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11883): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter(11883): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket(11883): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket(11883): bindListen(), new LocalSocket 
D/BluetoothSocket(11883): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11883): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@135462c8
D/BluetoothSocket(11883): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): start: OK
I/io.jxcore.node.ConnectionHelper(11883): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11883): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): start: Peer ID: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT706
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11883): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11883): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11883): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3524): InactiveState{ what=139292 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): start: Starting P2P device discovery...
D/WifiP2pService( 3524): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setState: RUNNING
D/WifiP2pService( 3524): P2pEnabledState add service
I/io.jxcore.node.ConnectionHelper(11883): start: OK
D/WifiP2pService( 3524): add a new client
,I/jxcore-log(11883): StartBroadcasting started ok
I/jxcore-log(11883): 
,I/jxcore-log(11883): null
I/jxcore-log(11883): 
,D/WifiP2pService( 3524): InactiveState{ what=139265 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3524): callSECApi what=74
D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log(11883): 2016-01-05T00:47:24.058Z SendDataTCPServer.js: TCP/IP server is bound to port: 35267
I/jxcore-log(11883): 
,D/WifiP2pService( 3524): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(11883): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper(11883): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11883): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: STARTED
,I/chromium(11883): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 3524): InactiveState{ what=139268 }
I/wpa_supplicant( 3837): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery stopped successfully
,D/WifiP2pService( 3524): InactiveState{ what=147493 }
D/WifiP2pService( 3524): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3524): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: RESTARTING
D/WifiP2pService( 3524): InactiveState{ what=139268 }
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): Start timer timeout, starting now...
,D/WifiP2pService( 3524): InactiveState{ what=139265 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139265 }
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3837): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService( 3524): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3837): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3837): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.,
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 201, CUR = 24
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 },
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
D/WifiP2pManager(11883): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=139310 },
D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,D/WifiP2pService( 3524): InactiveState{ what=147494 },
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 23
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,I/PowerManagerService( 3524): [PWL] Off : 455s ago,
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3524): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=147494 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 3524): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753],
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper(11883): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper(11883): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,E/Watchdog( 3524): !@Sync 18
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 23
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 22
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0,
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/WifiP2pService( 3524): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3524): P2pEnabledState add service request
D/WifiP2pManager(11883): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 3524): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 19
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 22
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: RESTARTING,
,D/WifiP2pService( 3524): InactiveState{ what=139268 }
,I/wpa_supplicant( 3837): P2P-FIND-STOPPED 
,D/WifiP2pService( 3524): InactiveState{ what=147493 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3524): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 21,
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): Start timer timeout, starting now...
,D/WifiP2pService( 3524): InactiveState{ what=139265 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139265 }
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: STARTED
,D/WifiP2pService( 3524): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
,D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): restart: Restarting...
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): InactiveState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3524): P2pEnabledState add service request
,D/WifiP2pManager(11883): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service request added successfully
,D/WifiP2pService( 3524): InactiveState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3524): P2pEnabledState discover services
,D/WifiService( 3524): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3524): callSECApi what=74
,D/WifiStateMachine( 3524): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3524): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3837): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service discovery started successfully
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3837): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=147477 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3524): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiDisplayController( 3524): Received list of peers.
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3524): DefaultState{ what=139283 }
,D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/WifiDisplayController( 3524): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 3524):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 3524):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 3524):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3524): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3524):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3524):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3524):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3524): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 3524):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/WifiDisplayController( 3524):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiDisplayController( 3524):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3524):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 3524):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3524): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 9: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 3524): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 20,
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 525s ago
,I/jxcore-log(11883): timeout now
I/jxcore-log(11883): 
,I/jxcore-log(11883): weAreDoneNow, resultArray.length: 0
I/jxcore-log(11883): 
,I/jxcore-log(11883): sendReportNow
I/jxcore-log(11883): 
,I/jxcore-log(11883): done, now sending data to server
I/jxcore-log(11883): 
,I/jxcore-log(11883): 2016-01-05T00:49:04.086Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11883): 
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 20
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3524): Killing 11594:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5643): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5643): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: RESTARTING,
,D/WifiP2pService( 3524): InactiveState{ what=139268 }
,I/wpa_supplicant( 3837): P2P-FIND-STOPPED 
,D/WifiP2pService( 3524): InactiveState{ what=147493 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3524): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/Watchdog( 3524): !@Sync 21
,I/jxcore-log(11883): teardown
I/jxcore-log(11883): 
,I/jxcore-log(11883): testSendData stopped
I/jxcore-log(11883): 
,I/io.jxcore.node.ConnectionHelper(11883): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11883): shutdown
,D/BluetoothSocket(11883): close() in, this: android.bluetooth.BluetoothSocket@5e0df47, channel: 6, state: LISTENING
D/BluetoothSocket(11883): close() this: android.bluetooth.BluetoothSocket@5e0df47, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@135462c8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3cb0e374mSocket: android.net.LocalSocket@1c56609d impl:android.net.LocalSocketImpl@38a52912 fd:FileDescriptor[116],
D/BluetoothSocket(11883): Closing mSocket: android.net.LocalSocket@1c56609d impl:android.net.LocalSocketImpl@38a52912 fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11883): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11883): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11883): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11883): stop: Stopping services
,D/WifiP2pService( 3524): InactiveState{ what=139298 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3524): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): setState: NOT_INITIALIZED
,D/WifiP2pService( 3524): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11883): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11883): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11883): setState: NOT_STARTED
,I/jxcore-log(11883): StopBroadcasting went ok
I/jxcore-log(11883): 
,D/WifiP2pService( 3524): InactiveState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3524): P2pEnabledState clear service request
,D/WifiP2pService( 3524): remove channel information from framework
,I/jxcore-log(11883): 2016-01-05T00:49:24.130Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log(11883): 
,I/io.jxcore.node.ConnectionHelper(11883): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11883): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper(11883): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11883): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11883): Service requests cleared successfully
,I/chromium(11883): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log(11883): ****TEST TOOK:  ms ****
I/jxcore-log(11883): 
,I/jxcore-log(11883): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11883): 
,D/SSRM:n  ( 3524): SIOP:: AP = 200, PST = 200, CUR = 19
,D/AndroidRuntime(13239): 
D/AndroidRuntime(13239): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(13239): CheckJNI is OFF
,D/AndroidRuntime(13239): readGMSProperty: start
D/AndroidRuntime(13239): readGMSProperty: already setted!!
,D/AndroidRuntime(13239): readGMSProperty: end
D/AndroidRuntime(13239): addProductProperty: start
,E/AffinityControl(13239): AffinityControl: registerfunction enter
,D/AndroidRuntime(13239): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3524): START PACKAGE DELETE: observer{504406910}
D/PackageManager( 3524): pkg{<packageName>}
D/PackageManager( 3524): user{0}
D/PackageManager( 3524): caller{2000},
D/PackageManager( 3524): flags{3}
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3524): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3524): !@killApplicatoin: 10531, uninstall pkg
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10531 user=-1: uninstall pkg
,I/ActivityManager( 3524): Killing 11883:com.test.thalitest/u0a531 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3524):   Force finishing activity ActivityRecord{18fb928c u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3524): mDVFSHelper.acquire()
,W/PackageSettings( 3524): Skipping PackageSetting{23ab8a25 com.example.hello/10529} due to missing metadata
,I/WindowState( 3524): WIN DEATH: Window{f2349f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3524): Client connection lost with reason: 4
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10531 user=0: pkg removed
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3524):   Force finishing activity ActivityRecord{18fb928c u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3524): Duplicate finish request for ActivityRecord{18fb928c u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6309): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/art     ( 8912): Explicit concurrent mark sweep GC freed 25291(1473KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.152ms total 48.094ms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6309): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
,E/SamsungIME( 4501): mOCRHelper is null
,W/GeofencerStateMachine( 4668): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/InputReader( 3524): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4054): Explicit concurrent mark sweep GC freed 31032(1923KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 978us total 71.684ms
,I/art     ( 6730): Explicit concurrent mark sweep GC freed 28160(1588KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.534ms total 104.437ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6309): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/LWLocationManager(11573): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11573): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (13260): MountEmulatedStorage()
E/Zygote  (13260): v2
I/libpersona(13260): KNOX_SDCARD checking this for 10063
I/libpersona(13260): KNOX_SDCARD not a persona
,I/SELinux (13260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13260 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (13260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 5337): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5337): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3524): mCursor = null
,D/EnterpriseDeviceManagerService( 3524): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3524): Admin package name: com.google.android.gms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ApplicationPolicy( 3524): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/TimaKeyStoreProvider(13260): TimaSignature is unavailable
,D/ActivityThread(13260): Added TimaKeyStore provider
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6309): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6309): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6309): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6309): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,D/ResourcesManager(11573): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/DBG_DM  ( 6309): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
,I/DBG_DM  ( 6309): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2850): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6309): updateVisibility : ActivityRecord{1474e2d5 token=android.os.BinderProxy@177b495e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager(13260): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(11573): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 79281(7MB) AllocSpace objects, 154(2MB) LOS objects, 24% free, 49MB/65MB, paused 2.200ms total 228.885ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 3524): WaitForGcToComplete blocked for 223.090ms for cause Explicit
D/VRSetupWizardStub/PackageIntentReceiver(13260): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13260): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13260): packagename:com.test.thalitest
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.521: (12145): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:49:25 GMT+01:00 2016
,D/ResourcesManager(11573): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.4.521: (12145): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onCreate()
,D/ResourcesManager(11573): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Zygote  (13279): MountEmulatedStorage()
E/Zygote  (13279): v2
I/libpersona(13279): KNOX_SDCARD checking this for 10106
I/libpersona(13279): KNOX_SDCARD not a persona
,I/SELinux (13279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13279 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (13279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (12145): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/InputMethodManagerService( 3524): Got RemoteException sending setActive(false) notification to pid 11883 uid 10531
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{5d91f59 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:646138
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/Timeline( 6309): Timeline: Activity_idle id: android.os.BinderProxy@177b495e time:646144
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11573): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3524): mCursor = null
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.521: (12145): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(13279): TimaSignature is unavailable
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ActivityThread(13279): Added TimaKeyStore provider
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/RegisteredServicesCache( 3969): empty dynamic service
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/RCPManager(12274):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3524):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524): queryAllProviders():  providerCallBack is not register for 0
,I/KLMS-2.4.521: (12145): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12145): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (12145): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13279): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/Zygote  (13297): MountEmulatedStorage()
E/Zygote  (13297): v2
I/libpersona(13297): KNOX_SDCARD checking this for 10050
I/libpersona(13297): KNOX_SDCARD not a persona
,I/SELinux (13297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux (13297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/SELinux (13297): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13297 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/elm:14491(13279): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(13279): ELMEngine.ELMEngine( context ).
D/elm:14491(13279): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11573): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(13297): TimaSignature is unavailable
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ActivityThread(13297): Added TimaKeyStore provider
,E/Zygote  (13312): MountEmulatedStorage()
E/Zygote  (13312): v2
I/libpersona(13312): KNOX_SDCARD checking this for 10183
I/libpersona(13312): KNOX_SDCARD not a persona
,I/SELinux (13312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13312 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/SELinux (13312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 13442(692KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.830ms total 222.948ms
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/SELinux (13312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11573): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11573): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11573): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11573): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (12145): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
I/art     ( 2878): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 919us total 24.071ms
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(13312): TimaSignature is unavailable
,D/ActivityThread(13312): Added TimaKeyStore provider
,D/ResourcesManager(13297): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 833us total 18.281ms
,D/ResourcesManager(11573): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourcesManager(13297): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(13297): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13297): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13297): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13297): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13297): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13297): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(13297): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     ( 2878): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 450us total 12.823ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,E/Zygote  (13327): MountEmulatedStorage()
E/Zygote  (13327): v2
I/libpersona(13327): KNOX_SDCARD checking this for 10101
I/libpersona(13327): KNOX_SDCARD not a persona
,I/SELinux (13327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SELinux (13327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13327 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13327): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12145): KLMSIntentService(): onDestroy()
,D/elm:14491(13279): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(13279): ElmAgentService : onCreate()
,D/elm:14491(13279): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(13279): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13279): MDMBridge.getInstance()
D/elm:14491(13279): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(13279): MDMBridge.getAllLicenseInfoFromSDK()
,I/ActivityManager( 3524): Killing 11613:com.android.calendar/u0a164 (adj 13): bgCount ##31
D/ResourcesManager(11573): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/TimaKeyStoreProvider(13327): TimaSignature is unavailable
,D/ActivityThread(13327): Added TimaKeyStore provider
D/ResourcesManager(13312): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(11573): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13344): MountEmulatedStorage()
E/Zygote  (13344): v2
I/libpersona(13344): KNOX_SDCARD checking this for 10019
I/libpersona(13344): KNOX_SDCARD not a persona
,I/SELinux (13344): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13344): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13344): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13344 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/PackageManager( 3524): delete codoeFile: 
,D/ResourcesManager(11573): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/elm:14491(13279): ElmAgentService : onDestroy().
,I/AASAUninstall( 3524):  com.test.thalitest not target!
,D/PackageManager( 3524): result of delete: 1{504406910}
,D/AndroidRuntime(13239): Shutting down VM
,D/TimaKeyStoreProvider(13344): TimaSignature is unavailable
,D/ActivityThread(13344): Added TimaKeyStore provider
,D/ResourcesManager(11573): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
I/ActivityManager( 3524): Killing 11573:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
E/SQLiteLog(13312): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager(13327): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(13344): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 3524): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/Zygote  (13364): MountEmulatedStorage()
E/Zygote  (13364): v2
I/libpersona(13364): KNOX_SDCARD checking this for 10190
I/libpersona(13364): KNOX_SDCARD not a persona
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/SELinux (13364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13364 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
E/SELinux (13364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(13344): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(13344): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(13344): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/ResourcesManager( 3524): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/DocsApplication(13327): Installing DEX configuration.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
D/TimaKeyStoreProvider(13364): TimaSignature is unavailable
,D/ActivityThread(13364): Added TimaKeyStore provider
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/ActivityManager( 3524): Killing 10904:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13379): MountEmulatedStorage()
E/Zygote  (13379): v2
I/libpersona(13379): KNOX_SDCARD checking this for 10022
I/libpersona(13379): KNOX_SDCARD not a persona
,I/SELinux (13379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=13379 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/SELinux (13379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11770:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/DexInstaller(13327): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/PackageInfoHelper(13327): Provided clientMode=RELEASE, packageInfo=PackageInfo{1afd96d com.google.android.apps.docs}
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/TAG     (13327): onCreate()
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/CrossAppStateProvider(13327): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(13364): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider(13379): TimaSignature is unavailable
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ActivityThread(13379): Added TimaKeyStore provider
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/NearbySource(13297): Nearby Source Create!
,D/NearbyContext(13297): Nearby Context Create!
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(13364): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13364): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/TapandpayWidget:Utils(13364): Clear T&P info.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/CrashAnrDetector( 3524): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3524): clearDefaults: com.test.thalitest
,D/TapandpayWidget:TanpandpayAppWidgetProvider(13364): Widget is not attached.
,I/ActivityManager( 3524): Killing 12428:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/RCPManagerService( 3524): PackageReceiver onReceive(),
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
I/HarmonyEASService( 3524): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,D/KnoxMUMContainerPolicy( 3524): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3524): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 3524): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
W/ContextImpl(13297): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
V/EnterpriseBillingPolicy( 3524): uID is 10531
V/EnterpriseBillingPolicy( 3524): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - enter
D/SLinkSource(13297): Samsung link source created
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(13379): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(13379): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13379): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13379): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=24_task.xml
,D/PackageBroadcastService( 6730): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6730): Clearing selected account for com.test.thalitest
,D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,D/ChimeraCfgMgr( 6730): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6730): Module APK com.google.android.play.games already loaded
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(13297): getAllContactInfoList Start
,D/ChimeraCfgMgr( 6730): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6730): Module APK com.google.android.play.games already loaded
,D/StatusBar( 3690): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
,I/LocationWidgetApplication(13379): onCreate() : start
D/LocationWidgetApplication(13379): countryCode = POLAND
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,I/LocationSettingsChecker( 6730): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 6730): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6730): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6730): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6730): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/gH_CompatibleDatabase( 6730): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6730): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6730): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/LocationManagerService( 3524): getProviders()=[]
D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(13379): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(13379): getLastUiLocationId() : mLastUiLocationId = -100
E/Zygote  (13402): MountEmulatedStorage()
I/libpersona(13402): KNOX_SDCARD checking this for 10031
E/Zygote  (13402): v2
I/libpersona(13402): KNOX_SDCARD not a persona
,I/SELinux (13402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/LocationWidgetFuctionData(13379): readDB
,I/SELinux (13402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.android.vending for preferred application com.android.vending: pid=13402 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13402): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/gH_CompatibleDatabase( 6730): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6730): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6730): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6730): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6730): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6730): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/LocationWidgetFuctionData(13379): selectedAppSize: 3
I/LocationWidgetFuctionData(13379): configPlaceList aroundMeItems
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/TimaKeyStoreProvider(13402): TimaSignature is unavailable
,D/ActivityThread(13402): Added TimaKeyStore provider
,E/Zygote  (13417): MountEmulatedStorage()
E/Zygote  (13417): v2
I/libpersona(13417): KNOX_SDCARD checking this for 10003
I/libpersona(13417): KNOX_SDCARD not a persona
,I/SELinux (13417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=13417 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,I/SELinux (13417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13417): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 4668): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4668): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4668): Shutting down VM
,E/SQLiteLog( 6730): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 6730): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 4668): FATAL EXCEPTION: main
E/AndroidRuntime( 4668): Process: com.google.android.gms.persistent, PID: 4668
E/AndroidRuntime( 4668): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4668): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4668): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4668): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4668): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4668): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4668): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4668): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4668): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4668): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4668): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4668): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4668): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4668): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4668): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4668): 	... 9 more
,E/ClearPendingStateOp( 6730): Runtime exception while performing operation
E/ClearPendingStateOp( 6730): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6730): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6730): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6730): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6730): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6730): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6730): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6730): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 6730): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6730): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6730): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6730): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6730): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6730): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6730): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6730): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6730): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6730): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6730): 	at java.lang.Thread.run(Thread.java:818)
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
E/SQLiteLog( 6730): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6730): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6730): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6730): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6730): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 6730): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6730): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6730): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6730): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3524): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3524): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3524): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3524): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3524): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/SQLiteLog( 6730): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6730): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 6730): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 6730): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(13417): TimaSignature is unavailable
,D/ActivityThread(13417): Added TimaKeyStore provider
,D/ResourcesManager(13402): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
E/SharedPreferencesImpl(13297): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
E/SQLiteLog( 6730): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6730): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 6730): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6730): Process: com.google.android.gms, PID: 6730
E/AndroidRuntime( 6730): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 6730): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6730): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6730): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6730): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6730): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6730): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Zygote  (13444): MountEmulatedStorage()
E/Zygote  (13444): v2
I/libpersona(13444): KNOX_SDCARD checking this for 10052
I/libpersona(13444): KNOX_SDCARD not a persona
,I/SELinux (13444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13444): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13444 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/DropBoxManagerService( 3524): Can't write: system_app_wtf
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3524): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.gms,
,I/EventHub( 3524): Removing device '/dev/input/event10' due to inotify event
,I/EventHub( 3524): Removing device '/dev/input/event7' due to inotify event
,D/TimaKeyStoreProvider(13444): TimaSignature is unavailable
,D/ActivityThread(13444): Added TimaKeyStore provider
,D/ResourcesManager(13417): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,W/ActivityManager( 3524): Process com.google.android.gms has crashed too many times: killing!
,I/Process ( 4668): Sending signal. PID: 4668 SIG: 9
,I/EventHub( 3524): Removing device '/dev/input/event8' due to inotify event
,I/ActivityManager( 3524): Killing 6730:com.google.android.gms/u0a14 (adj 0): crash
,I/EventHub( 3524): Removing device '/dev/input/event9' due to inotify event
,D/UserAnalysis.PlaceProvider(13417): PlaceProvider onCreate()
,D/MtpClient(13297): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(13297): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/ActivityThread(11978): Failed to find provider info for com.facebook.appmanager.installrecord
,I/EventHub( 3524): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(13444): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(13444): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(13444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(13444): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/SQLiteLog(13327): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
W/ResourcesManager(13444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13444): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(13444): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3524): Removing device '/dev/input/event12' due to inotify event
,E/SQLiteDatabase(13327): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(13327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13327): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(13327): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(13327): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13327): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13327): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13327): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13327): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13327): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13327): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13327): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(13327): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(13327): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(13327): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(13327): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(13327): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(13327): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(13327): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13327): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13327): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(13327): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(13327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(13327): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(13327): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(13327): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13327): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13327): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13327): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13327): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13327): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(13327): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13327): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(13327): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13327): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13327): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(13327): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(13327): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(13327): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(13327): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(13327): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(13327): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(13327): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(13327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(13327): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(13327): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(13327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(13327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(13327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/PowerManagerService( 3524): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10014, pid=6730, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=149)
D/ConnectivityService( 3524): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@21bcd29d)
D/ConnectivityService( 3524): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/SQLiteOpenHelper(13327): Opened ClientFlag.db in read-only mode
E/ConnectivityService( 3524): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocationManagerService( 3524): Location listener died
D/GpsStatusListenerHelper( 3524): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@27ffb312
I/LocationManagerService( 3524): remove 42a8775 by com.google.android.gms
D/LocationManagerService( 3524): Location listener died
D/WifiService( 3524): Client connection lost with reason: 4
D/LocationManagerService( 3524): provider request: passive ProviderRequest[ON interval=0]
I/LocationManagerService( 3524): remove 1e944af9 by com.google.android.gms
V/BackupManagerService( 3524): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LocationManagerService( 3524): provider request: passive ProviderRequest[ON interval=0]
V/BackupManagerService( 3524): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
I/ActivityManager( 3524): Process com.google.android.gms.persistent (pid 4668)(adj 0) has died(300,1196)
D/ContactProvider(13297): getAllContactInfoList End
,I/syncContacts(13297): thread: 1763, sync time = 523
D/UserAnalysis.SecureDbManager(13417): Key for secure DB is newly created
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 1000ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 10999ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.wearable.service.WearableControlService in 20998ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 30998ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 40998ms
I/EventHub( 3524): Removing device '/dev/input/event13' due to inotify event
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 50998ms
D/UserAnalysis.SecurePlaceDbHelper(13417): SecurePlaceDbHelper() 
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 60998ms
D/UserAnalysis.PlaceProvider(13417): Create SecureDbHelper
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 70998ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 80995ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 90995ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 100994ms
E/SQLiteLog(13327): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(13327): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(13327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13327): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(13327): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(13327): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(13327): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(13327): 	at aFp.run(Abstr,actDatabaseInstance.java:471)
E/AndroidRuntime(13327): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(13327): Process: com.google.android.apps.docs, PID: 13327
E/AndroidRuntime(13327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13327): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13327): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(13327): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(13327): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(13327): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(13327): 	at aFp.run(AbstractDatabaseInstance.java:471)
,I/EventHub( 3524): Removing device '/dev/input/event14' due to inotify event
,D/IntelligenceServiceApplication(13417): onCreate()
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,E/SQLiteLog(13417): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13417): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(13417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13417): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13417): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:210)
E/SQLiteDatabase(13417): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.getPrivacyGuardedFilter(PlaceProvider.java:989)
E/SQLiteDatabase(13417): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:581)
E/SQLiteDatabase(13417): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(13417): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(13417): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(13417): 	at android.os.Binder.execTransact(Binder.java:446)
E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,E/SQLiteOpenHelper(13417): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(13417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13417): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13417): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13417): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(13417): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:210)
E/SQLiteOpenHelper(13417): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.getPrivacyGuardedFilter(PlaceProvider.java:989)
E/SQLiteOpenHelper(13417): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:581)
E/SQLiteOpenHelper(13417): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(13417): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(13417): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(13417): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog(13327): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13327): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(13327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13327): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13327): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13327): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13327): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(13327): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(13327): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(13327): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13327): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13327): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13327): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13327): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(13417): Opened privacy in read-only mode
E/SQLiteOpenHelper(13327): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(13327): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13327): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13327): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13327): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
,E/SQLiteOpenHelper(13327): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(13327): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(13327): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(13327): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(13327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(13327): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(13327): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(13327): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(13327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(13327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(13327): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(13327): Opened ClientFlag.db in read-only mode
E/SQLiteLog(13417): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/Place.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13417): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/Place.db'.
E/SQLiteDatabase(13417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:906)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:879)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
E/SQLiteDatabase(13417): 	at android.database.sqlite.SQLiteSecureOpenHelper.getReadableDatabase(SQLiteSecureOpenHelper.java:280)
E/SQLiteDatabase(13417): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:587)
E/SQLiteDatabase(13417): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(13417): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(13417): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(13417): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(13417): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err(13417): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(13417): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
W/System.err(13417): 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
,W/System.err(13417): 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
W/System.err(13417): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
W/System.err(13417): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
W/System.err(13417): 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:906)
W/System.err(13417): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:879)
W/System.err(13417): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
W/System.err(13417): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
W/System.err(13417): 	at android.database.sqlite.SQLiteSecureOpenHelper.getReadableDatabase(SQLiteSecureOpenHelper.java:280)
W/System.err(13417): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:587)
W/System.err(13417): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(13417): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(13417): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(13417): 	at android.os.Binder.execTransact(Binder.java:446)
D/UserAnalysis.PlaceProvider(13417): query - query() SQLiteException!!!
,E/LocationWidgetFuctionData(13379): configPlaceListItems : cursor is null!!
,E/Zygote  (13470): MountEmulatedStorage()
I/libpersona(13470): KNOX_SDCARD checking this for 1000
E/Zygote  (13470): v2
I/libpersona(13470): KNOX_SDCARD not a persona
,I/SELinux (13470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=13470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (13470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MmsApp(13444): [start]    onCreate() consume time = 0.0
,W/BroadcastQueue( 3524): Skipping deliver [background] BroadcastRecord{927670c u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{6a1ee5e 13327 com.google.android.apps.docs/10101/u0 remote:2618fb99}: process crashing
,D/Mms/ArtClassLoader(13444): init before art
I/ActivityManager( 3524): Killing 8873:com.android.settings/1000 (adj 15): bgCount ##31
,D/Mms/ArtClassLoader(13444): init [DONE] art

```
