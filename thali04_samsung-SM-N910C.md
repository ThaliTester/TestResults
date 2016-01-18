#### Test 56151093f6e24ff_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3518): SIOP:: AP = 250, PST = 269, CUR = 30
D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3518): stay LED for fully charged
I/MotionRecognitionService( 3518): Plugged
I/MotionRecognitionService( 3518): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11780): 
D/AndroidRuntime(11780): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11780): CheckJNI is OFF
D/AndroidRuntime(11780): readGMSProperty: start
D/AndroidRuntime(11780): readGMSProperty: already setted!!
D/AndroidRuntime(11780): readGMSProperty: end
D/AndroidRuntime(11780): addProductProperty: start
E/AffinityControl(11780): AffinityControl: registerfunction enter
D/AndroidRuntime(11780): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3518): inState():  stateMachine is null !!
I/PersonaManagerService( 3518): PersonaId don't exist
I/ActivityManager( 3518): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3518): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3518): mDVFSHelper.acquire()
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/Zygote  (11799): MountEmulatedStorage()
I/libpersona(11799): KNOX_SDCARD checking this for 10583
E/Zygote  (11799): v2
I/libpersona(11799): KNOX_SDCARD not a persona
I/SELinux (11799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3518): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11799 uid=10583 gids={50583, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11799): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11780): Shutting down VM
D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11799): TimaSignature is unavailable
D/ActivityThread(11799): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11799): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6292): updateVisibility : ActivityRecord{26072591 token=android.os.BinderProxy@8b75aaa {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11799): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11799): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11799): Loading: webviewchromium
I/LibraryLoader(11799): Time to load native libraries: 5 ms (timestamps 4882-4887)
I/LibraryLoader(11799): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11799): Binding Chromium to main looper Looper (main, tid 1) {2b081a48}
,I/LibraryLoader(11799): Expected native library version number "",actual native library version number ""
I/chromium(11799): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11799): Initializing chromium process, renderers=0
,W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11799): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11799): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11799): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11799): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11799): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11799): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11799): CordovaWebView is running on device made by: samsung
,W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11799): performCreate Call secproduct feature valuefalse
D/Activity(11799): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11799): Render dirty regions requested: true
D/ActivityManager( 3518): post active user change for 0
D/KnoxTimeoutHandler( 3518): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3518): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11799): Initialized EGL, version 1.4
,I/OpenGLRenderer(11799): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279692528 
,D/OpenGLRenderer(11799): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11799): Enabling debug mode 0
,D/mali_winsys(11799): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11799): updateVisibility : ActivityRecord{101aa578 token=android.os.BinderProxy@1d8c22cf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3518): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3518): mDVFSHelper.release()
,I/Timeline( 3518): Timeline: Activity_windows_visible id: ActivityRecord{33364bed u0 com.test.thalitest/.MainActivity t26} time:135244
,W/IInputConnectionWrapper(11799): showStatusIcon on inactive InputConnection
,I/Timeline(11799): Timeline: Activity_idle id: android.os.BinderProxy@1d8c22cf time:135255
,I/chromium(11799): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11799): 
,D/JsMessageQueue(11799): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11799): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358476672
D/JX-Cordova(11799): jxcore cordova android initializing
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11799): Initializing JXcore engine
W/jxcore-log(11799): JXcore engine is ready
,W/jxcore-log(11799): Starting JXcore engine
,E/auditd  ( 4608): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3518): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3518): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11799): Platform android
W/jxcore-log(11799): 
W/jxcore-log(11799): Process ARCH arm
W/jxcore-log(11799): 
,I/jxcore-log(11799): JXcore Cordova bridge is ready!
I/jxcore-log(11799): 
W/jxcore-log(11799): JXcore engine is started
,I/jxcore-log(11799): Toggling radios to true
I/jxcore-log(11799): 
,D/BluetoothAdapter(11799): enable()
,D/BluetoothAdapter(11799): enable(): BT is already enabled..!
,D/WifiService( 3518): New client listening to asynchronous messages
,I/WifiManager(11799): packageName : com.test.thalitest
D/SecContentProvider( 3518): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3518): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3518): mCursor = null
D/WifiService( 3518): setWifiEnabled: true pid=11799, uid=10583
E/WifiService( 3518): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3518): Permission Denial: getCurrentUser() from pid=11799, uid=10583 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3518): Failed getting userId using ActivityManagerNative
W/WifiService( 3518): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11799, uid=10583 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3518): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3518): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3518): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3518): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3518): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3518): name = wifi_on
,I/WifiService( 3518): disconnect: pid=11799, uid=10583
I/wpa_supplicant( 3825): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3825): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3825): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3518): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3825): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): Disconnected - do not scan
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3518): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3518): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3518): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11799): Radios toggled
I/jxcore-log(11799): 
,I/jxcore-log(11799): My device name is: samsung-SM-N910C
I/jxcore-log(11799): 
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3518): do suspend true
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
,D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3518): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3518): updateNetworkInfo()
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3518): updateNetworkInfo()
D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,E/WifiStateMachine( 3518): Start Disconnecting Watchdog 1
,I/Hs20UtilService( 4110): Starting #8
E/WifiStateMachine( 3518): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3518): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3518): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3518): do suspend true
I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8820): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8820): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8820): MountReceiver.onReceive - Create mPrefHandler
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
,D/NearbySettings( 8820): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
V/NearbySettings( 8820): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/ConnectivityService( 3518): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3518): Not allowed due to - mEnabled false
E/WifiStateMachine( 3518): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
,D/WifiService( 3518): New client listening to asynchronous messages
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3518): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3518): updateConfiguredNetworkExpiration - currTime: 1453125299090
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/WifiStateMachine( 3518): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
I/NearbySettings( 8820): MountReceiver.onReceive - Set preference state off
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 6762): CM callback handler got msg 524292
V/NearbySettings( 8820): MountReceiver.mPrefHandler - 7002
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): P2P: Current p2p state = IDLE
D/CSLegacyTypeTracker( 3518): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> SCANNING
D/CSLegacyTypeTracker( 3518): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/wpa_supplicant( 3825): First Scan Start
E/WifiStateMachine( 3518): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3518): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
,I/wpa_supplicant( 3825): Scan requested (ret=0) - scan timeout 30 seconds
D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3518): Not allowed due to - mEnabled false
D/ConnectivityService( 3518): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): updateIfacesLocked()
V/NetworkStats( 3518): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3518): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 3691): updateDataNetType()
D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
,D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/SmartBondingService( 3518): getSBEnabled() enabled =false
E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
E/WifiStateMachine( 3518): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/SmartBondingService( 3518): getSBEnabled() enabled =false
E/WifiStateMachine( 3518): setDetailed state send new extra info"NG700"
V/NetworkStats( 3518): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering( 3518): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): performPollLocked() took 6ms
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
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
,I/SignOutReceiver(11459): NETWORK_STATE_CHANGED_ACTION
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,I/Hs20UtilService( 4110): Starting #9
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8820): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8820): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8820): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8820): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8820): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11459): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3518): updateDataUsageMap
I/ApplicationPolicy( 3518): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/GpsLocationProvider( 3518): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3518): No Active Data Connection
,I/DBG_DM  ( 6292): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6292): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11889): MountEmulatedStorage()
E/Zygote  (11889): v2
I/libpersona(11889): KNOX_SDCARD checking this for 10110
I/libpersona(11889): KNOX_SDCARD not a persona
,I/SELinux (11889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11889): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11889 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11889): TimaSignature is unavailable
,D/ActivityThread(11889): Added TimaKeyStore provider
,D/ResourcesManager(11889): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11889): ACRA is enabled for com.facebook.appmanager, intializing...
I/DexLibLoader(11889): not using cross-dex optimization: ART in use
I/art     (11889): Thread[1,tid=11889,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
V/DexLibLoader(11889): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11889): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11889): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11889): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11889): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
W/art     (11889): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11889): loading pre-built fallback odex files
V/MultiDexClassLoader(11889): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11889): released odex store lock
D/DexLibLoader(11889): DexLibLoader.loadAll took 15 ms
,W/ca      (11889): Verify
,W/LightSharedPreferencesImpl(11889): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11889): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11889): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11889): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11889): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11889): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11889): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11889): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11889): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11889): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11889): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11889): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11889): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11889): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11889): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11889): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11889): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11889): 	... 10 more
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11914): MountEmulatedStorage()
E/Zygote  (11914): v2
I/libpersona(11914): KNOX_SDCARD checking this for 1000
I/libpersona(11914): KNOX_SDCARD not a persona
,I/SELinux (11914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3518): Killing 9866:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11889): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11889): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11914): TimaSignature is unavailable
,D/ActivityThread(11914): Added TimaKeyStore provider
,D/ResourcesManager(11914): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11914): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11914): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11914): new DMDBOpenHelper instance
,W/appmanager(:<default>):QuickExperimentControllerImpl(11889): Exposure of experiment com.facebook.common.network.l@2e0007b9 occurred when no user was logged in
,W/BroadcastQueue( 3518): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{e6671e8 u0 ReceiverList{361a8f0b 11889 com.facebook.appmanager/10110/u0 remote:f342eda}}
,W/BroadcastQueue( 3518): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{e6671e8 u0 ReceiverList{361a8f0b 11889 com.facebook.appmanager/10110/u0 remote:f342eda}}
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): noConnectivity : true
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11942): MountEmulatedStorage()
I/libpersona(11942): KNOX_SDCARD checking this for 10135
E/Zygote  (11942): v2
I/libpersona(11942): KNOX_SDCARD not a persona
I/SELinux (11942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11942): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11942 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11052:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11942): TimaSignature is unavailable
,D/ActivityThread(11942): Added TimaKeyStore provider
,W/BroadcastQueue( 3518): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{11dc122c u0 ReceiverList{16c535df 11889 com.facebook.appmanager/10110/u0 remote:e09c7e}}
,D/ResourcesManager(11942): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11942): Database version: 104
,V/AlarmManager( 3518): waitForAlarm result :8
,D/ResourcesManager(11942): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11942): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11942): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11942): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11942): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11942): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2bef7d1c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11942): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11942): GMSCore installation verified
,I/ConfigStore(11942): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11942): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11942): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11942): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/art     ( 3518): Explicit concurrent mark sweep GC freed 55283(2MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 1.209ms total 81.521ms
,I/wpa_supplicant( 3825): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3825): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3825): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3518): [1,453,125,300,184 ms] noteScanEnd no scan source
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11889): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11889): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/WifiStateMachine( 3518): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@37224b23 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3518): setDetailed state send new extra info
D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3518): getStreamVolume 3 index 0
,I/MediaRouter(11942): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/appmanager(:<default>):QuickExperimentControllerImpl(11889): Exposure of experiment com.facebook.imagepipeline.a.g@a7f92df occurred when no user was logged in
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(11889): Exposure of experiment com.facebook.imagepipeline.a.d@29e4e18 occurred when no user was logged in
,E/Zygote  (11972): MountEmulatedStorage()
I/libpersona(11972): KNOX_SDCARD checking this for 10002
E/Zygote  (11972): v2
I/libpersona(11972): KNOX_SDCARD not a persona
I/SELinux (11972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11972 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (11889): Explicit concurrent mark sweep GC freed 48049(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 997us total 23.883ms
W/appmanager(:<default>):m(11889): No feature status reporters found; is this dead code?
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 290us total 10.639ms
,D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11942): type=WIFI subType= reason=null isConnected=false
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 264us total 8.307ms
,D/TimaKeyStoreProvider(11972): TimaSignature is unavailable
,D/ActivityThread(11972): Added TimaKeyStore provider
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 518us total 9.706ms
,I/ActivityManager( 3518): Killing 11069:com.policydm/1000 (adj 15): bgCount ##31
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3518): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3825): Associated with C0.AA.48
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,D/ResourcesManager(11972): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3825): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3825): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3825): Blacklist: Clear (temp) 
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3518): Network connection established
,D/WifiNative-HAL( 3518): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3518): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3518): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3518): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3518): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3518): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3518): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3518): updateNetworkInfo()
,D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3518): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3518): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3518): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3518): Start Dhcp Watchdog 2
D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
I/ActivityManager( 3518): Killing 11085:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11995): MountEmulatedStorage()
E/Zygote  (11995): v2
I/libpersona(11995): KNOX_SDCARD checking this for 1000
I/libpersona(11995): KNOX_SDCARD not a persona
,I/SELinux (11995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11995): TimaSignature is unavailable
,D/ActivityThread(11995): Added TimaKeyStore provider
,D/ResourcesManager(11995): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11995): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3518): do suspend false
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
,D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,I/DIAGMON_AGENT(11995): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11995): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11995): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11995): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12011): MountEmulatedStorage()
E/Zygote  (12011): v2
I/libpersona(12011): KNOX_SDCARD checking this for 10012
I/libpersona(12011): KNOX_SDCARD not a persona
,I/SELinux (12011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12011): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12011 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12011): TimaSignature is unavailable
,D/ActivityThread(12011): Added TimaKeyStore provider
,D/ResourcesManager(12011): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3518): Killing 11126:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11126/oom_score_adj; errno=22
,I/FOTA_Client(12011): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12011): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12011): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12027): MountEmulatedStorage()
E/Zygote  (12027): v2
I/libpersona(12027): KNOX_SDCARD checking this for 10021
I/libpersona(12027): KNOX_SDCARD not a persona
,I/SELinux (12027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12027 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 10934:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/10934/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12027): TimaSignature is unavailable
,D/ActivityThread(12027): Added TimaKeyStore provider
,D/ResourcesManager(12027): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12027): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 14:55:00 GMT+01:00 2016
,I/KLMS-2.4.521: (12027): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12027): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12027): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12027): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12027): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12027): StateImplV2(): networkChangeListener().END
E/Zygote  (12044): MountEmulatedStorage()
E/Zygote  (12044): v2
I/libpersona(12044): KNOX_SDCARD checking this for 10038
I/libpersona(12044): KNOX_SDCARD not a persona
,I/SELinux (12044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12044 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/dhcpcd  (12043): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onDestroy()
,I/dhcpcd  (12043): version 5.5.6 starting
,I/ActivityManager( 3518): Killing 11109:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12044): TimaSignature is unavailable
,D/ActivityThread(12044): Added TimaKeyStore provider
,E/lowmemorykiller( 2828): Error writing /proc/11109/oom_score_adj; errno=22
,E/dhcpcd  (12043): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager(12044): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12044): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  (12043): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12043): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12043): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12043): bssid match
I/dhcpcd  (12043): wlan0: rebinding lease of 192.168.1.124
,E/Zygote  (12065): MountEmulatedStorage()
I/libpersona(12065): KNOX_SDCARD checking this for 1000
E/Zygote  (12065): v2
I/libpersona(12065): KNOX_SDCARD not a persona
,I/SELinux (12065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12065 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11204:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12065): TimaSignature is unavailable
,D/ActivityThread(12065): Added TimaKeyStore provider
,D/ResourcesManager(12065): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12085): MountEmulatedStorage()
E/Zygote  (12085): v2
I/libpersona(12085): KNOX_SDCARD checking this for 10039
I/libpersona(12085): KNOX_SDCARD not a persona
,I/SELinux (12085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12085): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12085 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11171:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11171/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12085): TimaSignature is unavailable
,D/ActivityThread(12085): Added TimaKeyStore provider
,D/ResourcesManager(12085): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12085): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12085): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12085): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12085): PushLog.txt file is not deleted.
D/SPPClientService(12085): PushLog.txt file is not deleted.
D/SPPClientService(12085): ============PushLog. stop!
,I/SA      (11266): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11266): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11266): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11266): [SLFUCHKMGR] constructor called
,E/SPPClientService(12085): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11266): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11266): [OR] == isSIMCardReady false ==
,I/SA      (11266): [SCU] == networkStateCheck == false
I/SA      (11266): [OR] onReceive END
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3518): Killing 11223:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12105): MountEmulatedStorage()
I/libpersona(12105): KNOX_SDCARD checking this for 10067
E/Zygote  (12105): v2
I/libpersona(12105): KNOX_SDCARD not a persona
,I/SELinux (12105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12105): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12105 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12105): TimaSignature is unavailable
,D/ActivityThread(12105): Added TimaKeyStore provider
,D/ResourcesManager(12105): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12105): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12105): Other Intent
,I/ActivityManager( 3518): Killing 11146:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/accuweather( 5125): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5125): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5125): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5125): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5125): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11799): 
,E/Zygote  (12121): MountEmulatedStorage()
I/libpersona(12121): KNOX_SDCARD checking this for 1000
E/Zygote  (12121): v2
I/libpersona(12121): KNOX_SDCARD not a persona
I/SELinux (12121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12121 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12121): TimaSignature is unavailable
,D/ActivityThread(12121): Added TimaKeyStore provider
,D/ResourcesManager(12121): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12121): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12121): premStatus:2
,I/KnoxUsageLogPro(12121): isEulaShown : false
I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12136): MountEmulatedStorage()
I/libpersona(12136): KNOX_SDCARD checking this for 10090
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD not a persona
,I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12136 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11187:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ActivityThread(12136): Added TimaKeyStore provider
,D/ResourcesManager(12136): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12152): MountEmulatedStorage()
E/Zygote  (12152): v2
I/libpersona(12152): KNOX_SDCARD checking this for 10127
I/libpersona(12152): KNOX_SDCARD not a persona
,I/SELinux (12152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12152 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11319:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12152): TimaSignature is unavailable
,D/ActivityThread(12152): Added TimaKeyStore provider
,D/ResourcesManager(12152): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12152): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12152): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12152): stopCheckCategoryVersion
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12169): MountEmulatedStorage()
E/Zygote  (12169): v2
I/libpersona(12169): KNOX_SDCARD checking this for 10136
I/libpersona(12169): KNOX_SDCARD not a persona
,I/SELinux (12169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12169): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12169 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11288:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 655us total 10.659ms
,D/TimaKeyStoreProvider(12169): TimaSignature is unavailable
,D/ActivityThread(12169): Added TimaKeyStore provider
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 8.563ms
,D/ResourcesManager(12169): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 361us total 8.305ms
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11799): 
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11799): 
,I/WebViewFactory(12169): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12169): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12169): Loading: webviewchromium
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11799): 
,I/LibraryLoader(12169): Time to load native libraries: 3 ms (timestamps 9081-9084)
I/LibraryLoader(12169): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12169): Binding Chromium to main looper Looper (main, tid 1) {7054f08}
,I/LibraryLoader(12169): Expected native library version number "",actual native library version number ""
,I/chromium(12169): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11799): 
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11799): 
,I/BrowserStartupController(12169): Initializing chromium process, renderers=0
,W/art     (12169): Attempt to remove local handle scope entry from IRT, ignoring
,I/jxcore-log(11799): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11799): 
,W/chromium(12169): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid(12169): Requires BLUETOOTH permission
I/chromium(12169): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12169): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12169): Starting up...
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12237): MountEmulatedStorage()
,E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD checking this for 10150
I/libpersona(12237): KNOX_SDCARD not a persona
I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12237 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11339:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
,D/ActivityThread(12237): Added TimaKeyStore provider
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12237): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12237): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12237): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12237): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12237): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12237): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12252): MountEmulatedStorage()
E/Zygote  (12252): v2
I/libpersona(12252): KNOX_SDCARD checking this for 10178
I/libpersona(12252): KNOX_SDCARD not a persona
,I/SELinux (12252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12252 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11356:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12252): TimaSignature is unavailable
,D/ActivityThread(12252): Added TimaKeyStore provider
,D/ResourcesManager(12252): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12252): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12252): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12252): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12252): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12252): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12252): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,E/Zygote  (12275): MountEmulatedStorage()
I/libpersona(12275): KNOX_SDCARD checking this for 10082
E/Zygote  (12275): v2
I/libpersona(12275): KNOX_SDCARD not a persona
I/SELinux (12275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12275): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12275 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12275): TimaSignature is unavailable
D/ActivityThread(12275): Added TimaKeyStore provider
D/RCPManagerService( 3518): exchangeData() failure , invalid userId
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12275): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/BadgeProvider(12275): onCreate
D/BadgeProvider(12275): DatabaseHelper
E/Zygote  (12291): MountEmulatedStorage()
E/Zygote  (12291): v2
I/libpersona(12291): KNOX_SDCARD checking this for 1000
I/libpersona(12291): KNOX_SDCARD not a persona
I/SELinux (12291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3518): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12291 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3518): Killing 11479:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
I/ActivityManager( 3518): Killing 11372:com.samsung.helphub/1000 (adj 15): bgCount ##32
I/SELinux (12291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12291): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BadgeProvider(12275): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/jxcore-log(11799): Test app app.js loaded
I/jxcore-log(11799): 
D/TimaKeyStoreProvider(12291): TimaSignature is unavailable
D/ActivityThread(12291): Added TimaKeyStore provider
D/BadgeProvider(12275): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12275): sendNotify, [notify] : null
D/BadgeProvider(12275): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12275): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12275): update, [UpdateCount] : 1
D/Launcher.Model( 3997): reloadBadges entered.
D/ResourcesManager(12291): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
I/chromium(11799): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ActivityManager( 3518): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 3518): Killing 11496:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
I/chromium(11799): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/iu.Environment( 6762): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 6762): num queued entries: 0
I/iu.UploadsManager( 6762): num updated entries: 0
I/iu.SyncManager( 6762): NEXT; no task
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/Zygote  (12309): MountEmulatedStorage()
E/Zygote  (12309): v2
I/libpersona(12309): KNOX_SDCARD checking this for 10013
I/libpersona(12309): KNOX_SDCARD not a persona
I/SELinux (12309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12309): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12309 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(12309): TimaSignature is unavailable
D/ActivityThread(12309): Added TimaKeyStore provider
D/ResourcesManager(12309): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
I/ActivityManager( 3518): Killing 11514:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
I/Hs20UtilService( 4110): Starting #10
I/Hs20UtilService( 4110): Message received 5007
D/NearbySettings( 8820): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8820): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8820): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8820): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11459): NETWORK_STATE_CHANGED_ACTION
I/dhcpcd  (12043): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
I/dhcpcd  (12043): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3518): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3518): do suspend true
D/WifiP2pService( 3518): InactiveState{ what=143375 }
D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3518): WifiStateMachine DHCP successful
E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3518): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3518): Not connected state, yet.
E/WifiStateMachine( 3518): VerifyingLinkState enter
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3518): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3518): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3518): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3518): callSECApiInt - ID [210]
E/WifiStateMachine( 3518): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3518): updateNetworkInfo()
D/ConnectivityService( 3518): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3518): Adding iface wlan0 to network 503
D/WifiWatchdogStateMachine( 3518): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3518): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3518): Now, connected state.
E/WifiStateMachine( 3518): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3518): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
E/WifiStateMachine( 3518): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/Hs20UtilService( 4110): Starting #11
I/Hs20UtilService( 4110): Message received 5007
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3518): callSECApiVoid - ID [212]
E/WifiStateMachine( 3518): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService( 3518): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService( 3518): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/WifiStateMachine( 3518): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/ConnectivityService( 3518): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3518): Unexpected mtu value: 0, wlan0
V/        ( 2845): QcRouteController
D/NearbySettings( 8820): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8820): MountReceiver.onReceive - Keep current state
V/        ( 2845): QcRouteController
I/SignOutReceiver(11459): NETWORK_STATE_CHANGED_ACTION
W/NetworkManagementService( 3518): route cmd failed: 
W/NetworkManagementService( 3518): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '71 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 71 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3518): '
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3518): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3518): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/        ( 2845): QcRouteController
I/Hs20UtilService( 4110): Starting #12
I/Hs20UtilService( 4110): Message received 5007
D/NearbySettings( 8820): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8820): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/        ( 2845): QcRouteController
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8820): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8820): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8820): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11459): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
I/Hs20UtilService( 4110): Starting #13
I/Hs20UtilService( 4110): Message received 5007
D/NearbySettings( 8820): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8820): MountReceiver.onReceive - Keep current state
V/        ( 2845): QcRouteController
I/WifiStateMachine( 3518): callSECApi what=220
D/WifiStateMachine( 3518): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
V/        ( 2845): QcRouteController
I/SignOutReceiver(11459): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
V/        ( 2845): QcRouteController
D/PowerManagerService( 3518): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3518
D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
D/ConnectivityService( 3518): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3518): LTETest block dns file not exists
D/ConnectivityService( 3518): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3518): updateNetworkInfo()
E/ConnectivityService( 3518): updateNetworkInfo()
D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3518): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3518): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3518):    accepting network in place of null
D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out( 3518): (HTTPLog)-Static: isSBSettingEnabled false
E/CSLegacyTypeTracker( 3518): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3518): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
D/Tethering( 3518): MasterInitialState.processMessage what=3
D/ConnectivityService( 3518): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity( 3518): Not allowed due to - mEnabled false
D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): updateIfacesLocked()
V/NetworkStats( 3518): performPollLocked(flags=0x1)
D/ConnectivityService( 3518): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
D/NetworkStatsFactory( 3518): UpdateStatsForKnox
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): performPollLocked() took 10ms
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 6762): CM callback handler got msg 524290
D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
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
,I/System.out( 3518): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 13:55:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453125302433], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453125302415]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Validated
D/ConnectivityService( 3518): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3518): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3518): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3518): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6762): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3518): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3518): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3518): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6292): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6292): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
,I/NetworkMonitor(11942): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5354): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5354): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11995): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11995): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3518): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3518): mCursor = null
,I/FOTA_Client(12011): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12011): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12011): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12027): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 14:55:03 GMT+01:00 2016
,I/KLMS-2.4.521: (12027): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12027): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12027): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12027): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12027): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12027): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12027): NetworkChangeOperations(): uploadRequestLog().START 
,I/SO_AGENT(12044): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12027): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12027): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onDestroy()
,E/SPPClientService(12085): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11266): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11266): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      (11266): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11266): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11266): [OR] == isSIMCardReady false ==
,I/SA      (11266): [SCU] == networkStateCheck == true
,I/SA      (11266): [DM] getCountryCodeFromCSC : PL
I/SA      (11266): isChinaCountryCode : false
I/SA      (11266): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11266): [OR] == networkStateCheck true ==
,I/SA      (11266): [OR] GetMyCountryZoneTask
,I/SA      (11266): [OR] onReceive END
,I/SA      (11266): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11266): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11266): [SSP] query invoked
,I/SCloudBackupReceiver(12105): Other Intent
,I/SA      (11266): [TPMU] GetMccFromDB : null
I/SA      (11266): [SCU] getMccFromPreferece mcc = 260
I/SA      (11266): [TPM] isNoProxy(default) : true
,D/accuweather( 5125): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5125): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5125): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5125): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5125): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5125): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12121): premStatus:2
,I/KnoxUsageLogPro(12121): isEulaShown : false
I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12152): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12152): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12152): stopCheckCategoryVersion
,D/QuickConnect(12237): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12237): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12237): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,I/iu.Environment( 6762): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6762): num queued entries: 0
,I/iu.UploadsManager( 6762): num updated entries: 0
,I/iu.SyncManager( 6762): NEXT; no task
,D/WaitQueueForNetworkActivate(12309): notifyNetworkActivated
,D/ConnectivityService( 3518): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12309): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3518): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12309): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12309): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12309): exit::IDLE
D/InitializeManagerStateMachine(12309): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12309): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12309): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12309): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12309): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12309): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12309): entry::SUCCESS
D/hcjo    (12309): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12309): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12309): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12309): exit::SUCCESS
D/InitializeManagerStateMachine(12309): entry::IDLE
,I/SA      (11266): [RC New] Execute method=[GET] start
,I/SA      (11266): [RC New] Security=[true]
,I/System.out(11266): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11266): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11266): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11266): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11799): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11799): BLE advertisement is supported
I/jxcore-log(11799): 
,W/ProcessCpuTracker( 3518): Skipping unknown process pid 12412
,I/SA      (11266): [RC New] [v2liruge] api execute + 846
,I/SA      (11266): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11266): AsyncTask #1 calls detatch()
,I/SA      (11266): [TPMU] getNetworkMcc : 
,I/SA      (11266): [SCU] saveMccToPreferece Start
,I/SA      (11266): [SCU] RegionMCC : 260
,I/SA      (11266): [SSP] query invoked
,I/art     ( 3518): Explicit concurrent mark sweep GC freed 58342(3MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 6.090ms total 183.070ms
,I/SA      (11266): [TPMU] GetMccFromDB : null
I/SA      (11266): [SCU] getMccFromPreferece mcc = 260
I/SA      (11266): [SCU] saveMccToPreferece End
,I/SA      (11266): [RC New] executeRequest [v2liruge] end. 1078
,I/SA      (11266): [RC New] Execute end
,I/SA      (11266): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11266): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12043): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4643): callingUid 10014, callindPid: 4643
,D/ResourcesManager(11942): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11942): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11942): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11942): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11942): Conditions not met for autocaching.
I/MusicLeanback(11942): Stop autocaching.
,D/WearableClient(11942): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11942): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11942): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11942): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11942): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11942): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11942): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@31aed474 that was originally bound here
E/ActivityThread(11942): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@31aed474 that was originally bound here
E/ActivityThread(11942): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11942): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11942): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11942): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11942): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11942): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11942): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11942): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11942): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11942): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11942): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11942): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11942): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11942): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11942): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11942): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11942): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11942): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11942): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11942): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11942): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11942): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11942): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11942): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3518): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3518): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3518): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3518) eventTime = 143558
,D/PowerManagerService( 3518): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3518 (0x0)
,D/PowerManagerService( 3518): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3518, ws=WorkSource{10060}) (elapsedTime=3492)
,D/SSRM:n  ( 3518): SIOP:: AP = 280, PST = 268, CUR = 58
,I/GAV4    (12169): Thread[GAThread,5,main]: No campaign data found.
,I/PowerManagerService( 3518): [PWL] Off : 50s ago
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:-69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:95
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3518): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11914): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11914): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11914): ================================================
,I/CSTORAGE(11914):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11914): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11914): [GetString-S]
,E/art     (11914): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11914): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11914): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11914): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12043): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (12043): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12043): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12309): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12309): exit::IDLE
D/PreloadUpdateManagerStateMachine(12309): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12309): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (12309): RestApi Request Add : 2307
,I/System.out(12309): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12309): (HTTPLog)-Static: isShipBuild true
I/System.out(12309): (HTTPLog)-Thread-1741-274765177: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12309): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10013
,I/System.out(12309): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12309): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12309, getuid(): 10013
,I/qtaguid (12309): Untagging socket 26
,D/hcjo    (12309): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (12309): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(12309): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12309): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12309): entry::REQ_UPDATE_CHECK
,I/Volley  (12309): RestApi Request Add : 2315
,I/System.out(12309): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(12309): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12309): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12309, getuid(): 10013
,I/qtaguid (12309): Untagging socket -1,
,I/qtaguid (12309): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (12309): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger(12309): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine(12309): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(12309): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine(12309): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12309): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12309): entry::FINISH
,D/PreloadUpdateManagerStateMachine(12309): exit::FINISH
,D/PreloadUpdateManagerStateMachine(12309): entry::IDLE
,D/SSRM:n  ( 3518): SIOP:: AP = 260, PST = 269, CUR = -69
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:82
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryService( 3518): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3518): Waited long enough for: ServiceRecord{75f884d u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3518): !@Sync 5
,D/SSRM:n  ( 3518): SIOP:: AP = 250, PST = 261, CUR = 21
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:68
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/BatteryService( 3518): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 3518): [PWL] Off : 75s ago
,D/SSRM:n  ( 3518): SIOP:: AP = 250, PST = 259, CUR = 51
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/BatteryService( 3518): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3518): Skipping unknown process pid 12606
,I/ClearcutLoggerApiImpl( 4643): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3518): SIOP:: AP = 250, PST = 258, CUR = 57
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3518): !@Sync 6
,D/SSRM:n  ( 3518): SIOP:: AP = 250, PST = 257, CUR = 58
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/BatteryService( 3518): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3518): [PWL] Off : 105s ago
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 255, CUR = 55
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 254, CUR = 51
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/BatteryService( 3518): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3518): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3518): !@Sync 7
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 253, CUR = 46
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3518): [PWL] Off : 140s ago
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 252, CUR = 45
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 248, CUR = 42
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3518): !@Sync 8
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 247, CUR = 40
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/BatteryService( 3518): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/AlarmManager( 3518): waitForAlarm result :8
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 246, CUR = 39
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3518): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3518): [PWL] Off : 180s ago
,D/SSRM:n  ( 3518): SIOP:: AP = 240, PST = 245, CUR = 37
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3518): stay LED for fully charged
,I/MotionRecognitionService( 3518): Plugged
,I/MotionRecognitionService( 3518): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5620): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5620): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11799): --= Surplus to requirements =--,
I/jxcore-log(11799): 
,I/jxcore-log(11799): ****TEST TOOK:  ms ****
I/jxcore-log(11799): 
,I/jxcore-log(11799): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11799): 
,D/AndroidRuntime(12705): 
D/AndroidRuntime(12705): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12705): CheckJNI is OFF
,D/AndroidRuntime(12705): readGMSProperty: start
D/AndroidRuntime(12705): readGMSProperty: already setted!!
,D/AndroidRuntime(12705): readGMSProperty: end
D/AndroidRuntime(12705): addProductProperty: start
,E/AffinityControl(12705): AffinityControl: registerfunction enter
,D/AndroidRuntime(12705): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3518): START PACKAGE DELETE: observer{462573163}
D/PackageManager( 3518): pkg{<packageName>}
D/PackageManager( 3518): user{0}
D/PackageManager( 3518): caller{2000}
D/PackageManager( 3518): flags{3}
,D/PersonaManagerService( 3518): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3518): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3518): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3518): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3518): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3518): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 3518): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3518): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3518): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3518): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3518): !@killApplicatoin: 10583, uninstall pkg
I/ActivityManager( 3518): Force stopping com.test.thalitest appid=10583 user=-1: uninstall pkg
,I/ActivityManager( 3518): Killing 11799:com.test.thalitest/u0a583 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3518):   Force finishing activity ActivityRecord{33364bed u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3518): mDVFSHelper.acquire()
,D/WifiService( 3518): Client connection lost with reason: 4
,I/WindowState( 3518): WIN DEATH: Window{2ca1291b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3518): Skipping PackageSetting{6843eb7 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3518): Force stopping com.test.thalitest appid=10583 user=0: pkg removed
,I/ActivityManager( 3518):   Force finishing activity ActivityRecord{33364bed u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3518): Duplicate finish request for ActivityRecord{33364bed u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6292): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/art     ( 9095): Explicit concurrent mark sweep GC freed 23687(1404KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.168ms total 39.354ms
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 6762): Explicit concurrent mark sweep GC freed 6062(275KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.371ms total 89.062ms
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/GeofencerStateMachine( 4643): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4491): mOCRHelper is null
,I/InputReader( 3518): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/LWLocationManager(11532): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11532): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6292): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/Zygote  (12736): MountEmulatedStorage()
E/Zygote  (12736): v2
I/libpersona(12736): KNOX_SDCARD checking this for 10063
I/libpersona(12736): KNOX_SDCARD not a persona
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 30693(1895KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 931us total 91.389ms
,W/ResourceType( 5354): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5354): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/ActivityManager( 3518): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12736 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/DBG_DM  ( 6292): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/SELinux (12736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/SecContentProvider2( 3518): uri = 14 selection = getSealedState
D/SecContentProvider2( 3518): mCursor = null
,D/ApplicationPolicy( 3518): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/TimaKeyStoreProvider(12736): TimaSignature is unavailable
,D/ActivityThread(12736): Added TimaKeyStore provider
,I/DBG_DM  ( 6292): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6292): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6292): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6292): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6292): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3518): post active user change for 0
D/KnoxTimeoutHandler( 3518): postActiveUserChange for user 0
,I/DBG_DM  ( 6292): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,V/ActivityThread( 6292): updateVisibility : ActivityRecord{26072591 token=android.os.BinderProxy@8b75aaa {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 3518): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(12736): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/art     ( 3518): Explicit concurrent mark sweep GC freed 32773(2MB) AllocSpace objects, 49(784KB) LOS objects, 24% free, 48MB/64MB, paused 2.242ms total 175.142ms
,I/art     ( 3518): WaitForGcToComplete blocked for 71.107ms for cause Explicit
,D/EnterpriseDeviceManagerService( 3518): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3518): Admin package name: com.google.android.gms
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 3518): Got RemoteException sending setActive(false) notification to pid 11799 uid 10583
,D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12736): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12736): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12736): packagename:com.test.thalitest
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3518): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3518): mCursor = null
I/KLMS-2.4.521: (12027): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 14:57:20 GMT+01:00 2016
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/Timeline( 6292): Timeline: Activity_idle id: android.os.BinderProxy@8b75aaa time:278409
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (12027): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Books/Books.apk
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onCreate()
D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/splitIntent( 3518): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3518): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.521: (12027): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (12027): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12027): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12027): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12027): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12027): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,E/Zygote  (12757): MountEmulatedStorage()
E/Zygote  (12757): v2
I/libpersona(12757): KNOX_SDCARD checking this for 10106
I/libpersona(12757): KNOX_SDCARD not a persona
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux (12757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3518): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12757 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ActivityManager( 3518): mDVFSHelper.release()
I/Timeline( 3518): Timeline: Activity_windows_visible id: ActivityRecord{3e9208ba u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:278465
,D/RegisteredServicesCache( 3962): empty dynamic service
,D/RCPManager(12121):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3518):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3518): queryAllProviders():  providerCallBack is not register for 0
,D/TimaKeyStoreProvider(12757): TimaSignature is unavailable
D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ActivityThread(12757): Added TimaKeyStore provider
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12773): MountEmulatedStorage()
E/Zygote  (12773): v2
I/libpersona(12773): KNOX_SDCARD checking this for 10050
I/libpersona(12773): KNOX_SDCARD not a persona
,I/SELinux (12773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3518): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12773 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux (12773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/art     ( 3518): Explicit concurrent mark sweep GC freed 6712(314KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.120ms total 146.069ms
,I/KLMS-2.4.521: (12027): KLMSIntentService(): listeningToPackageRemoved().END
W/ResourcesManager(11532): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(12773): TimaSignature is unavailable
,D/ActivityThread(12773): Added TimaKeyStore provider
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(12757): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/Zygote  (12788): MountEmulatedStorage()
E/Zygote  (12788): v2
I/libpersona(12788): KNOX_SDCARD checking this for 10101
I/libpersona(12788): KNOX_SDCARD not a persona
,I/SELinux (12788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux (12788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12788): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/ActivityManager( 3518): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12788 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/elm:14491(12757): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12757): ELMEngine.ELMEngine( context ).
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/elm:14491(12757): MDMBridge.setEnterpriseBridge()
I/KLMS-2.4.521: (12027): KLMSIntentService(): onDestroy()
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/PackageManager( 3518): delete codoeFile: 
,W/ResourcesManager(11532): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11532): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(11532): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11532): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(12788): TimaSignature is unavailable
,D/ActivityThread(12788): Added TimaKeyStore provider
I/AASAUninstall( 3518):  com.test.thalitest not target!
D/PackageManager( 3518): result of delete: 1{462573163}
,D/AndroidRuntime(12705): Shutting down VM
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/elm:14491(12757): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(12773): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/elm:14491(12757): ElmAgentService : onCreate()
,D/elm:14491(12757): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/ResourcesManager(12773): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12773): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12773): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12773): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/elm:14491(12757): MainReceiver.listeningToPackageRemoved()
W/ResourcesManager(12773): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/elm:14491(12757): MDMBridge.getInstance()
W/ResourcesManager(12773): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/elm:14491(12757): MDMBridge.getAllLicenseInfoFromSDK()
W/ResourcesManager(12773): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12773): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/elm:14491(12757): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12788): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  (12805): MountEmulatedStorage()
E/Zygote  (12805): v2
I/libpersona(12805): KNOX_SDCARD checking this for 10183
I/libpersona(12805): KNOX_SDCARD not a persona
,I/SELinux (12805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3518): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12805 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/SELinux (12805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12757): ElmAgentService : onDestroy().
,I/ActivityManager( 3518): Killing 11549:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  (12820): MountEmulatedStorage()
I/libpersona(12820): KNOX_SDCARD checking this for 10019
E/Zygote  (12820): v2
I/libpersona(12820): KNOX_SDCARD not a persona
,I/SELinux (12820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(12805): TimaSignature is unavailable
,I/SELinux (12820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ActivityThread(12805): Added TimaKeyStore provider
E/SELinux (12820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12820 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ResourceType( 3518): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 440us total 10.593ms
D/TimaKeyStoreProvider(12820): TimaSignature is unavailable
D/ActivityThread(12820): Added TimaKeyStore provider
,D/ResourcesManager(11532): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 266us total 8.504ms
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/ActivityManager( 3518): Killing 11564:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 2890): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 257us total 8.197ms
,D/ResourcesManager(11532): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager(12820): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(12805): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/DocsApplication(12788): Installing DEX configuration.
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12820): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12820): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12820): onReceive() : package name is not s health. Return !!!
,D/DexInstaller(12788): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/PackageInfoHelper(12788): Provided clientMode=RELEASE, packageInfo=PackageInfo{3b9195a9 com.google.android.apps.docs}
,D/TAG     (12788): onCreate()
W/ResourcesManager( 3518): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 3518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
W/ResourcesManager( 3518): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3518): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/SQLiteLog(12805): (284) automatic index on shooting_modes(title_id)
,D/CrossAppStateProvider(12788): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/LocationWidgetApplication(11532): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/PackageManager( 3518): findPreferredActivity: No PreferredActivities set
,E/Zygote  (12840): MountEmulatedStorage()
E/Zygote  (12840): v2
I/libpersona(12840): KNOX_SDCARD checking this for 10190
I/libpersona(12840): KNOX_SDCARD not a persona
,I/SELinux (12840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux (12840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3518): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12840 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (12840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 3518): PackageReceiver onReceive()
I/HarmonyEASService( 3518): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3518): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3518): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3518): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3518): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3518): uID is 10583
V/EnterpriseBillingPolicy( 3518): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3518): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3518): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3518): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3518): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3518): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3518): getBillingProfileForVpnEngine - end - null
,D/UsbSettingsManager( 3518): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3518): onPackageRemoved : com.test.thalitest
,D/ResourcesManager(11532): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/TimaKeyStoreProvider(12840): TimaSignature is unavailable
D/ActivityThread(12840): Added TimaKeyStore provider
D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Books/Books.apk
I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/ActivityManager( 3518): Killing 10861:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
D/ResourcesManager(11532): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/KnoxTimeoutHandler( 3518): handleActiveUserChange for user 0
,D/ResourcesManager(12840): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12840): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12840): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,E/Zygote  (12855): MountEmulatedStorage()
E/Zygote  (12855): v2
I/libpersona(12855): KNOX_SDCARD checking this for 10035
I/libpersona(12855): KNOX_SDCARD not a persona
,I/SELinux (12855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/TapandpayWidget:Utils(12840): Clear T&P info.
,E/SELinux (12855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/ActivityManager( 3518): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12855 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/StatusBar( 3691): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12840): Widget is not attached.
,I/ActivityManager( 3518): Killing 11673:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
,D/TaskPersister( 3518): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3518): removeObsoleteFile: deleting file=24_task.xml
D/TimaKeyStoreProvider(12855): TimaSignature is unavailable
I/PhoneStatusBar( 3691): Icon Only
D/ActivityThread(12855): Added TimaKeyStore provider
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
D/PanelView( 3691): There is/are notification(s) 
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/PersonaManager( 3691): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
,I/ActivityManager( 3518): Killing 12275:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/PackageBroadcastService( 6762): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6762): Clearing selected account for com.test.thalitest
,D/NearbySource(12773): Nearby Source Create!
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/NearbyContext(12773): Nearby Context Create!
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/FeatureConfig(12855): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/LocationSettingsChecker( 6762): Removing dialog suppression flag for package com.test.thalitest
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
W/ResourcesManager(12855): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12855): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 6762): Loading module com.google.android.gms.games from APK com.google.android.play.games
W/ResourcesManager(12855): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/ChimeraModuleLdr( 6762): Module APK com.google.android.play.games already loaded
W/ResourcesManager(12855): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12855): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(12855): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/ResourcesManager(11532): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12773): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12773): Samsung link source created
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12855): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(11532): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ChimeraCfgMgr( 6762): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6762): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(11532): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,E/NetworkScheduler.SchedulerReceiver( 4643): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4643): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/SQLiteLog(12773): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteDatabase(12773): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12773): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12773): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12773): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12773): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12773): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12773): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12773): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12773): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12773): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12773): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12773): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12773): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12773): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12773): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12773): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12773): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12773): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12773): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12773): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12773): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12773): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12773): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12773): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12773): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12773): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12773): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12773): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager(12855): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager(11532): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ContactProvider(12773): getAllContactInfoList Start
D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/FileUtils( 6762): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 6762): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6762): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 6762): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6762): (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 6762): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ResourcesManager(12855): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/SQLiteLog( 6762): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6762): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ResourcesManager(12855): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/Process ( 6762): Sending signal. PID: 6762 SIG: 9
E/ActivityThread(11889): Failed to find provider info for com.facebook.appmanager.installrecord
E/SharedPreferencesImpl(12773): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/ResourcesManager(12855): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Zygote  (12886): MountEmulatedStorage()
E/Zygote  (12886): v2
I/libpersona(12886): KNOX_SDCARD checking this for 10031
I/libpersona(12886): KNOX_SDCARD not a persona
,D/ResourcesManager(12855): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager(12855): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SELinux (12886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3518): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12886 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12886): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager(12855): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12855): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(12855): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3518): displayNotification : [02h,02h,01h]
D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
W/ResourcesManager(12855): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/UsbHostManager( 3518): displayNotification : [0ah,00h,00h]
W/ResourcesManager(12855): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3518): displayNotification : [02h,0dh,00h]
E/Zygote  (12900): MountEmulatedStorage()
I/libpersona(12900): KNOX_SDCARD checking this for 10036
E/Zygote  (12900): v2
I/libpersona(12900): KNOX_SDCARD not a persona
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3518): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
I/SELinux (12900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/UsbHostManager( 3518): displayNotification : [09h,00h,00h]
D/ResourcesManager(11532): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
D/UsbHostManager( 3518): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3518): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3518): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/ConnectivityService( 3518): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2736a6b7)
D/ConnectivityService( 3518): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SELinux (12900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12900): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ConnectivityService( 3518): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager( 3518): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12900 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
E/lowmemorykiller( 2828): Error writing /proc/8820/oom_score_adj; errno=22
I/ActivityManager( 3518): Killing 8820:com.android.settings/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12886): TimaSignature is unavailable
,D/ActivityThread(12886): Added TimaKeyStore provider
D/ResourcesManager(12855): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(12855): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 3518): Process com.google.android.gms (pid 6762)(adj 5) has died(244,1189)
,W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
,W/GalaxyFinderApplication(12855): system/finder_cp/cpdata.xml file not found
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12900): TimaSignature is unavailable
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12900): Added TimaKeyStore provider
,D/ResourcesManager(12886): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/Zygote  (12926): MountEmulatedStorage()
E/Zygote  (12926): v2
I/libpersona(12926): KNOX_SDCARD checking this for 10052
I/libpersona(12926): KNOX_SDCARD not a persona
,I/SELinux (12926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3518): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12926 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (12926): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/MtpClient(12773): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12773): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/ActivityManager( 3518): Killing 11972:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,D/UsbHostManager( 3518): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3518): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/TimaKeyStoreProvider(12926): TimaSignature is unavailable
,D/ActivityThread(12926): Added TimaKeyStore provider
D/ResourcesManager(12900): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/WifiService( 3518): Client connection lost with reason: 4
,I/EventHub( 3518): Removing device '/dev/input/event10' due to inotify event
,I/EventHub( 3518): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(12926): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ContactProvider(12773): getAllContactInfoList End
,I/syncContacts(12773): thread: 1753, sync time = 243
,W/ResourcesManager(12926): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12926): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12926): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12926): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12926): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12926): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3518): Removing device '/dev/input/event8' due to inotify event
,I/EventHub( 3518): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteLog(12788): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12788): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12788): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12788): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12788): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12788): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12788): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12788): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12788): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12788): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12788): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12788): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12788): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12788): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12788): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12788): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12788): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12788): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12788): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12788): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12788): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12788): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12788): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12788): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12788): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12788): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12788): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12788): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12788): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12788): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12788): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12788): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12788): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12788): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12788): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12788): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12788): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12788): 	at bsh.a(Gelly,MembersInjector.java:30)
E/SQLiteOpenHelper(12788): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12788): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12788): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12788): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12788): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12788): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12788): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12788): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/EventHub( 3518): Removing device '/dev/input/event11' due to inotify event
,W/SQLiteOpenHelper(12788): Opened ClientFlag.db in read-only mode
,E/SQLiteLog(12900): (28) failed to open "/data/data/com.sec.android.app.shealth/databases/base.db" with flag (131138) and mode_t (0) due to error (30)
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/EventHub( 3518): Removing device '/dev/input/event12' due to inotify event
,E/SQLiteDatabase(12900): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12900): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12900): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase(12900): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase(12900): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase(12900): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(12900): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(12900): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(12900): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(12900): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(12900): 	at java.lang.Thread.run(Thread.java:818)
,D/Mms/MmsApp(12926): [start]    onCreate() consume time = 0.0
,E/SQLiteLog(12788): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12788): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12788): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12788): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12788): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12788): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12788): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12788): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12788): Process: com.google.android.apps.docs, PID: 12788
E/AndroidRuntime(12788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12788): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12788): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12788): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12788): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12788): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12788): 	at aFp.run(AbstractDatabaseInstance.java:471)
,D/Mms/ArtClassLoader(12926): init before art
,V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,D/Mms/ArtClassLoader(12926): init [DONE] art
,I/EventHub( 3518): Removing device '/dev/input/event13' due to inotify event
,D/Mms/TelephonyPermission(12926): start operation mode monitor
,D/ResourcesManager(12926): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12926): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog(12788): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
E/DropBoxManagerService( 3518): Can't write: system_app_crash
E/DropBoxManagerService( 3518): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3518): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3518): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3518): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3518): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3518): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3518): 	... 5 more
E/SQLiteDatabase(12788): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12788): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12788): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12788): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12788): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12788): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12788): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12788): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12788): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12788): 	at java.lang.reflect.Method.invok,e(Method.java:372)
E/SQLiteDatabase(12788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12788): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12788): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12788): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12788): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12788): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12788): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12788): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12788): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12788): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12788): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12788): Opened ClientFlag.db in read-only mode
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
I/EventHub( 3518): Removing device '/dev/input/event14' due to inotify event
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/Zygote  (12957): MountEmulatedStorage()
E/Zygote  (12957): v2
I/libpersona(12957): KNOX_SDCARD checking this for 1000
I/libpersona(12957): KNOX_SDCARD not a persona
,I/SELinux (12957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3518): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12957 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Process (12788): Sending signal. PID: 12788 SIG: 9
,E/lowmemorykiller( 2828): Error writing /proc/12788/oom_score_adj; errno=22
,W/BroadcastQueue( 3518): Skipping deliver [background] BroadcastRecord{289bddbc u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{baef98e 12788 com.google.android.apps.docs/10101/u0 remote:13337589}: process crashing
,D/Mms/TelephonyPermission(12926): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission(12926): isDefault true
,D/Mms/MmsApp(12926): onCreate() com.android.mms
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12900): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/Finsky  (12886): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TimaKeyStoreProvider(12957): TimaSignature is unavailable
,D/ActivityThread(12957): Added TimaKeyStore provider

```
