#### Test 583805004251330_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 255, CUR = 42
--------- beginning of main
D/AndroidRuntime(11721): 
D/AndroidRuntime(11721): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11721): CheckJNI is OFF
D/AndroidRuntime(11721): readGMSProperty: start
D/AndroidRuntime(11721): readGMSProperty: already setted!!
D/AndroidRuntime(11721): readGMSProperty: end
D/AndroidRuntime(11721): addProductProperty: start
D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3521): stay LED for fully charged
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5628): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/AffinityControl(11721): AffinityControl: registerfunction enter
D/AndroidRuntime(11721): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11740): MountEmulatedStorage()
E/Zygote  (11740): v2
I/libpersona(11740): KNOX_SDCARD checking this for 10648
I/libpersona(11740): KNOX_SDCARD not a persona
I/SELinux (11740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11740 uid=10648 gids={50648, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11721): Shutting down VM
E/SELinux (11740): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11740): TimaSignature is unavailable
D/ActivityThread(11740): Added TimaKeyStore provider
I/SurfaceFlinger( 2850): id=13 Removed YUIInstallC (6/8)
I/SurfaceFlinger( 2850): id=13 Removed YUIInstallC (-2/8)
D/ResourcesManager(11740): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6278): updateVisibility : ActivityRecord{60ac2c2 token=android.os.BinderProxy@125c50bf {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11740): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11740): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11740): Loading: webviewchromium
I/LibraryLoader(11740): Time to load native libraries: 4 ms (timestamps 5467-5471)
I/LibraryLoader(11740): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11740): Binding Chromium to main looper Looper (main, tid 1) {1055f0ca}
,I/LibraryLoader(11740): Expected native library version number "",actual native library version number ""
I/chromium(11740): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11740): Initializing chromium process, renderers=0
,W/art     (11740): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11740): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11740): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11740): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11740): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11740): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11740): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11740): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11740): CordovaWebView is running on device made by: samsung
,W/art     (11740): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11740): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11740): performCreate Call secproduct feature valuefalse
D/Activity(11740): performCreate Call debug elastic valuetrue
,W/ActivityManager( 3521): Activity pause timeout for ActivityRecord{c62fd4a u0 com.test.thalitest/.MainActivity t26}
,D/OpenGLRenderer(11740): Render dirty regions requested: true
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,V/ActivityThread(11740): updateVisibility : ActivityRecord{b4207a token=android.os.BinderProxy@8cf5979 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11740): Initialized EGL, version 1.4
,I/OpenGLRenderer(11740): HWUI protection enabled for context ,  &this =0xaf69d1a0 ,&mEglDisplay = 1 , &mEglConfig = -1279823600 
,D/OpenGLRenderer(11740): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11740): Enabling debug mode 0
,D/mali_winsys(11740): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(11740): showStatusIcon on inactive InputConnection
W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{c62fd4a u0 com.test.thalitest/.MainActivity t26} time:215941
,I/Timeline(11740): Timeline: Activity_idle id: android.os.BinderProxy@8cf5979 time:215941
,I/chromium(11740): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11740): 
,D/JsMessageQueue(11740): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11740): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358476672
,I/chromium(11740): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11740): Initializing JXcore engine
W/jxcore-log(11740): JXcore engine is ready
,E/auditd  ( 4613): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3521): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3521): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11740): Starting JXcore engine
,W/jxcore-log(11740): Platform android
W/jxcore-log(11740): 
W/jxcore-log(11740): Process ARCH arm
W/jxcore-log(11740): 
,I/jxcore-log(11740): JXcore Cordova bridge is ready!
I/jxcore-log(11740): 
W/jxcore-log(11740): JXcore engine is started
,I/jxcore-log(11740): Toggling radios to true
I/jxcore-log(11740): 
,D/BluetoothAdapter(11740): enable()
,D/BluetoothAdapter(11740): enable(): BT is already enabled..!
D/WifiService( 3521): New client listening to asynchronous messages
,I/WifiManager(11740): packageName : com.test.thalitest
,D/SecContentProvider( 3521): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3521): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3521): mCursor = null
,D/WifiService( 3521): setWifiEnabled: true pid=11740, uid=10648
E/WifiService( 3521): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3521): Permission Denial: getCurrentUser() from pid=11740, uid=10648 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3521): Failed getting userId using ActivityManagerNative
W/WifiService( 3521): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11740, uid=10648 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3521): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3521): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3521): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3521): name = wifi_on
,I/WifiService( 3521): disconnect: pid=11740, uid=10648
,I/wpa_supplicant( 3829): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3829): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3829): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3521): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3829): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): Disconnected - do not scan
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3521): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11740): Radios toggled
I/jxcore-log(11740): 
,I/jxcore-log(11740): My device name is: samsung-SM-N910C
I/jxcore-log(11740): 
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3521): updateNetworkInfo()
,D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
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
,E/WifiStateMachine( 3521): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 3521): ConnectModeState: Network connection lost 
,I/Hs20UtilService( 4070): Starting #8
,E/WifiStateMachine( 3521): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/Hs20UtilService( 4070): Message received 5007
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3521): do suspend true
,D/NearbySettings( 8751): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8751): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8751): MountReceiver.onReceive - Create mPrefHandler
D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,D/NearbySettings( 8751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3521): New client listening to asynchronous messages
,I/NearbySettings( 8751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8751): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8751): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/ConnectivityService( 3521): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,I/SignOutReceiver(11340): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3521): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity( 3521): Not allowed due to - mEnabled false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
,D/CSLegacyTypeTracker( 3521): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/TelephonyNetworkFactory( 3984): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - currTime: 1455034158306
,D/CSLegacyTypeTracker( 3521): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WifiStateMachine( 3521): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 6784): CM callback handler got msg 524292
,I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3829): First Scan Start
,I/wpa_supplicant( 3829): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3521): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3521): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
,D/ConnectivityService( 3521): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/Tethering( 3521): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): updateIfacesLocked()
D/SmartBondingService( 3521): getSBEnabled() enabled =false
V/NetworkStats( 3521): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3521): performPollLocked() took 6ms
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
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
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/Hs20UtilService( 4070): Starting #9
,I/Hs20UtilService( 4070): Message received 5007
,D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/NearbySettings( 8751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8751): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8751): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8751): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11340): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3521): updateDataUsageMap
,I/ApplicationPolicy( 3521): updateDataUsageMap  idList is null 
D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3521): No Active Data Connection
,I/DBG_DM  ( 6278): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6278): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11844): MountEmulatedStorage()
E/Zygote  (11844): v2
I/libpersona(11844): KNOX_SDCARD checking this for 1000
I/libpersona(11844): KNOX_SDCARD not a persona
,I/SELinux (11844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11844): TimaSignature is unavailable
,D/ActivityThread(11844): Added TimaKeyStore provider
,D/ResourcesManager(11844): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11844): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11844): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11844): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11844): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11844): sales region : global
I/PCWCLIENTTRACE_PushUtil(11844): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11844): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11844): noConnectivity : true
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11860): MountEmulatedStorage()
E/Zygote  (11860): v2
I/libpersona(11860): KNOX_SDCARD checking this for 10135
I/libpersona(11860): KNOX_SDCARD not a persona
,I/SELinux (11860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11860): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11860 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11021:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11860): TimaSignature is unavailable
,D/ActivityThread(11860): Added TimaKeyStore provider
,D/ResourcesManager(11860): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11860): Database version: 104
,D/ResourcesManager(11860): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11860): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11860): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11860): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@93bc17e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11860): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11860): GMSCore installation verified
,I/ConfigStore(11860): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11860): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11860): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11860): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3521): getStreamVolume 3 index 0
,I/MediaRouter(11860): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11885): MountEmulatedStorage()
I/libpersona(11885): KNOX_SDCARD checking this for 10002
E/Zygote  (11885): v2
I/libpersona(11885): KNOX_SDCARD not a persona
,I/SELinux (11885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11885): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11885 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/NetworkMonitor(11860): type=WIFI subType= reason=null isConnected=false
I/ActivityManager( 3521): Killing 10226:com.sec.android.gallery3d/u0a50 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11885): TimaSignature is unavailable
D/ActivityThread(11885): Added TimaKeyStore provider
,D/ResourcesManager(11885): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3521): Killing 10736:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11903): MountEmulatedStorage()
I/libpersona(11903): KNOX_SDCARD checking this for 1000
E/Zygote  (11903): v2
I/libpersona(11903): KNOX_SDCARD not a persona
I/SELinux (11903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11903 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8739(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 660us total 12.495ms
,D/TimaKeyStoreProvider(11903): TimaSignature is unavailable
,D/ActivityThread(11903): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 371us total 9.028ms
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 75220(4MB) AllocSpace objects, 41(656KB) LOS objects, 24% free, 49MB/65MB, paused 1.355ms total 86.889ms
D/CountryDetector( 3521): No listener is left
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 382us total 9.276ms
,D/ResourcesManager(11903): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11903): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11903): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11903): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11903): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11903): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 3829): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 3829): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3829): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3829): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3521): [1,455,034,159,396 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1ed78a7e sup_state=SCANNING debouncing=false
,E/Zygote  (11920): MountEmulatedStorage()
I/libpersona(11920): KNOX_SDCARD checking this for 10012
E/Zygote  (11920): v2
I/libpersona(11920): KNOX_SDCARD not a persona
I/SELinux (11920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11920): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11920 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/TimaKeyStoreProvider(11920): TimaSignature is unavailable
,D/ActivityThread(11920): Added TimaKeyStore provider
,D/ResourcesManager(11920): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3521): Killing 11061:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/lowmemorykiller( 2827): Error writing /proc/11061/oom_score_adj; errno=22
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11920): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3521): setDetailed state send new extra info"NG700"
,I/wpa_supplicant( 3829): Associated with C0.AA.48
E/Zygote  (11936): MountEmulatedStorage()
I/libpersona(11936): KNOX_SDCARD checking this for 10021
E/Zygote  (11936): v2
I/libpersona(11936): KNOX_SDCARD not a persona
,I/SELinux (11936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
E/SELinux (11936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11936 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11077:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11936): TimaSignature is unavailable
,D/ActivityThread(11936): Added TimaKeyStore provider
,D/ResourcesManager(11936): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 17:09:19 GMT+01:00 2016
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3829): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 3521): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/wpa_supplicant( 3829): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3829): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3829): Blacklist: Clear (temp) 
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3521): Network connection established
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive().END.
D/WifiNative-HAL( 3521): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3521): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11936): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/WifiStateMachine( 3521): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3521): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3521): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3521): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3521): updateNetworkInfo()
I/KLMS-2.4.521: (11936): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
I/KLMS-2.4.521: (11936): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11936): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11936): StateImplV2(): networkChangeListener().END
,E/WifiStateMachine( 3521): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3521): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3521): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3521): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/libpersona(11953): KNOX_SDCARD checking this for 10038
E/Zygote  (11953): MountEmulatedStorage()
I/libpersona(11953): KNOX_SDCARD not a persona
E/Zygote  (11953): v2
,I/SELinux (11953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11953 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3521): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onDestroy()
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider(11953): TimaSignature is unavailable
,D/ActivityThread(11953): Added TimaKeyStore provider
I/ActivityManager( 3521): Killing 11095:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/ResourcesManager(11953): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11953): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11968): MountEmulatedStorage()
E/Zygote  (11968): v2
I/libpersona(11968): KNOX_SDCARD checking this for 1000
I/libpersona(11968): KNOX_SDCARD not a persona
,I/SELinux (11968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11111:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11968): TimaSignature is unavailable
,D/ActivityThread(11968): Added TimaKeyStore provider
,D/ResourcesManager(11968): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend false
,D/SecContentProvider2( 3521): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3521): mCursor = null
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11988): MountEmulatedStorage()
I/libpersona(11988): KNOX_SDCARD checking this for 10039
E/Zygote  (11988): v2
I/libpersona(11988): KNOX_SDCARD not a persona
I/SELinux (11988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11988): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11988 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11157:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11988): TimaSignature is unavailable
,D/ActivityThread(11988): Added TimaKeyStore provider
,D/ResourcesManager(11988): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11988): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11988): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11988): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(11988): PushLog.txt file is not deleted.
D/SPPClientService(11988): PushLog.txt file is not deleted.
D/SPPClientService(11988): ============PushLog. stop!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12005): MountEmulatedStorage()
E/Zygote  (12005): v2
I/libpersona(12005): KNOX_SDCARD checking this for 10045
I/libpersona(12005): KNOX_SDCARD not a persona
,I/SELinux (12005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12005): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12005 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11139:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,E/SPPClientService(11988): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider(12005): TimaSignature is unavailable
,D/ActivityThread(12005): Added TimaKeyStore provider
,D/ResourcesManager(12005): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12005): [SSP] onCreated
,I/SA      (12005): [TPM] There is no property file
,I/SA      (12005): [SCU] isHaveSA() - false
,I/SA      (12005): [TPM] getModelProperty : null
I/SA      (12005): [TPM] getCSCProperty : null
,I/SA      (12005): [DM] init START
,I/SA      (12005): [DM] This device is not a Vodafone
,I/SA      (12005): checkReactivationActive for LOLLIPOP
,I/SA      (12005): checkReactivationActive for reactiveActive
I/SA      (12005): setSupportRL : true
,I/SA      (12005): [SCU] isHaveSA() - false
I/SA      (12005): support phone number id : false
I/SA      (12005): [DM] init END
I/SA      (12005): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12005): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12005): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (12005): [SLFUCHKMGR] constructor called
,I/SA      (12005): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12005): [OR] == isSIMCardReady false ==
,I/SA      (12005): [SCU] == networkStateCheck == false
I/SA      (12005): [OR] onReceive END
,I/ActivityManager( 3521): Killing 11205:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12026): MountEmulatedStorage()
E/Zygote  (12026): v2
I/libpersona(12026): KNOX_SDCARD checking this for 10067
I/libpersona(12026): KNOX_SDCARD not a persona
,I/SELinux (12026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12026 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12026): TimaSignature is unavailable
,D/ActivityThread(12026): Added TimaKeyStore provider
,D/ResourcesManager(12026): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,E/dhcpcd  (12041): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12041): version 5.5.6 starting
,E/dhcpcd  (12041): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/sCloudBackupApp(12026): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12026): Other Intent
,I/ActivityManager( 3521): Killing 11222:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/dhcpcd  (12041): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12041): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12041): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12041): bssid match
I/dhcpcd  (12041): wlan0: rebinding lease of 192.168.1.124
,D/accuweather( 5198): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5198): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5198): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5198): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5198): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5198): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5198): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12049): MountEmulatedStorage()
I/libpersona(12049): KNOX_SDCARD checking this for 1000
E/Zygote  (12049): v2
I/libpersona(12049): KNOX_SDCARD not a persona
,I/SELinux (12049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12049): TimaSignature is unavailable
,D/ActivityThread(12049): Added TimaKeyStore provider
,D/ResourcesManager(12049): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12049): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12049): premStatus:2
,I/KnoxUsageLogPro(12049): isEulaShown : false
I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12064): MountEmulatedStorage()
E/Zygote  (12064): v2
I/libpersona(12064): KNOX_SDCARD checking this for 10090
I/libpersona(12064): KNOX_SDCARD not a persona
,I/SELinux (12064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12064): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12064 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11190:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12064): TimaSignature is unavailable
,D/ActivityThread(12064): Added TimaKeyStore provider
,D/ResourcesManager(12064): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12080): MountEmulatedStorage()
I/libpersona(12080): KNOX_SDCARD checking this for 10127
E/Zygote  (12080): v2
I/libpersona(12080): KNOX_SDCARD not a persona
,I/SELinux (12080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12080 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11240:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12080): TimaSignature is unavailable
,D/ActivityThread(12080): Added TimaKeyStore provider
,D/ResourcesManager(12080): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12080): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12080): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12080): stopCheckCategoryVersion
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12097): MountEmulatedStorage()
I/libpersona(12097): KNOX_SDCARD checking this for 10136
E/Zygote  (12097): v2
I/libpersona(12097): KNOX_SDCARD not a persona
I/SELinux (12097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12097): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12097 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11254:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 277us total 9.879ms
,D/TimaKeyStoreProvider(12097): TimaSignature is unavailable
,D/ActivityThread(12097): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 312us total 8.738ms
,D/ResourcesManager(12097): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 511us total 8.625ms
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12097): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12097): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12097): Loading: webviewchromium
,I/LibraryLoader(12097): Time to load native libraries: 3 ms (timestamps 9456-9459)
I/LibraryLoader(12097): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12097): Binding Chromium to main looper Looper (main, tid 1) {54e778a}
,I/LibraryLoader(12097): Expected native library version number "",actual native library version number ""
,I/chromium(12097): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12097): Initializing chromium process, renderers=0
,W/art     (12097): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12097): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12097): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12097): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12097): Requires BLUETOOTH permission
,I/NSApplication(12097): Starting up...
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12166): MountEmulatedStorage()
I/libpersona(12166): KNOX_SDCARD checking this for 10150
,E/Zygote  (12166): v2
I/libpersona(12166): KNOX_SDCARD not a persona
I/SELinux (12166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12166 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11360:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12166): TimaSignature is unavailable
,D/ActivityThread(12166): Added TimaKeyStore provider
,D/ResourcesManager(12166): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12166): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12166): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12166): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12166): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12181): MountEmulatedStorage()
I/libpersona(12181): KNOX_SDCARD checking this for 10178
E/Zygote  (12181): v2
I/libpersona(12181): KNOX_SDCARD not a persona
,I/SELinux (12181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12181): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12181 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11377:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12181): TimaSignature is unavailable
,D/ActivityThread(12181): Added TimaKeyStore provider
,D/ResourcesManager(12181): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12181): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12181): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12181): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12181): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12181): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12204): MountEmulatedStorage()
I/libpersona(12204): KNOX_SDCARD checking this for 10082
E/Zygote  (12204): v2
I/libpersona(12204): KNOX_SDCARD not a persona
I/SELinux (12204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12204): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12204 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12204): TimaSignature is unavailable
,D/ActivityThread(12204): Added TimaKeyStore provider
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12204): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12204): onCreate
D/BadgeProvider(12204): DatabaseHelper
,E/Zygote  (12220): MountEmulatedStorage()
I/libpersona(12220): KNOX_SDCARD checking this for 1000
E/Zygote  (12220): v2
I/libpersona(12220): KNOX_SDCARD not a persona
,I/SELinux (12220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12220): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12220 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 11410:com.facebook.system/u0a10 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 11394:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##32
,D/BadgeProvider(12204): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider(12220): TimaSignature is unavailable
,D/ActivityThread(12220): Added TimaKeyStore provider
,D/BadgeProvider(12204): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12204): sendNotify, [notify] : null
D/BadgeProvider(12204): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12204): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12204): update, [UpdateCount] : 1
,D/Launcher.Model( 4002): reloadBadges entered.
,D/ResourcesManager(12220): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3521): Killing 11436:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,I/iu.Environment( 6784): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6784): num queued entries: 0
,I/iu.UploadsManager( 6784): num updated entries: 0
I/iu.SyncManager( 6784): NEXT; no task
,E/JavaBinder( 3521): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3521): Exception when sending broadcast to ComponentInfo{com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.networkstatereceiver.NetworkStateReceiver}
W/BroadcastQueue( 3521): android.os.TransactionTooLargeException
W/BroadcastQueue( 3521): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3521): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3521): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3521): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3521): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3521): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12238): MountEmulatedStorage()
E/Zygote  (12238): v2
I/libpersona(12238): KNOX_SDCARD checking this for 10013
I/libpersona(12238): KNOX_SDCARD not a persona
,I/SELinux (12238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12238): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12238 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12238): TimaSignature is unavailable
,D/ActivityThread(12238): Added TimaKeyStore provider
,D/ResourcesManager(12238): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3521): Killing 11470:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4070): Starting #10
,I/Hs20UtilService( 4070): Message received 5007
,D/NearbySettings( 8751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8751): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8751): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11340): NETWORK_STATE_CHANGED_ACTION
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11740): 
,I/dhcpcd  (12041): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11740): 
,I/dhcpcd  (12041): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3521): do suspend true
,D/WifiP2pService( 3521): InactiveState{ what=143375 }
D/WifiP2pService( 3521): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3521): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3521): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3521): Not connected state, yet.
E/WifiStateMachine( 3521): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3521): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3521): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3521): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3521): callSECApiInt - ID [210]
,E/WifiStateMachine( 3521): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3521): updateNetworkInfo()
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3521): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3521): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3521): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/Hs20UtilService( 4070): Starting #11
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/NearbySettings( 8751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8751): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 4070): Message received 5007
,D/ConnectivityService( 3521): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3521): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3521): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3521): Unexpected mtu value: 0, wlan0
V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3521): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3521): Now, connected state.
E/WifiStateMachine( 3521): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3521): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/SignOutReceiver(11340): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
E/WifiStateMachine( 3521): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiNative-HAL( 3521): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3521): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3521): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3521): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
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
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4070): Starting #12
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
I/Hs20UtilService( 4070): Message received 5007
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/NearbySettings( 8751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8751): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8751): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8751): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8751): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8751): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11340): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4070): Starting #13
,V/        ( 2845): QcRouteController
I/Hs20UtilService( 4070): Message received 5007
,D/NearbySettings( 8751): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8751): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3521): callSECApi what=220
D/WifiStateMachine( 3521): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3521): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3521): LTETest block dns file not exists
,E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3521): updateNetworkInfo()
D/ConnectivityService( 3521): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3521): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3521):    accepting network in place of null
,E/CSLegacyTypeTracker( 3521): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3521): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/TelephonyNetworkFactory( 3984): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3521): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3521): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3521): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): updateIfacesLocked()
V/NetworkStats( 3521): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3521): UpdateStatsForKnox
D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
,D/EntConnectivity( 3521): Not allowed due to - mEnabled false
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/ConnectivityService( 3521): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
V/        ( 2845): QcRouteController
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityManager.CallbackHandler( 6784): CM callback handler got msg 524290
V/NetworkStats( 3521): performPollLocked() took 7ms
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,I/SignOutReceiver(11340): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3521): route cmd failed: 
W/NetworkManagementService( 3521): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '75 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 75 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
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
D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/ConnectivityService( 3521): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6784): CM callback handler got msg 524295
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 6784): CM callback handler got msg 524295
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
I/SurfaceFlinger( 2850): id=15 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521
D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3521): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:09:22 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455034162087], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455034162072]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3521): Validated
D/ConnectivityService( 3521): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3521): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3521): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6784): CM callback handler got msg 524290
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
,D/ConnectivityService( 3521): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3521): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3521): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3521): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3521): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/SmartBondingService( 3521): getSBEnabled() enabled =false
D/GpsLocationProvider( 3521): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6278): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6278): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/SmartBondingService( 3521): getNetworkEnabled : wifi : true mobile : false
,I/NetworkMonitor(11860): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5353): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5353): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11844): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11844): sales region : global
I/PCWCLIENTTRACE_PushUtil(11844): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11844): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11903): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11903): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11920): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 17:09:22 GMT+01:00 2016
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11936): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11936): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11936): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(11953): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11936): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11936): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11936): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11936): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11936): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onDestroy()
,E/SPPClientService(11988): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12005): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (12005): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12005): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12005): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12005): [OR] == isSIMCardReady false ==
,I/SA      (12005): [SCU] == networkStateCheck == true
,I/SA      (12005): [DM] getCountryCodeFromCSC : PL
I/SA      (12005): isChinaCountryCode : false
I/SA      (12005): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12005): [OR] == networkStateCheck true ==
I/SA      (12005): [OR] GetMyCountryZoneTask
I/SA      (12005): [OR] onReceive END
,I/SA      (12005): [SRS] prepareGetMyCountryZone
,I/SA      (12005): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12005): [SSP] query invoked
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12005): [TPMU] GetMccFromDB : null
I/SA      (12005): [SCU] getMccFromPreferece mcc = 260
I/SA      (12005): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12026): Other Intent
,D/accuweather( 5198): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5198): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5198): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5198): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5198): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5198): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5198): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12049): premStatus:2
,I/KnoxUsageLogPro(12049): isEulaShown : false
I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12080): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12080): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12080): stopCheckCategoryVersion
,D/QuickConnect(12166): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12166): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12166): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/iu.Environment( 6784): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6784): num queued entries: 0
,I/iu.UploadsManager( 6784): num updated entries: 0
,I/iu.SyncManager( 6784): NEXT; no task
,D/WaitQueueForNetworkActivate(12238): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12238): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3521): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12238): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12238): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine(12238): exit::IDLE
D/InitializeManagerStateMachine(12238): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12238): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12238): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12238): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12238): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12238): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12238): entry::SUCCESS
D/hcjo    (12238): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12238): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12238): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12238): exit::SUCCESS
D/InitializeManagerStateMachine(12238): entry::IDLE
,I/SA      (12005): [RC New] Execute method=[GET] start
,I/SA      (12005): [RC New] Security=[true]
,I/System.out(12005): Thread-1690(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12005): Thread-1690(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12005): Thread-1690(ApacheHTTPLog):isShipBuild true
I/System.out(12005): Thread-1690(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3521): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (12005): [RC New] [v2liruge] api execute + 582
I/SA      (12005): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(12005): AsyncTask #1 calls detatch()
I/SA      (12005): [TPMU] getNetworkMcc : 
I/SA      (12005): [SCU] saveMccToPreferece Start
I/SA      (12005): [SCU] RegionMCC : 260
I/SA      (12005): [SSP] query invoked
I/SA      (12005): [TPMU] GetMccFromDB : null
I/SA      (12005): [SCU] getMccFromPreferece mcc = 260
I/SA      (12005): [SCU] saveMccToPreferece End
I/SA      (12005): [RC New] executeRequest [v2liruge] end. 603
I/SA      (12005): [RC New] Execute end
I/SA      (12005): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12005): [OR] GetMyCountryZoneTask Success
E/Watchdog( 3521): !@Sync 7
,I/dhcpcd  (12041): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4623): callingUid 10014, callindPid: 4623
,D/ResourcesManager(11860): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11860): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11860): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11860): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11860): Conditions not met for autocaching.
I/MusicLeanback(11860): Stop autocaching.
,D/WearableClient(11860): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11860): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11860): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11860): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11860): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11860): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11860): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2dcf7516 that was originally bound here
E/ActivityThread(11860): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2dcf7516 that was originally bound here
E/ActivityThread(11860): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11860): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11860): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11860): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11860): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11860): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11860): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11860): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11860): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11860): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11860): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11860): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11860): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11860): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11860): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11860): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11860): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11860): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11860): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11860): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11860): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11860): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11860): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11860): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11740): 
,I/jxcore-log(11740): Test app app.js loaded
I/jxcore-log(11740): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11740): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f13842 added. We now have 1 listener(s)
,I/jxcore-log(11740): BLE advertisement is supported
I/jxcore-log(11740): 
,I/chromium(11740): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WifiStateMachine( 3521): REQUEST_POWER_SAVE_ON
,I/jxcore-log(11740): --= Surplus to requirements =--
I/jxcore-log(11740): 
I/jxcore-log(11740): ****TEST TOOK:  ms ****
I/jxcore-log(11740): 
I/jxcore-log(11740): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11740): 
,E/WifiStateMachine( 3521): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 62086(3MB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 49MB/65MB, paused 1.227ms total 74.697ms
,I/GAV4    (12097): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12336): 
D/AndroidRuntime(12336): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12336): CheckJNI is OFF
,D/AndroidRuntime(12336): readGMSProperty: start
D/AndroidRuntime(12336): readGMSProperty: already setted!!
,D/AndroidRuntime(12336): readGMSProperty: end
D/AndroidRuntime(12336): addProductProperty: start
,D/SSRM:n  ( 3521): SIOP:: AP = 290, PST = 255, CUR = 41
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (8/9)
I/SurfaceFlinger( 2850): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3521): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3521) eventTime = 224663
D/PowerManagerService( 3521): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3521 (0x0)
D/PowerManagerService( 3521): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3521, ws=WorkSource{10060}) (elapsedTime=3466)
,E/AffinityControl(12336): AffinityControl: registerfunction enter
,D/AndroidRuntime(12336): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3521): START PACKAGE DELETE: observer{729164144}
D/PackageManager( 3521): pkg{<packageName>}
D/PackageManager( 3521): user{0}
D/PackageManager( 3521): caller{2000}
D/PackageManager( 3521): flags{3}
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3521): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3521): !@killApplicatoin: 10648, uninstall pkg
I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10648 user=-1: uninstall pkg
I/ActivityManager( 3521): Killing 11740:com.test.thalitest/u0a648 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3521):   Force finishing activity ActivityRecord{c62fd4a u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3521): mDVFSHelper.acquire()
,W/PackageSettings( 3521): Skipping PackageSetting{9c05c22 com.example.hello/10563} due to missing metadata
,D/WifiService( 3521): Client connection lost with reason: 4
,I/WindowState( 3521): WIN DEATH: Window{647520 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10648 user=0: pkg removed
,I/ActivityManager( 3521):   Force finishing activity ActivityRecord{c62fd4a u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3521): Duplicate finish request for ActivityRecord{c62fd4a u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6278): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 8958): Explicit concurrent mark sweep GC freed 29272(1642KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 358us total 45.744ms
,I/art     ( 6784): Explicit concurrent mark sweep GC freed 6324(257KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.936ms total 54.393ms
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 7546(447KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.328ms total 50.465ms
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6278): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 13
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6278): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/SamsungIME( 4487): mOCRHelper is null
,W/GeofencerStateMachine( 4623): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/LWLocationManager(11453): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(11453): getLastUiLocationId() : mLastUiLocationId = -100
,I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/libpersona(12353): KNOX_SDCARD checking this for 10063
E/Zygote  (12353): MountEmulatedStorage()
I/libpersona(12353): KNOX_SDCARD not a persona
E/Zygote  (12353): v2
I/ActivityManager( 3521): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12353 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/SELinux (12353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourceType( 5353): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5353): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/TimaKeyStoreProvider(12353): TimaSignature is unavailable
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ActivityThread(12353): Added TimaKeyStore provider
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/SecContentProvider2( 3521): mCursor = null
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/RegisteredServicesCache( 3968): empty dynamic service
,D/ResourcesManager(12353): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager(11453): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6278): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6278): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6278): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6278): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6278): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
,I/DBG_DM  ( 6278): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2850): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6278): updateVisibility : ActivityRecord{60ac2c2 token=android.os.BinderProxy@125c50bf {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/VRSetupWizardStub/PackageIntentReceiver(12353): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12353): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12353): packagename:com.test.thalitest
,D/ResourcesManager(11453): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 17:09:25 GMT+01:00 2016
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive().END.
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/splitIntent( 3521): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3521): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11453): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/KLMS-2.4.521: (11936): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11936): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/KLMS-2.4.521: (11936): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(11453): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Zygote  (12375): MountEmulatedStorage()
E/Zygote  (12375): v2
I/libpersona(12375): KNOX_SDCARD checking this for 10106
I/libpersona(12375): KNOX_SDCARD not a persona
,I/SELinux (12375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux (12375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/ActivityManager( 3521): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12375 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.521: (11936): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11936): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11453): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/TimaKeyStoreProvider(12375): TimaSignature is unavailable
,D/ActivityThread(12375): Added TimaKeyStore provider
,W/InputMethodManagerService( 3521): Got RemoteException sending setActive(false) notification to pid 11740 uid 10648
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-232, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3521): stay LED for fully charged
,D/RCPManager(12049):  in createShortcut() for packageName: com.test.thalitest userId0
D/EnterpriseDeviceManagerService( 3521): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 3521): Admin package name: com.google.android.gms
I/art     ( 3521): Explicit concurrent mark sweep GC freed 20833(1582KB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 49MB/65MB, paused 2.426ms total 333.852ms
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(12375): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/RCPManagerService( 3521):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3521): queryAllProviders():  providerCallBack is not register for 0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/Timeline( 6278): Timeline: Activity_idle id: android.os.BinderProxy@125c50bf time:225211
,D/ResourcesManager(11453): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/elm:14491(12375): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12375): ELMEngine.ELMEngine( context ).
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/elm:14491(12375): MDMBridge.setEnterpriseBridge()
E/Zygote  (12393): MountEmulatedStorage()
E/Zygote  (12393): v2
I/libpersona(12393): KNOX_SDCARD checking this for 10050
I/libpersona(12393): KNOX_SDCARD not a persona
,I/SELinux (12393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/SELinux (12393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12393 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12375): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12375): ElmAgentService : onCreate()
,D/elm:14491(12375): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/TimaKeyStoreProvider(12393): TimaSignature is unavailable
D/ActivityThread(12393): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11936): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11453): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12409): MountEmulatedStorage()
E/Zygote  (12409): v2
I/libpersona(12409): KNOX_SDCARD checking this for 10183
I/libpersona(12409): KNOX_SDCARD not a persona
,I/SELinux (12409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/SELinux (12409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12409 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/elm:14491(12375): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12375): MDMBridge.getInstance()
D/elm:14491(12375): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/elm:14491(12375): MDMBridge.getAllLicenseInfoFromSDK()
,D/RCPManagerService( 3521): PackageReceiver onReceive()
I/HarmonyEASService( 3521): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{3318b8cf u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:225250
,D/KnoxMUMContainerPolicy( 3521): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3521): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): uID is 10648
V/EnterpriseBillingPolicy( 3521): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - end - null
,D/TimaKeyStoreProvider(12409): TimaSignature is unavailable
,D/PackageManager( 3521): delete codoeFile: 
D/ActivityThread(12409): Added TimaKeyStore provider
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12393): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (11936): KLMSIntentService(): onDestroy()
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,I/AASAUninstall( 3521):  com.test.thalitest not target!
W/ResourcesManager(12393): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/PackageManager( 3521): result of delete: 1{729164144}
W/ResourcesManager(12393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12393): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ResourcesManager(12393): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12393): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12393): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12393): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12393): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  (12425): MountEmulatedStorage()
E/Zygote  (12425): v2
I/libpersona(12425): KNOX_SDCARD checking this for 10101
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
I/libpersona(12425): KNOX_SDCARD not a persona
,I/SELinux (12425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12425): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12425 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/elm:14491(12375): ElmAgentService : onDestroy().
,D/AndroidRuntime(12336): Shutting down VM
,D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12425): TimaSignature is unavailable
,D/ActivityThread(12425): Added TimaKeyStore provider
,D/ResourcesManager(11453): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/Zygote  (12441): MountEmulatedStorage()
E/Zygote  (12441): v2
I/libpersona(12441): KNOX_SDCARD checking this for 10019
I/libpersona(12441): KNOX_SDCARD not a persona
D/PackageManager( 3521): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SELinux (12441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(12409): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/SELinux (12441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 296us total 10.473ms
,I/ActivityManager( 3521): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12441 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12441): TimaSignature is unavailable
D/ActivityThread(12441): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 244us total 7.444ms
,W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 487us total 8.917ms
,I/ActivityManager( 3521): Killing 11485:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=24_task.xml
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(12425): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SQLiteLog(12409): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/ResourcesManager(12441): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/StatusBar( 3691): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
D/PanelView( 3691): There is/are notification(s) 
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
,D/ResourcesManager(11453): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/ActivityManager( 3521): Killing 11453:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/com.sec.android.service.health.upgrade.UninstallReceiver(12441): onReceive()
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/com.sec.android.service.health.upgrade.UninstallReceiver(12441): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/com.sec.android.service.health.upgrade.UninstallReceiver(12441): onReceive() : package name is not s health. Return !!!
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 3521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,E/Zygote  (12458): MountEmulatedStorage()
E/Zygote  (12458): v2
I/libpersona(12458): KNOX_SDCARD checking this for 10190
I/libpersona(12458): KNOX_SDCARD not a persona
,I/SELinux (12458): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12458): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12458 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (12458): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 10859:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,E/JavaBinder( 3521): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3521): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.locationwidget/com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider}
W/BroadcastQueue( 3521): android.os.TransactionTooLargeException
W/BroadcastQueue( 3521): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3521): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3521): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3521): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3521): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3521): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3521): 	at android.os.Binder.execTransact(Binder.java:446)
,D/DocsApplication(12425): Installing DEX configuration.
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/TimaKeyStoreProvider(12458): TimaSignature is unavailable
,D/ActivityThread(12458): Added TimaKeyStore provider
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Zygote  (12473): MountEmulatedStorage()
E/Zygote  (12473): v2
I/libpersona(12473): KNOX_SDCARD checking this for 10022
I/libpersona(12473): KNOX_SDCARD not a persona
,I/SELinux (12473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/SELinux (12473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12473 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/SELinux (12473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/DexInstaller(12425): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12425): Provided clientMode=RELEASE, packageInfo=PackageInfo{2e13ddc3 com.google.android.apps.docs}
,I/ActivityManager( 3521): Killing 11518:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,D/TAG     (12425): onCreate()
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12458): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/CrossAppStateProvider(12425): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/TimaKeyStoreProvider(12473): TimaSignature is unavailable
,D/ActivityThread(12473): Added TimaKeyStore provider
,D/PackageManager( 3521): findPreferredActivity: No PreferredActivities set
,D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12458): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12458): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
D/ResourcesManager(12473): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12473): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/TapandpayWidget:Utils(12458): Clear T&P info.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TapandpayWidget:TanpandpayAppWidgetProvider(12458): Widget is not attached.
,I/ActivityManager( 3521): Killing 10366:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/PackageBroadcastService( 6784): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6784): Clearing selected account for com.test.thalitest
,D/UsbSettingsManager( 3521): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3521): onPackageRemoved : com.test.thalitest
,D/NearbySource(12393): Nearby Source Create!
I/LocationWidgetApplication(12473): onCreate() : start
D/NearbyContext(12393): Nearby Context Create!
,D/LocationWidgetApplication(12473): countryCode = POLAND
,I/LocationSettingsChecker( 6784): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 6784): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6784): Module APK com.google.android.play.games already loaded
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12393): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12393): Samsung link source created
,D/LocationManagerService( 3521): getProviders()=[]
D/LocationManagerService( 3521): getProviders()=[passive]
D/LocationManagerService( 3521): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12473): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12473): getLastUiLocationId() : mLastUiLocationId = -100
,I/LocationWidgetFuctionData(12473): readDB
,E/NetworkScheduler.SchedulerReceiver( 4623): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4623): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationWidgetFuctionData(12473): selectedAppSize: 3
I/LocationWidgetFuctionData(12473): configPlaceList aroundMeItems
,D/gH_CompatibleDatabase( 6784): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 6784): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/ChimeraCfgMgr( 6784): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6784): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/gH_MetricsDatabase( 6784): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6784): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/gH_CompatibleDatabase( 6784): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6784): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6784): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6784): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6784): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6784): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6784): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6784): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6784): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,E/Zygote  (12500): MountEmulatedStorage()
I/libpersona(12500): KNOX_SDCARD checking this for 10003
E/Zygote  (12500): v2
I/libpersona(12500): KNOX_SDCARD not a persona
,I/SELinux (12500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12500 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/ActivityThread(10329): Failed to find provider info for com.facebook.appmanager.installrecord
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12500): TimaSignature is unavailable
D/ActivityThread(12500): Added TimaKeyStore provider
,I/Icing   ( 6784): doRemovePackageData com.test.thalitest
,E/Zygote  (12518): MountEmulatedStorage()
E/Zygote  (12518): v2
I/libpersona(12518): KNOX_SDCARD checking this for 10031
I/libpersona(12518): KNOX_SDCARD not a persona
,I/SELinux (12518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12518): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12518 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(12500): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
D/TimaKeyStoreProvider(12518): TimaSignature is unavailable
D/ContactProvider(12393): getAllContactInfoList Start
D/ActivityThread(12518): Added TimaKeyStore provider
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12536): MountEmulatedStorage()
,E/Zygote  (12536): v2
I/libpersona(12536): KNOX_SDCARD checking this for 10052
D/UserAnalysis.PlaceProvider(12500): PlaceProvider onCreate()
I/libpersona(12536): KNOX_SDCARD not a persona
,I/SELinux (12536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12536 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (12536): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12518): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/ActivityManager( 3521): Killing 12204:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/UserAnalysis.SecureDbManager(12500): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(12500): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12500): Create SecureDbHelper
,D/TimaKeyStoreProvider(12536): TimaSignature is unavailable
,D/ActivityThread(12536): Added TimaKeyStore provider
,D/IntelligenceServiceApplication(12500): onCreate()
,D/ResourcesManager(12536): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12536): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12536): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12536): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12536): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12536): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/FileUtils(12500): Failed to chmod(/data/user/0/com.samsung.android.intelligenceservice/databases/privacy): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog(12500): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/Place.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12500): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/Place.db'.
E/SQLiteDatabase(12500): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:906)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:879)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
E/SQLiteDatabase(12500): 	at android.database.sqlite.SQLiteSecureOpenHelper.getReadableDatabase(SQLiteSecureOpenHelper.java:280)
E/SQLiteDatabase(12500): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:587)
E/SQLiteDatabase(12500): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12500): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12500): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12500): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12500): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(12500): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(12500): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
W/System.err(12500): 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
W/System.err(12500): 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
W/System.err(12500): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
W/System.err(12500): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
W/System.err(12500): 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:906)
W/System.err(12500): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:879)
W/System.err(12500): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
W/System.err(12500): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
W/System.err(12500): 	at android.database.sqlite.SQLiteSecureOpenHelper.getReadableDatabase(SQLiteSecureOpenHelper.java:280)
W/System.err(12500): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:587)
W/System.err(12500): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(12500): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(12500): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(12500): 	at android.os.Binder.execTransact(Binder.java:446)
D/UserAnalysis.PlaceProvider(12500): query - query() SQLiteException!!!
,E/LocationWidgetFuctionData(12473): configPlaceListItems : cursor is null!!
I/ActivityManager( 3521): Killing 8751:com.android.settings/1000 (adj 13): bgCount ##31
I/PCWCLIENTTRACE_PushUtil(11844): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11844): sales region : global
I/PCWCLIENTTRACE_PushUtil(11844): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11844): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (12552): MountEmulatedStorage()
I/libpersona(12552): KNOX_SDCARD checking this for 10035
E/Zygote  (12552): v2
I/libpersona(12552): KNOX_SDCARD not a persona
I/SELinux (12552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12552 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 11885:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
D/ContactProvider(12393): getAllContactInfoList End
I/syncContacts(12393): thread: 1753, sync time = 172
I/SELinux (12552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12552): TimaSignature is unavailable
,D/ActivityThread(12552): Added TimaKeyStore provider
,D/Mms/MmsApp(12536): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(12536): init before art
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/Mms/ArtClassLoader(12536): init [DONE] art
,D/Mms/TelephonyPermission(12536): start operation mode monitor
,D/WifiService( 3521): Client connection lost with reason: 4
,D/ResourcesManager(12536): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12536): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/FeatureConfig(12552): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/Mms/TelephonyPermission(12536): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12536): isDefault true
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3521): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3521): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
,D/UsbHostManager( 3521): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3521): displayNotification : [0ah,00h,01h]
D/Mms/MmsApp(12536): onCreate() com.android.mms
,D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3521): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3521): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/MtpClient(12393): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12393): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/Mms/MmsApp(12536): [start]    initCountryIso consume time = 36.377666
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/CountryDetector( 3521): The first listener is added
,W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/MmsApp(12536): [end]    initCountryIso consume time = 7.090459
D/Mms/MmsConfig(12536): [start]    MmsConfig.init() consume time = 0.06125
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/Finsky  (12518): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Mms/MmsConfig(12536): before partial update
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12552): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/Mms/MmsConfig(12536): Load Resize quality : 80
,D/Mms/MmsConfig(12536):  enable multiwindow = true
,E/Zygote  (12587): MountEmulatedStorage()
E/Zygote  (12587): v2
I/libpersona(12587): KNOX_SDCARD checking this for 10036
I/libpersona(12587): KNOX_SDCARD not a persona
,I/SELinux (12587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/UsbHostManager( 3521): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3521): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(12552): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux (12587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12587): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12587 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/Mms/MessageUtils(12536): setCountryDetector : update country detector info 
E/Mms/MessageUtils(12536): updateCountryIso : update country iso info 
,D/ResourcesManager(12552): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/Mms/PackageInfo(12536): com.sec.imsservice is not installed
D/Mms/MmsConfig(12536): [end]    init() consume time = 48.4245
,D/Mms/Contact(12536): [start]    init() consume time = 1.344458
,I/EventHub( 3521): Removing device '/dev/input/event10' due to inotify event
,D/TP/MmsSmsProvider( 3984): query,matched:13, calling pid = 12536
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TP/MmsSmsProvider( 3984): match 13:Elapsed time : 4.522 ms
,D/TimaKeyStoreProvider(12587): TimaSignature is unavailable
,D/ActivityThread(12587): Added TimaKeyStore provider
,W/ResourcesManager(12552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/Mms/Contact(12536): [end]    init consume time = 48.36225
,D/Mms/DraftCache(12536): [start]    rebuildCache consume time = 6.349542
,D/Mms/TelephonyUtils(12536): getSubId from simSlot 0, return Value = -1
,I/EventHub( 3521): Removing device '/dev/input/event7' due to inotify event
,D/Mms/DownloadManager(12536): roaming -> false (slotId = 0)
D/Mms/DownloadManager(12536): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(12536): auto download without roaming -> true
D/Mms/DownloadManager(12536): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(12536): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(12536): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(12536): roaming -> false (slotId = 1)
D/Mms/DownloadManager(12536): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(12536): auto download without roaming -> true
D/Mms/DownloadManager(12536): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(12536): auto download during roaming secondary -> false
D/Mms/DownloadManager(12536): mAutoDownload ------> true
D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/TP/MmsSmsProvider( 3984): query,matched:12, calling pid = 12536
W/ResourcesManager(12552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/MmsApp(12536): [end]    onCreate() consume time = 31.95825
W/ResourcesManager(12552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/FreeMessageStatusReceiver(12536): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/Conversation(12536): [start]    init() consume time = 4.67075
,E/RollingFileStream(12518): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
,D/TP/MmsSmsProvider( 3984): match 12:Elapsed time : 21.372 ms
,D/Finsky  (12518): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/ResourcesManager(12587): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/TP/MmsSmsProvider( 3984): deleteConversation threadId: 9223372036854775807
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/Settings(12518): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings(12518): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteLog(12518): (28) failed to open "/data/data/com.android.vending/databases/library.db" with flag (131138) and mode_t (0) due to error (30)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/Mms/DownloadManager(12536): Service state changed: Bundle[mParcelledData.dataSize=692]
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/SQLiteDatabase(12518): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase(12518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/SQLiteDatabase(12518): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase(12518): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase(12518): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3521): Removing device '/dev/input/event8' due to inotify event
,W/Finsky.CrashDetector(12518): Failed to write crash file cnt=0, ts=0.
W/Finsky.CrashDetector(12518): java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash804305: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector(12518): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/Finsky.CrashDetector(12518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/Finsky.CrashDetector(12518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/Finsky.CrashDetector(12518): 	at com.google.android.finsky.CrashDetector.safeWriteCrashFile(CrashDetector.java:169)
W/Finsky.CrashDetector(12518): 	at com.google.android.finsky.CrashDetector.uncaughtException(CrashDetector.java:97)
W/Finsky.CrashDetector(12518): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
W/Finsky.CrashDetector(12518): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
W/Finsky.CrashDetector(12518): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector(12518): 	at libcore.io.Posix.open(Native Method)
W/Finsky.CrashDetector(12518): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/Finsky.CrashDetector(12518): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/Finsky.CrashDetector(12518): 	... 6 more
D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/AndroidRuntime(12518): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime(12518): Process: com.android.vending, PID: 12518
E/AndroidRuntime(12518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12518): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
,E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12518): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/AndroidRuntime(12518): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/AndroidRuntime(12518): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime(12518): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime(12518): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog(12518): (28) failed to open "/data/data/com.android.vending/databases/localappstate.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12518): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase(12518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12518): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:3082)
E/SQLiteDatabase(12518): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(12518): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(12518): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(12518): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(12518): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(12518): 	,at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog(12518): (28) failed to open "/data/data/com.android.vending/databases/localappstate.db" with flag (131138) and mode_t (0) due to error (30)
D/Mms/DownloadManager(12536): roaming ------> false, mSimSlot = 0
,E/SQLiteLog(12425): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12518): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase(12518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
,E/SQLiteDatabase(12518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase(12518): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:4082)
E/SQLiteDatabase(12518): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(12518): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(12518): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(12518): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(12518): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(12518): 	at java.lang.Thread.run(Thread.java:818)
,D/Mms/TelephonyUtils(12536): getSubId from simSlot 0, return Value = -1
D/Mms/DownloadManager(12536): roaming -> false (slotId = 0)
D/Mms/DownloadManager(12536): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager(12536): auto download without roaming -> true
D/Mms/DownloadManager(12536): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(12536): mAutoDownload ------> true
,E/SQLiteDatabase(12425): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12425): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12425): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
,E/SQLiteDatabase(12425): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12425): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12425): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12425): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12425): 	,at buL.a(Scopes.java:65)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12425): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12425): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12425): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12425): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12425): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12425): 	at brQ.a(GellyInjector.java:119)
E/SQLiteDatabase(12425): 	at ajB.a(ScopedInje,ctor.java:216)
E/SQLiteDatabase(12425): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12425): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12425): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12425): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12425): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12425): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12425): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12425): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12425): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12425): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12425): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12425): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12425): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12425): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12425): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12425): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12425): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12425): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12425): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12425): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12425): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12425): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12425): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12425): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12425): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12425): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12425): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12425): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12425): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12425): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/EventHub( 3521): Removing device '/dev/input/event9' due to inotify event
W/SQLiteOpenHelper(12425): Opened ClientFlag.db in read-only mode
,D/Mms/FreeMessageReceiverService(12536): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(12536): onHandleIntent: ACTION_PACKAGE_REMOVED
,E/Zygote  (12625): MountEmulatedStorage()
I/libpersona(12625): KNOX_SDCARD checking this for 1000
E/Zygote  (12625): v2
I/libpersona(12625): KNOX_SDCARD not a persona
D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux (12625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(12552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SELinux (12625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.android.settings for broadcast com.android.settings/.TactileAssistBroadcastReceiver: pid=12625 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SQLiteLog(12425): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12425): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12425): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12425): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12425): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12425): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12425): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12425): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12425): Process: com.google.android.apps.docs, PID: 12425
E/AndroidRuntime(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12425): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12425): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12425): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12425): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12425): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12425): 	at aFp.run(AbstractDatabaseInstance.java:471)
,I/EventHub( 3521): Removing device '/dev/input/event11' due to inotify event
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
D/Mms/DraftCache(12536): [end]    rebuildCache consume time = 153.570083
,I/ActivityManager( 3521): Killing 11903:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/EventHub( 3521): Removing device '/dev/input/event12' due to inotify event
,E/SQLiteLog(11312): (28) failed to open "/data/user/0/com.google.android.gsf/databases/googlesettings.db" with flag (131138) and mode_t (0) due to error (30),
,E/SQLiteLog(12425): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 3521): Killing 11953:com.sec.android.soagent/u0a38 (adj 13): bgCount ##31
E/SQLiteDatabase(12425): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12425): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12425): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12425): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12425): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12425): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12425): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12425): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12425): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12425): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 3521): Killing 11920:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##32
E/SQLiteOpenHelper(12425): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12,425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12425): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12425): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12425): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12425): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12425): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12425): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12425): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12425): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12425): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12425): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12425): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12425): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase(11312): Failed to open database '/data/user/0/com.google.android.gsf/databases/googlesettings.db'.
E/SQLiteDatabase(11312): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11312): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11312): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11312): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(11312): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/SQLiteDatabase(11312): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(11312): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(11312): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(11312): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteOpenHelper(11312): Couldn't open googlesettings.db for writing (will try read-only):
E/SQLiteOpenHelper(11312): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(11312): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(11312): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(11312): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(11312): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/SQLiteOpenHelper(11312): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(11312): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(11312): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(11312): 	at android.os.Binder.execTransact(Binder.java:446)
E/DropBoxManagerService( 3521): Can't write: system_app_crash
E/DropBoxManagerService( 3521): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3521): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3521): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3521): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3521): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3521): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3521): 	... 5 more
E/DropBoxManagerService( 3521): Can't write: system_app_crash
E/DropBoxManagerService( 3521): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3521): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3521): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3521): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3521): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3521): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3521): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3521): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3521): 	... 5 more
E/SQLiteLog(11312): (28) failed to open "/data/user/0/com.google.android.gsf/databases/googlesettings.db-wal" with flag (131138) and mode_t (1b0) due to error (30)
,E/SQLiteLog(11312): (28) failed to open "/data/user/0/com.google.android.gsf/databases/googlesettings.db-shm" with flag (66) and mode_t (1b0) due to error (30)
E/SQLiteLog(11312): (14) cannot open file at line 30996 of [9491ba7d73]
E/SQLiteLog(11312): (14) os_unix.c:30996: (30) open(/data/user/0/com.google.android.gsf/databases/googlesettings.db-shm) - 
E/SQLiteLog(11312): (14) statement aborts at 1: [PRAGMA user_version;] unable to open database file
I/Process (12518): Sending signal. PID: 12518 SIG: 9
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12552): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/SQLiteLog(11312): (10) POSIX Error : 9 SQLite Error : 3850
W/ResourcesManager(12552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/DatabaseUtils(11312): Writing exception to parcel
E/DatabaseUtils(11312): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:768)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/DatabaseUtils(11312): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/DatabaseUtils(11312): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:988)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:241)
E/DatabaseUtils(11312): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/DatabaseUtils(11312): 	at com.google.android.gsf.settings.GoogleSettingsProvider.query(GoogleSettingsProvider.java:174)
E/DatabaseUtils(11312): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(11312): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(11312): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(11312): 	at android.os.Binder.execTransact(Binder.java:446)
D/TimaKeyStoreProvider(12625): TimaSignature is unavailable
I/EventHub( 3521): Removing device '/dev/input/event13' due to inotify event
D/ActivityThread(12625): Added TimaKeyStore provider
,D/ResourcesManager(12552): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/SQLiteLog(12587): (28) failed to open "/data/data/com.sec.android.app.shealth/databases/base.db" with flag (131138) and mode_t (0) due to error (30)
,W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/SQLiteDatabase(12587): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12587): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12587): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12587): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12587): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12587): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase(12587): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase(12587): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase(12587): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(12587): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(12587): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(12587): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(12587): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(12587): 	at java.lang.Thread.run(Thread.java:818)
,E/Zygote  (12647): MountEmulatedStorage()
E/Zygote  (12647): v2
I/libpersona(12647): KNOX_SDCARD checking this for 1000
I/libpersona(12647): KNOX_SDCARD not a persona
I/SELinux (12647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12647 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3521): Removing device '/dev/input/event14' due to inotify event
,I/ActivityManager( 3521): Killing 11968:com.policydm/1000 (adj 13): bgCount ##31
,D/ResourcesManager(12552): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/Process (12425): Sending signal. PID: 12425 SIG: 9
,W/ResourcesManager(12552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12647): TimaSignature is unavailable
,D/ActivityThread(12647): Added TimaKeyStore provider
,D/ResourcesManager(12552): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)(12587): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(12587): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(12587): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/ResourcesManager(12552): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/ActivityManager( 3521): Process com.android.vending (pid 12518)(adj 9) has died(268,1176)
,W/ResourcesManager(12552): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12625): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/BroadcastQueue( 3521): Skipping deliver [background] BroadcastRecord{289170fe u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{9663680 12425 com.google.android.apps.docs/10101/u0 remote:2852a703}: process crashing
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(12552): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12625): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12625): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(12625): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12625): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12625): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12625): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/ResourcesManager(12625): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.

```
