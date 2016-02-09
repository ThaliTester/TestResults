#### Test 584164489c56086_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
I/PowerManagerService( 3530): [PWL] Off : 140s ago
D/SSRM:n  ( 3530): SIOP:: AP = 250, PST = 256, CUR = 45
--------- beginning of main
D/AndroidRuntime(11748): 
D/AndroidRuntime(11748): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11748): CheckJNI is OFF
D/AndroidRuntime(11748): readGMSProperty: start
D/AndroidRuntime(11748): readGMSProperty: already setted!!
D/AndroidRuntime(11748): readGMSProperty: end
D/AndroidRuntime(11748): addProductProperty: start
E/AffinityControl(11748): AffinityControl: registerfunction enter
D/AndroidRuntime(11748): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3530): inState():  stateMachine is null !!
I/PersonaManagerService( 3530): PersonaId don't exist
I/ActivityManager( 3530): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3530): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3530): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3530): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3530): mDVFSHelper.acquire()
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/Zygote  (11766): MountEmulatedStorage()
I/libpersona(11766): KNOX_SDCARD checking this for 10642
E/Zygote  (11766): v2
I/libpersona(11766): KNOX_SDCARD not a persona
I/SELinux (11766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3530): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11766 uid=10642 gids={50642, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11766): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11748): Shutting down VM
D/PointerIcon( 3530): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3530): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3530): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3530): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11766): TimaSignature is unavailable
D/ActivityThread(11766): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11766): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6314): updateVisibility : ActivityRecord{695483f token=android.os.BinderProxy@df86160 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11766): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11766): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/BatteryService( 3530): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3530): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3530): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3530): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3530): Plugged
I/MotionRecognitionService( 3530): setPowerConnected  = true
D/BatteryService( 3530): stay LED for fully charged
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5664): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5664): Disconnected process message: 10
I/LibraryLoader(11766): Loading: webviewchromium
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/LibraryLoader(11766): Time to load native libraries: 11 ms (timestamps 5266-5277)
I/LibraryLoader(11766): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11766): Binding Chromium to main looper Looper (main, tid 1) {2811b20f}
I/LibraryLoader(11766): Expected native library version number "",actual native library version number ""
I/chromium(11766): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11766): Initializing chromium process, renderers=0
W/art     (11766): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11766): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11766): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11766): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11766): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11766): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11766): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11766): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11766): CordovaWebView is running on device made by: samsung
W/art     (11766): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11766): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 3530): Activity pause timeout for ActivityRecord{21c7d8aa u0 com.test.thalitest/.MainActivity t26}
D/Activity(11766): performCreate Call secproduct feature valuefalse
D/Activity(11766): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11766): Render dirty regions requested: true
D/ActivityManager( 3530): post active user change for 0
D/KnoxTimeoutHandler( 3530): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3530): handleActiveUserChange for user 0
V/ActivityThread(11766): updateVisibility : ActivityRecord{379a8c2a token=android.os.BinderProxy@340f44ed {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3530): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3530): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3530): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3530): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3530): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11766): Initialized EGL, version 1.4
I/OpenGLRenderer(11766): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1279827696 
D/OpenGLRenderer(11766): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11766): Enabling debug mode 0
D/mali_winsys(11766): new_window_surface returns 0x3000,  [1440x2560]-format:1
D/InputMethodManagerService( 3530): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3530): mDVFSHelper.release()
I/Timeline( 3530): Timeline: Activity_windows_visible id: ActivityRecord{21c7d8aa u0 com.test.thalitest/.MainActivity t26} time:235671
W/IInputConnectionWrapper(11766): showStatusIcon on inactive InputConnection
I/Timeline(11766): Timeline: Activity_idle id: android.os.BinderProxy@340f44ed time:235672
I/chromium(11766): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11766): 
D/JsMessageQueue(11766): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(11766): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361618560
I/chromium(11766): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11766): Initializing JXcore engine
W/jxcore-log(11766): JXcore engine is ready
,E/auditd  ( 4617): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3530): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3530): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11766): Starting JXcore engine
,W/jxcore-log(11766): Platform android
W/jxcore-log(11766): 
W/jxcore-log(11766): Process ARCH arm
W/jxcore-log(11766): 
,I/jxcore-log(11766): JXcore Cordova bridge is ready!
I/jxcore-log(11766): 
W/jxcore-log(11766): JXcore engine is started
,I/jxcore-log(11766): Toggling radios to true
I/jxcore-log(11766): 
,D/BluetoothAdapter(11766): enable()
,D/BluetoothAdapter(11766): enable(): BT is already enabled..!
,D/WifiService( 3530): New client listening to asynchronous messages
,I/WifiManager(11766): packageName : com.test.thalitest
,D/SecContentProvider( 3530): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3530): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3530): mCursor = null
D/WifiService( 3530): setWifiEnabled: true pid=11766, uid=10642
E/WifiService( 3530): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3530): Permission Denial: getCurrentUser() from pid=11766, uid=10642 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3530): Failed getting userId using ActivityManagerNative
W/WifiService( 3530): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11766, uid=10642 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3530): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3530): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3530): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3530): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3530): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3530): name = wifi_on
,I/WifiService( 3530): disconnect: pid=11766, uid=10642
,I/wpa_supplicant( 3834): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3530): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): Disconnected - do not scan
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3530): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3530): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3530): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3530): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11766): Radios toggled
I/jxcore-log(11766): 
,I/jxcore-log(11766): My device name is: samsung-SM-N910C
I/jxcore-log(11766): 
,E/WifiStateMachine( 3530): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3530): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3530): do suspend true
,D/WifiP2pService( 3530): InactiveState{ what=143375 }
,D/WifiP2pService( 3530): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3530): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore( 3530): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ConnectivityService( 3530): updateNetworkInfo()
,D/ConnectivityService( 3530): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3530): updateNetworkInfo()
I/WifiTrafficPoller( 3530): evaluateTrafficStatsPolling
D/ConnectivityService( 3530): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4110): Starting #8
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8869): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8869): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8869): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 8869): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8869): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3530): New client listening to asynchronous messages
,I/NearbySettings( 8869): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8869): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8869): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine( 3530): Start Disconnecting Watchdog 1
E/WifiStateMachine( 3530): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3530): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3530): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3530): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3530): do suspend true
,D/WifiP2pService( 3530): InactiveState{ what=143375 }
,D/WifiP2pService( 3530): P2pEnabledState{ what=143375 }
I/SignOutReceiver(11441): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/ConnectivityService( 3530): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3530): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
,D/ConnectivityService( 3530): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3530): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3530): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3530): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3530): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 3981): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524292
,D/WifiStateMachine( 3530): updateConfiguredNetworkExpiration - currTime: 1455009804173
D/WifiStateMachine( 3530): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3530): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3530): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3834): First Scan Start
,E/WifiStateMachine( 3530): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3530): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
D/EntConnectivity( 3530): Not allowed due to - mEnabled false
,D/ConnectivityService( 3530): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/WifiTrafficPoller( 3530): evaluateTrafficStatsPolling
E/WifiStateMachine( 3530): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3530): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3530): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3530): mCursor = null
,D/Tethering( 3530): MasterInitialState.processMessage what=3
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/SmartBondingService( 3530): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/SmartBondingService( 3530): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
V/NetworkStats( 3530): updateIfacesLocked()
V/NetworkStats( 3530): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3530): UpdateStatsForKnox
D/SmartBondingService( 3530): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
V/NetworkStats( 3530): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NetworkStats( 3530): performPollLocked() took 4ms
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
E/WifiStateMachine( 3530): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3530): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3530): setDetailed state send new extra info"NG700"
I/Hs20UtilService( 4110): Starting #9
I/Hs20UtilService( 4110): Message received 5007
,D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3530): mCursor = null
D/NearbySettings( 8869): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8869): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8869): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8869): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8869): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11441): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/ConnectivityService( 3530): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3530): updateDataUsageMap
I/ApplicationPolicy( 3530): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3530): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3530): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3530): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3530): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3530): No Active Data Connection
,I/DBG_DM  ( 6314): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6314): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11869): MountEmulatedStorage()
I/libpersona(11869): KNOX_SDCARD checking this for 10110
E/Zygote  (11869): v2
I/libpersona(11869): KNOX_SDCARD not a persona
,I/SELinux (11869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3530): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11869 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11869): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11869): TimaSignature is unavailable
,D/ActivityThread(11869): Added TimaKeyStore provider
,D/ResourcesManager(11869): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11869): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11869): not using cross-dex optimization: ART in use
,I/art     (11869): Thread[1,tid=11869,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11869): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11869): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11869): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11869): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11869): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11869): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11869): loading pre-built fallback odex files
,V/MultiDexClassLoader(11869): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11869): released odex store lock
D/DexLibLoader(11869): DexLibLoader.loadAll took 20 ms
,W/ca      (11869): Verify
,W/LightSharedPreferencesImpl(11869): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11869): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11869): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11869): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11869): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11869): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11869): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11869): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11869): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11869): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11869): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11869): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11869): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11869): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11869): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11869): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11869): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11869): 	... 10 more
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/Zygote  (11894): MountEmulatedStorage()
E/Zygote  (11894): v2
I/libpersona(11894): KNOX_SDCARD checking this for 1000
I/libpersona(11894): KNOX_SDCARD not a persona
I/SELinux (11894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11894): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11894 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3530): Killing 10976:com.android.mms/u0a52 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11869): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11869): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11894): TimaSignature is unavailable
,D/ActivityThread(11894): Added TimaKeyStore provider
,D/ResourcesManager(11894): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11894): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11894): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11894): new DMDBOpenHelper instance
,D/CountryDetector( 3530): No listener is left
,I/PCWCLIENTTRACE_PushUtil(11894): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11894): sales region : global
I/PCWCLIENTTRACE_PushUtil(11894): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11894): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/appmanager(:<default>):QuickExperimentControllerImpl(11869): Exposure of experiment com.facebook.common.network.l@2e0a9666 occurred when no user was logged in
W/BroadcastQueue( 3530): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{6f62729 u0 ReceiverList{1c28bcb0 11869 com.facebook.appmanager/10110/u0 remote:38efa7f3}}
I/PCWCLIENTTRACE_SYSTEMReceiver(11894): noConnectivity : true
W/BroadcastQueue( 3530): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{6f62729 u0 ReceiverList{1c28bcb0 11869 com.facebook.appmanager/10110/u0 remote:38efa7f3}}
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11917): MountEmulatedStorage()
E/Zygote  (11917): v2
I/libpersona(11917): KNOX_SDCARD checking this for 10135
I/libpersona(11917): KNOX_SDCARD not a persona
,I/SELinux (11917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11917): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11917 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3530): Killing 11046:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11917): TimaSignature is unavailable
,D/ActivityThread(11917): Added TimaKeyStore provider
,D/ResourcesManager(11917): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3530): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3b4cf39d u0 ReceiverList{7e9e274 11869 com.facebook.appmanager/10110/u0 remote:c727a47}}
,I/MusicStore(11917): Database version: 104
,D/ResourcesManager(11917): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11917): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11917): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11917): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11917): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11917): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e8a26ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11917): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11917): GMSCore installation verified
,I/ConfigStore(11917): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11917): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11869): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11869): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11917): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11917): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11869): Exposure of experiment com.facebook.imagepipeline.a.g@353c23d4 occurred when no user was logged in
D/WifiDisplayAdapter( 3530): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/appmanager(:<default>):QuickExperimentControllerImpl(11869): Exposure of experiment com.facebook.imagepipeline.a.d@b66c079 occurred when no user was logged in
,D/WifiDisplayAdapter( 3530): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3530): getStreamVolume 3 index 0
,I/MediaRouter(11917): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,I/art     (11869): Explicit concurrent mark sweep GC freed 44463(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 518us total 22.491ms
W/appmanager(:<default>):m(11869): No feature status reporters found; is this dead code?
,E/Zygote  (11951): MountEmulatedStorage()
I/libpersona(11951): KNOX_SDCARD checking this for 10002
E/Zygote  (11951): v2
I/libpersona(11951): KNOX_SDCARD not a persona
I/SELinux (11951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11951 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3530): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11917): type=WIFI subType= reason=null isConnected=false
,I/wpa_supplicant( 3834): nl80211: Received scan results (2 BSSes)
,I/ActivityManager( 3530): Killing 10317:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 8 sec 0 usec
,E/WifiStateMachine( 3530): [1,455,009,805,261 ms] noteScanEnd no scan source
,I/wpa_supplicant( 3834): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3834): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/TimaKeyStoreProvider(11951): TimaSignature is unavailable
,D/ActivityThread(11951): Added TimaKeyStore provider
,E/WifiStateMachine( 3530): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3ebc1318 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3530): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3530): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3530): setDetailed state send new extra info
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3530): mCursor = null
,D/ResourcesManager(11951): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3530): Killing 11062:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11973): MountEmulatedStorage()
E/Zygote  (11973): v2
I/libpersona(11973): KNOX_SDCARD checking this for 1000
I/libpersona(11973): KNOX_SDCARD not a persona
,I/SELinux (11973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11973 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11973): TimaSignature is unavailable
,D/ActivityThread(11973): Added TimaKeyStore provider
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/ResourcesManager(11973): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/wpa_supplicant( 3834): Associated with C0.AA.48
E/WifiStateMachine( 3530): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3530): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3530): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3530): mCursor = null
,I/DIAGMON_AGENT(11973): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3530): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3530): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3530): mCursor = null
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3530): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3530): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3834): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3834): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3834): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3834): Blacklist: Clear (temp) 
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3530): Network connection established
D/WifiNative-HAL( 3530): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3530): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3530): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3530): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3530): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3530): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3530): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3530): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3530): updateNetworkInfo()
D/ConnectivityService( 3530): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3530): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3530): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3530): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3530): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
E/WifiStateMachine( 3530): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3530): mCursor = null
,E/WifiStateMachine( 3530): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3530): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(11973): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11973): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11973): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11973): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11990): MountEmulatedStorage()
I/libpersona(11990): KNOX_SDCARD checking this for 10012
E/Zygote  (11990): v2
I/libpersona(11990): KNOX_SDCARD not a persona
,I/SELinux (11990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11990): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11990 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3530): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3530): do suspend false
,D/SecContentProvider2( 3530): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3530): InactiveState{ what=143375 }
D/SecContentProvider2( 3530): mCursor = null
D/WifiP2pService( 3530): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider(11990): TimaSignature is unavailable
,D/ActivityThread(11990): Added TimaKeyStore provider
,D/ResourcesManager(11990): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3530): Killing 10943:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11990): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12006): MountEmulatedStorage()
,E/Zygote  (12006): v2
I/libpersona(12006): KNOX_SDCARD checking this for 10021
I/libpersona(12006): KNOX_SDCARD not a persona
I/SELinux (12006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12006): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12006 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3530): Killing 9914:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/9914/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12006): TimaSignature is unavailable
,D/ActivityThread(12006): Added TimaKeyStore provider
,D/ResourcesManager(12006): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 10:23:25 GMT+01:00 2016
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12006): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12006): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12006): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12006): StateImplV2(): networkChangeListener().END
,E/Zygote  (12022): MountEmulatedStorage()
I/libpersona(12022): KNOX_SDCARD checking this for 10038
E/Zygote  (12022): v2
I/libpersona(12022): KNOX_SDCARD not a persona
I/SELinux (12022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12022 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3530): Killing 11105:com.policydm/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12022): TimaSignature is unavailable
,D/ActivityThread(12022): Added TimaKeyStore provider
E/lowmemorykiller( 2828): Error writing /proc/11105/oom_score_adj; errno=22
,D/ResourcesManager(12022): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12022): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,I/ActivityManager( 3530): Killing 11123:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/JavaBinder( 3530): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3530): Exception when sending broadcast to ComponentInfo{com.policydm/com.policydm.XDMBroadcastReceiver}
W/BroadcastQueue( 3530): android.os.TransactionTooLargeException
W/BroadcastQueue( 3530): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3530): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3530): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3530): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3530): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3530): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3530): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3530): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3530): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12038): MountEmulatedStorage()
I/libpersona(12038): KNOX_SDCARD checking this for 1000
E/Zygote  (12038): v2
I/libpersona(12038): KNOX_SDCARD not a persona
,I/SELinux (12038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 433us total 9.961ms
,E/dhcpcd  (12046): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12046): version 5.5.6 starting
,E/dhcpcd  (12046): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 476us total 9.216ms
,D/TimaKeyStoreProvider(12038): TimaSignature is unavailable
D/ActivityThread(12038): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 435us total 8.630ms
,D/ResourcesManager(12038): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/dhcpcd  (12046): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12046): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12046): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12046): bssid match
I/dhcpcd  (12046): wlan0: rebinding lease of 192.168.1.124
,E/SPPClientService(11161): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      (11292): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11292): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11292): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11292): [SLFUCHKMGR] constructor called
E/SPPClientService(11161): [[SystemStateMonitorService]] No Active Internet
I/SA      (11292): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11292): [OR] == isSIMCardReady false ==
I/SA      (11292): [SCU] == networkStateCheck == false
I/SA      (11292): [OR] onReceive END
I/ActivityManager( 3530): Killing 11138:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
E/lowmemorykiller( 2828): Error writing /proc/11138/oom_score_adj; errno=22
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/Zygote  (12068): MountEmulatedStorage()
I/libpersona(12068): KNOX_SDCARD checking this for 10067
E/Zygote  (12068): v2
I/libpersona(12068): KNOX_SDCARD not a persona
I/SELinux (12068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12068 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12068): TimaSignature is unavailable
,D/ActivityThread(12068): Added TimaKeyStore provider
,D/ResourcesManager(12068): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12068): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12068): Other Intent
,I/ActivityManager( 3530): Killing 11231:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/accuweather( 5196): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5196): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5196): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5196): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5196): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12084): MountEmulatedStorage()
E/Zygote  (12084): v2
I/libpersona(12084): KNOX_SDCARD checking this for 1000
I/libpersona(12084): KNOX_SDCARD not a persona
,I/SELinux (12084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12084): TimaSignature is unavailable
,D/ActivityThread(12084): Added TimaKeyStore provider
,D/ResourcesManager(12084): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12084): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12084): premStatus:2
,I/KnoxUsageLogPro(12084): isEulaShown : false
I/KnoxUsageLogPro(12084): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12099): MountEmulatedStorage()
I/libpersona(12099): KNOX_SDCARD checking this for 10090
E/Zygote  (12099): v2
I/libpersona(12099): KNOX_SDCARD not a persona
,I/SELinux (12099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12099): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12099 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3530): Killing 11196:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12099): TimaSignature is unavailable
,D/ActivityThread(12099): Added TimaKeyStore provider
,D/ResourcesManager(12099): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12115): MountEmulatedStorage()
E/Zygote  (12115): v2
I/libpersona(12115): KNOX_SDCARD checking this for 10127
I/libpersona(12115): KNOX_SDCARD not a persona
,I/SELinux (12115): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12115): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12115): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12115 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3530): Killing 11176:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12115): TimaSignature is unavailable
,D/ActivityThread(12115): Added TimaKeyStore provider
,D/ResourcesManager(12115): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12115): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12115): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12115): stopCheckCategoryVersion
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12131): MountEmulatedStorage()
I/libpersona(12131): KNOX_SDCARD checking this for 10136
E/Zygote  (12131): v2
I/libpersona(12131): KNOX_SDCARD not a persona
,I/SELinux (12131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12131): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12131 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3530): Killing 11090:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12131): TimaSignature is unavailable
,D/ActivityThread(12131): Added TimaKeyStore provider
,D/ResourcesManager(12131): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12131): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12131): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12131): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12131): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12131): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12131): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12131): Loading: webviewchromium
,I/LibraryLoader(12131): Time to load native libraries: 3 ms (timestamps 9152-9155)
I/LibraryLoader(12131): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12131): Binding Chromium to main looper Looper (main, tid 1) {14cf80a9}
,I/LibraryLoader(12131): Expected native library version number "",actual native library version number ""
,I/chromium(12131): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12131): Initializing chromium process, renderers=0
,W/art     (12131): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12131): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12131): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
W/AudioManagerAndroid(12131): Requires BLUETOOTH permission
I/chromium(12131): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12131): Starting up...
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12199): MountEmulatedStorage()
E/Zygote  (12199): v2
I/libpersona(12199): KNOX_SDCARD checking this for 10150
I/libpersona(12199): KNOX_SDCARD not a persona
,I/SELinux (12199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12199 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3530): Killing 10228:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12199): TimaSignature is unavailable
,D/ActivityThread(12199): Added TimaKeyStore provider
,D/ResourcesManager(12199): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12199): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12199): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12199): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12199): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12216): MountEmulatedStorage()
I/libpersona(12216): KNOX_SDCARD checking this for 10178
E/Zygote  (12216): v2
I/libpersona(12216): KNOX_SDCARD not a persona
,I/SELinux (12216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12216): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12216 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3530): Killing 11214:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12216): TimaSignature is unavailable
,D/ActivityThread(12216): Added TimaKeyStore provider
,D/ResourcesManager(12216): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12216): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12216): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12216): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12216): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12216): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3530): exchangeData() failure , invalid userId
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12239): MountEmulatedStorage()
,E/Zygote  (12239): v2
I/libpersona(12239): KNOX_SDCARD checking this for 10082
I/libpersona(12239): KNOX_SDCARD not a persona
I/SELinux (12239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12239): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12239 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12239): TimaSignature is unavailable
,D/ActivityThread(12239): Added TimaKeyStore provider
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12239): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  (12255): MountEmulatedStorage()
E/Zygote  (12255): v2
I/libpersona(12255): KNOX_SDCARD checking this for 1000
I/libpersona(12255): KNOX_SDCARD not a persona
,I/SELinux (12255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12255 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/BadgeProvider(12239): onCreate
D/BadgeProvider(12239): DatabaseHelper
,I/ActivityManager( 3530): Killing 11308:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3530): Killing 11275:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##32
,D/TimaKeyStoreProvider(12255): TimaSignature is unavailable
,D/ActivityThread(12255): Added TimaKeyStore provider
,I/art     ( 3530): Explicit concurrent mark sweep GC freed 74568(4MB) AllocSpace objects, 44(704KB) LOS objects, 24% free, 49MB/65MB, paused 1.294ms total 85.493ms
,D/BadgeProvider(12239): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/ResourcesManager(12255): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3530): Killing 11326:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/Launcher.Model( 3999): reloadBadges entered.
,D/BadgeProvider(12239): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12239): sendNotify, [notify] : null
D/BadgeProvider(12239): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12239): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12239): update, [UpdateCount] : 1
,W/ActivityManager( 3530): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 6800): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6800): num queued entries: 0
I/iu.UploadsManager( 6800): num updated entries: 0
,I/iu.SyncManager( 6800): NEXT; no task
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12273): MountEmulatedStorage()
E/Zygote  (12273): v2
I/libpersona(12273): KNOX_SDCARD checking this for 10013
I/libpersona(12273): KNOX_SDCARD not a persona
,I/SELinux (12273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12273): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12273 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12273): TimaSignature is unavailable
,D/ActivityThread(12273): Added TimaKeyStore provider
,D/ResourcesManager(12273): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3530): Killing 11359:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/Hs20UtilService( 4110): Starting #10
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8869): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8869): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8869): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8869): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11441): NETWORK_STATE_CHANGED_ACTION
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11766): 
,I/dhcpcd  (12046): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12046): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3530): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3530): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11766): 
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11766): 
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11766): 
,E/WifiStateMachine( 3530): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3530): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3530): do suspend true
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11766): 
,D/WifiP2pService( 3530): InactiveState{ what=143375 }
D/WifiP2pService( 3530): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3530): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3530): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3530): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3530): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3530): Not connected state, yet.
E/WifiStateMachine( 3530): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3530): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3530): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3530): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3530): callSECApiInt - ID [210]
,E/WifiStateMachine( 3530): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3530): updateNetworkInfo()
,D/ConnectivityService( 3530): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3530): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3530): updateDnsLinkProperty: enter
I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11766): 
,D/WifiWatchdogStateMachine.DnsPinger( 3530): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3530): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3530): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3530): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4110): Starting #11
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8869): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 3530): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/NearbySettings( 8869): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3530): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 3530): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3530): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3530): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3530): Now, connected state.
E/WifiStateMachine( 3530): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3530): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3530): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,V/        ( 2845): QcRouteController
,I/WifiTrafficPoller( 3530): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3530): callSECApiVoid - ID [212]
E/WifiStateMachine( 3530): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 3530): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3530): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/SignOutReceiver(11441): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4110): Starting #12
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings( 8869): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8869): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8869): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8869): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8869): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8869): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11441): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4110): Starting #13
I/Hs20UtilService( 4110): Message received 5007
,V/        ( 2845): QcRouteController
,D/NearbySettings( 8869): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8869): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3530): callSECApi what=220
D/WifiStateMachine( 3530): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3530): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3530): LTETest block dns file not exists
,E/ConnectivityService( 3530): updateNetworkInfo()
D/ConnectivityService( 3530): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3530): updateNetworkInfo()
,D/ConnectivityService( 3530): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3530): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3530): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3530): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3530):    accepting network in place of null
,I/SignOutReceiver(11441): NETWORK_STATE_CHANGED_ACTION
D/CSLegacyTypeTracker( 3530): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3530): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/CSLegacyTypeTracker( 3530): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/Tethering( 3530): MasterInitialState.processMessage what=3
D/SmartBondingService( 3530): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3530): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/ConnectivityService( 3530): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats( 3530): updateIfacesLocked()
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
V/NetworkStats( 3530): performPollLocked(flags=0x1)
,D/SmartBondingService( 3530): getNetworkEnabled : wifi : true mobile : false
D/EntConnectivity( 3530): Not allowed due to - mEnabled false
D/ConnectivityService( 3530): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NetworkStatsFactory( 3530): UpdateStatsForKnox
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
V/NetworkStats( 3530): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524290
,D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
V/NetworkStats( 3530): performPollLocked() took 3ms
,D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
D/NtpTrustedTime( 3530): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3530): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3530
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/System.out( 3530): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 09:23:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455009807743], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455009807716]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3530): Validated
D/ConnectivityService( 3530): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3530): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3530): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3530): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/ConnectivityService( 3530): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3530): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3530): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3530): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3530): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3530): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3530): getSBEnabled() enabled =false
,D/SmartBondingService( 3530): getSBEnabled() enabled =false
D/GpsLocationProvider( 3530): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3530): getSBEnabled() enabled =false
,D/SmartBondingService( 3530): getNetworkEnabled : wifi : true mobile : false
,W/ResourceType( 5358): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5358): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6314): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6314): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11917): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11894): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11894): sales region : global
I/PCWCLIENTTRACE_PushUtil(11894): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11894): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3530): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3530): mCursor = null
,I/DIAGMON_AGENT(11973): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11973): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11990): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 10:23:28 GMT+01:00 2016
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12006): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12006): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12006): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(12022): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12006): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.521: (12006): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12006): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12006): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onDestroy()
,E/SPPClientService(11161): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11292): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11292): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11292): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11292): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11292): [OR] == isSIMCardReady false ==
,I/SA      (11292): [SCU] == networkStateCheck == true
I/SA      (11292): [DM] getCountryCodeFromCSC : PL
I/SA      (11292): isChinaCountryCode : false
I/SA      (11292): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11292): [OR] == networkStateCheck true ==
,I/SA      (11292): [OR] GetMyCountryZoneTask
I/SA      (11292): [OR] onReceive END
I/SA      (11292): [SRS] prepareGetMyCountryZone
,I/SA      (11292): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11292): [SSP] query invoked
,I/SA      (11292): [TPMU] GetMccFromDB : null
I/SA      (11292): [SCU] getMccFromPreferece mcc = 260
I/SA      (11292): [TPM] isNoProxy(default) : true
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SCloudBackupReceiver(12068): Other Intent
,D/accuweather( 5196): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5196): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5196): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5196): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5196): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12084): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12084): premStatus:2
,I/KnoxUsageLogPro(12084): isEulaShown : false
I/KnoxUsageLogPro(12084): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12115): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12115): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12115): stopCheckCategoryVersion
,D/QuickConnect(12199): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12199): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12199): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,D/RCPManagerService( 3530): exchangeData() failure , invalid userId
,I/iu.Environment( 6800): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6800): num queued entries: 0
I/iu.UploadsManager( 6800): num updated entries: 0
,I/iu.SyncManager( 6800): NEXT; no task
,D/WaitQueueForNetworkActivate(12273): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12273): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3530): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12273): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12273): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12273): exit::IDLE
D/InitializeManagerStateMachine(12273): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12273): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12273): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12273): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12273): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12273): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12273): entry::SUCCESS
D/hcjo    (12273): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12273): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12273): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12273): exit::SUCCESS
D/InitializeManagerStateMachine(12273): entry::IDLE
,I/SA      (11292): [RC New] Execute method=[GET] start
,I/SA      (11292): [RC New] Security=[true]
,I/System.out(11292): Thread-1555(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11292): Thread-1555(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11292): Thread-1555(ApacheHTTPLog):isShipBuild true
I/System.out(11292): Thread-1555(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3530): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11292): [RC New] [v2liruge] api execute + 596
I/SA      (11292): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11292): AsyncTask #1 calls detatch()
,I/SA      (11292): [TPMU] getNetworkMcc : 
,I/SA      (11292): [SCU] saveMccToPreferece Start
I/SA      (11292): [SCU] RegionMCC : 260
I/SA      (11292): [SSP] query invoked
,I/SA      (11292): [TPMU] GetMccFromDB : null
I/SA      (11292): [SCU] getMccFromPreferece mcc = 260
I/SA      (11292): [SCU] saveMccToPreferece End
,I/SA      (11292): [RC New] executeRequest [v2liruge] end. 616
I/SA      (11292): [RC New] Execute end
I/SA      (11292): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11292): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12046): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12046): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 4636): callingUid 10014, callindPid: 4636
,D/ResourcesManager(11917): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11917): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11917): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11917): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11917): Conditions not met for autocaching.
I/MusicLeanback(11917): Stop autocaching.
,D/WearableClient(11917): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11917): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11917): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11917): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11917): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11917): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11917): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@c039825 that was originally bound here
E/ActivityThread(11917): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@c039825 that was originally bound here
E/ActivityThread(11917): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11917): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11917): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11917): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11917): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11917): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11917): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11917): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11917): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11917): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11917): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11917): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11917): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11917): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11917): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11917): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11917): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11917): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11917): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11917): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11917): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11917): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11766): 
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11766): 
,I/jxcore-log(11766): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11766): 
,I/jxcore-log(11766): Test app app.js loaded
I/jxcore-log(11766): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11766): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb428fb added. We now have 1 listener(s)
,I/jxcore-log(11766): BLE advertisement is supported
I/jxcore-log(11766): 
,I/chromium(11766): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WifiStateMachine( 3530): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3530): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3530): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3530) eventTime = 244043
,D/PowerManagerService( 3530): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3530 (0x0)
,D/PowerManagerService( 3530): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3530, ws=WorkSource{10060}) (elapsedTime=3491)
,E/WifiStateMachine( 3530): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3530): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3530): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3530): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3530): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3530): getSBEnabled() enabled =false
,D/SmartBondingService( 3530): getSBEnabled() enabled =false
,D/SmartBondingService( 3530): getSBEnabled() enabled =false
,I/GAV4    (12131): Thread[GAThread,5,main]: No campaign data found.
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3530): route cmd failed: 
W/NetworkManagementService( 3530): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3530): '
W/NetworkManagementService( 3530): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3530): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3530): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3530): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3530): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3530): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3530): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3530): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3530): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3530): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3530): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3530): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityService( 3530): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524295
,D/SSRM:n  ( 3530): SIOP:: AP = 300, PST = 257, CUR = 45
,D/PackageManager( 3530): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/BatteryService( 3530): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3530): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3530): online:4, current avg:-230, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:84
,D/BatteryService( 3530): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3530): Plugged
,I/MotionRecognitionService( 3530): setPowerConnected  = true
,D/BatteryService( 3530): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5664): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5664): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PCWCLIENTTRACE_SYSTEMReceiver(11894): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11894): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11894): ================================================
,I/CSTORAGE(11894):  CSTORAGE_SKM_LIB v1.0.15
,I/CSTORAGE(11894): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11894): [GetString-S]
,E/art     (11894): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11894): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11894): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11894): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11894): sales region : global
I/PCWCLIENTTRACE_PushUtil(11894): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11894): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12046): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11766): --= Surplus to requirements =--
I/jxcore-log(11766): 
I/jxcore-log(11766): ****TEST TOOK:  ms ****
I/jxcore-log(11766): 
I/jxcore-log(11766): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11766): 
,D/AndroidRuntime(12418): 
D/AndroidRuntime(12418): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12418): CheckJNI is OFF
,D/AndroidRuntime(12418): readGMSProperty: start
D/AndroidRuntime(12418): readGMSProperty: already setted!!
,D/AndroidRuntime(12418): readGMSProperty: end
D/AndroidRuntime(12418): addProductProperty: start
,E/AffinityControl(12418): AffinityControl: registerfunction enter
,D/AndroidRuntime(12418): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3530): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3530): START PACKAGE DELETE: observer{723333823}
D/PackageManager( 3530): pkg{<packageName>}
D/PackageManager( 3530): user{0}
D/PackageManager( 3530): caller{2000}
D/PackageManager( 3530): flags{3}
D/PersonaManagerService( 3530): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3530): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3530): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3530): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3530): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3530): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3530): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3530): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3530): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3530): !@killApplicatoin: 10642, uninstall pkg
,I/ActivityManager( 3530): Force stopping com.test.thalitest appid=10642 user=-1: uninstall pkg
,I/ActivityManager( 3530): Killing 11766:com.test.thalitest/u0a642 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3530):   Force finishing activity ActivityRecord{21c7d8aa u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3530): mDVFSHelper.acquire()
,W/PackageSettings( 3530): Skipping PackageSetting{1a23b79c com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3530): Force stopping com.test.thalitest appid=10642 user=0: pkg removed
,E/JavaBinder( 3530): !!! FAILED BINDER TRANSACTION !!!
I/DBG_DM  ( 6314): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/PointerIcon( 3530): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3530): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3530): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
I/ActivityManager( 3530):   Force finishing activity ActivityRecord{21c7d8aa u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3530): Duplicate finish request for ActivityRecord{21c7d8aa u0 com.test.thalitest/.MainActivity t26 f}
,D/PointerIcon( 3530): setHoveringSpenCustomIcon IconType is same.1
,I/WindowState( 3530): WIN DEATH: Window{117380 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3530): Client connection lost with reason: 4
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6314): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 11
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6314): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/art     ( 4052): Explicit concurrent mark sweep GC freed 30913(1905KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.084ms total 75.963ms
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 6800): Explicit concurrent mark sweep GC freed 23120(1347KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.578ms total 85.356ms
,I/art     ( 9076): Explicit concurrent mark sweep GC freed 30854(1709KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.175ms total 58.720ms
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/SecContentProvider2( 3530): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3530): mCursor = null
,D/ApplicationPolicy( 3530): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 3530): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6314): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6314): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6314): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/InputReader( 3530): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 6314): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6314): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,E/SamsungIME( 4499): mOCRHelper is null
,W/GeofencerStateMachine( 4636): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 5358): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5358): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,E/Zygote  (12429): MountEmulatedStorage()
E/Zygote  (12429): v2
I/libpersona(12429): KNOX_SDCARD checking this for 10063
I/libpersona(12429): KNOX_SDCARD not a persona
,I/SELinux (12429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3530): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12429 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 3530): post active user change for 0
D/KnoxTimeoutHandler( 3530): postActiveUserChange for user 0
I/SELinux (12429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/DBG_DM  ( 6314): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,E/SELinux (12429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3530): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3530): Admin package name: com.google.android.gms
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3530): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3530): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3530): setMouseCustomIcon IconType is same.101
V/ActivityThread( 6314): updateVisibility : ActivityRecord{695483f token=android.os.BinderProxy@df86160 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/PointerIcon( 3530): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 867us total 24.030ms
D/PointerIcon( 3530): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 439us total 18.310ms
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 395us total 11.651ms
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 3530): Explicit concurrent mark sweep GC freed 54182(3MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 49MB/65MB, paused 2.073ms total 167.067ms
,D/TimaKeyStoreProvider(12429): TimaSignature is unavailable
,I/art     ( 3530): WaitForGcToComplete blocked for 165.512ms for cause Explicit
D/ResourcesManager( 3530): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ActivityThread(12429): Added TimaKeyStore provider
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/InputMethodManagerService( 3530): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/InputMethodManagerService( 3530): Got RemoteException sending setActive(false) notification to pid 11766 uid 10642
,W/ContextImpl( 3530): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(12429): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ActivityManager( 3530): mDVFSHelper.release()
I/Timeline( 3530): Timeline: Activity_windows_visible id: ActivityRecord{1bbce931 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:248756
,I/Timeline( 6314): Timeline: Activity_idle id: android.os.BinderProxy@df86160 time:248769
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12429): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12429): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12429): packagename:com.test.thalitest
,D/SecContentProvider2( 3530): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3530): mCursor = null
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 10:23:35 GMT+01:00 2016
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3530): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3530): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/RegisteredServicesCache( 3966): empty dynamic service
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onCreate()
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12006): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12006): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12006): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12006): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,E/Zygote  (12449): MountEmulatedStorage()
I/libpersona(12449): KNOX_SDCARD checking this for 10106
E/Zygote  (12449): v2
I/libpersona(12449): KNOX_SDCARD not a persona
I/SELinux (12449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3530): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12449 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManager(12084):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3530):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3530): queryAllProviders():  providerCallBack is not register for 0
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12449): TimaSignature is unavailable
,E/Zygote  (12464): MountEmulatedStorage()
D/ActivityThread(12449): Added TimaKeyStore provider
I/libpersona(12464): KNOX_SDCARD checking this for 10050
E/Zygote  (12464): v2
I/libpersona(12464): KNOX_SDCARD not a persona
,I/SELinux (12464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12464): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3530): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12464 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     ( 3530): Explicit concurrent mark sweep GC freed 6093(302KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.758ms total 205.271ms
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12449): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(12464): TimaSignature is unavailable
,D/PackageManager( 3530): delete codoeFile: 
I/KLMS-2.4.521: (12006): KLMSIntentService(): listeningToPackageRemoved().END
,D/ActivityThread(12464): Added TimaKeyStore provider
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/AASAUninstall( 3530):  com.test.thalitest not target!
,D/PackageManager( 3530): result of delete: 1{723333823}
,E/Zygote  (12480): MountEmulatedStorage()
E/Zygote  (12480): v2
I/libpersona(12480): KNOX_SDCARD checking this for 10101
I/libpersona(12480): KNOX_SDCARD not a persona
,I/SELinux (12480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3530): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12480 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12480): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(12418): Shutting down VM
,D/elm:14491(12449): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12449): ELMEngine.ELMEngine( context ).
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11498): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11498): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11498): Clear T&P info.
,D/elm:14491(12449): MDMBridge.setEnterpriseBridge()
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11498): Widget is not attached.
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(12480): TimaSignature is unavailable
,D/ActivityThread(12480): Added TimaKeyStore provider
,D/elm:14491(12449): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12449): ElmAgentService : onCreate()
,D/elm:14491(12449): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(12464): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/elm:14491(12449): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12449): MDMBridge.getInstance()
D/elm:14491(12449): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12449): MDMBridge.getAllLicenseInfoFromSDK()
,W/ResourcesManager(12464): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12464): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12464): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12464): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12464): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12464): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12464): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(12480): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 6800): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6800): Clearing selected account for com.test.thalitest
,E/Zygote  (12498): MountEmulatedStorage()
,E/Zygote  (12498): v2
I/libpersona(12498): KNOX_SDCARD checking this for 10019
I/libpersona(12498): KNOX_SDCARD not a persona
,I/SELinux (12498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12498 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/elm:14491(12449): ElmAgentService : onDestroy().
,I/ActivityManager( 3530): Killing 11464:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/gH_CompatibleDatabase( 6800): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 6800): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/LocationSettingsChecker( 6800): Removing dialog suppression flag for package com.test.thalitest
,D/TimaKeyStoreProvider(12498): TimaSignature is unavailable
D/gH_MetricsDatabase( 6800): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6800): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/ActivityThread(12498): Added TimaKeyStore provider
,D/gH_CompatibleDatabase( 6800): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6800): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6800): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/ResourceType( 3530): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/gH_CompatibleDatabase( 6800): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6800): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/gH_CompatibleDatabase( 6800): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/gH_CompatibleDatabase( 6800): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6800): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 6800): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/DocsApplication(12480): Installing DEX configuration.
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3530): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3530): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3530): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ChimeraCfgMgr( 6800): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6800): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(12498): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/DexInstaller(12480): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/ResourcesManager( 3530): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/PackageInfoHelper(12480): Provided clientMode=RELEASE, packageInfo=PackageInfo{cf63f96 com.google.android.apps.docs}
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ChimeraCfgMgr( 6800): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6800): Module APK com.google.android.play.games already loaded
,D/TAG     (12480): onCreate()
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/CrossAppStateProvider(12480): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/PackageManager( 3530): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3530): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12498): onReceive()
W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/com.sec.android.service.health.upgrade.UninstallReceiver(12498): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/com.sec.android.service.health.upgrade.UninstallReceiver(12498): onReceive() : package name is not s health. Return !!!
D/ResourcesManager( 3530): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3530): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/NetworkScheduler.SchedulerReceiver( 4636): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4636): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/RCPManagerService( 3530): PackageReceiver onReceive()
,I/HarmonyEASService( 3530): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3530): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3530): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3530): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3530): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3530): uID is 10642
V/EnterpriseBillingPolicy( 3530): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3530): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3530): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3530): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3530): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3530): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3530): getBillingProfileForVpnEngine - end - null
,D/UsbSettingsManager( 3530): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3530): onPackageRemoved : com.test.thalitest
,I/ActivityManager( 3530): Killing 10881:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12523): MountEmulatedStorage()
E/Zygote  (12523): v2
I/libpersona(12523): KNOX_SDCARD checking this for 10022
I/libpersona(12523): KNOX_SDCARD not a persona
,I/SELinux (12523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3530): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12523 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/KnoxTimeoutHandler( 3530): handleActiveUserChange for user 0
,D/TaskPersister( 3530): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3530): removeObsoleteFile: deleting file=24_task.xml
,D/TimaKeyStoreProvider(12523): TimaSignature is unavailable
,D/ActivityThread(12523): Added TimaKeyStore provider
,W/System.err( 3530): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,W/System.err( 3530): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3530): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3530): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
W/System.err( 3530): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3530): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3530): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3530): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3530): 	at com.android.server.SystemServer.run(SystemServer.java:427)
W/System.err( 3530): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3530): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3530): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3530): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3530): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3530): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3530): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3530): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3530): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3530): 	... 12 more
,W/FileUtils( 6800): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/Icing   ( 6800): Failed to open Apps corpus file.
E/Icing   ( 6800): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 6800): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
D/NearbySource(12464): Nearby Source Create!
D/NearbyContext(12464): Nearby Context Create!
D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/PanelView( 3694): There is/are notification(s) 
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
,D/ResourcesManager(12523): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,E/ActivityThread(11869): Failed to find provider info for com.facebook.appmanager.installrecord
,W/ResourcesManager(12523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12523): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12464): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12464): Samsung link source created
,E/Icing   ( 6800): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 6800): Writing status failed
,I/art     ( 4636): Explicit concurrent mark sweep GC freed 69482(3MB) AllocSpace objects, 36(1536KB) LOS objects, 34% free, 30MB/46MB, paused 1.532ms total 73.148ms
E/Icing   ( 6800): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
I/Icing   ( 6800): doRemovePackageData com.test.thalitest
,D/UsbHostManager( 3530): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3530): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3530): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3530): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3530): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3530): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3530): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3530): displayNotification : [0ah,00h,01h]
,E/SQLiteLog(12464): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/UsbHostManager( 3530): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3530): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3530): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/UsbHostManager( 3530): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3530): displayNotification : [09h,00h,00h]
,I/LocationWidgetApplication(12523): onCreate() : start
,D/LocationWidgetApplication(12523): countryCode = POLAND
,E/SQLiteDatabase(12464): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12464): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12464): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12464): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12464): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12464): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12464): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12464): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12464): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12464): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12464): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12464): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12464): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12464): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12464): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12464): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12464): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12464): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12464): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12464): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12464): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12464): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12464): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12464): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12464): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12464): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12464): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12464): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12464): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12464): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12464): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12464): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12464): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12464): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12464): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12464): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12464): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12464): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12464): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12464): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12464): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12464): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
W/SQLiteOpenHelper(12464): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3530): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider(12464): getAllContactInfoList Start
D/WifiDisplayAdapter( 3530): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/LocationManagerService( 3530): getProviders()=[]
D/LocationManagerService( 3530): getProviders()=[passive]
D/LocationManagerService( 3530): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(12523): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12523): getLastUiLocationId() : mLastUiLocationId = -100
D/MtpClient(12464): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12464): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/SQLiteLog(12523): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/SQLiteDatabase(12523): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12523): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12523): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12523): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12523): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12523): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12523): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12523): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12523): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12523): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12523): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12523): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12523): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12523): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12523): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12523): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12523): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12523): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12523): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12523): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12523): Shutting down VM
,E/AndroidRuntime(12523): FATAL EXCEPTION: main
E/AndroidRuntime(12523): Process: com.sec.android.widgetapp.locationwidget, PID: 12523
E/AndroidRuntime(12523): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12523): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12523): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12523): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12523): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12523): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12523): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12523): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12523): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12523): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12523): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12523): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12523): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12523): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12523): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12523): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12523): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12523): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12523): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12523): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12523): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12523): 	... 9 more
E/SharedPreferencesImpl(12464): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/UsbHostManager( 3530): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3530): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/Zygote  (12555): MountEmulatedStorage()
E/Zygote  (12555): v2
I/libpersona(12555): KNOX_SDCARD checking this for 10052
I/libpersona(12555): KNOX_SDCARD not a persona
I/SELinux (12555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3530): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12555 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/EventHub( 3530): Removing device '/dev/input/event10' due to inotify event
I/SELinux (12555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12555): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 3530): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,I/EventHub( 3530): Removing device '/dev/input/event7' due to inotify event
,I/PCWCLIENTTRACE_PushUtil(11894): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11894): sales region : global
I/PCWCLIENTTRACE_PushUtil(11894): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11894): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/DropBoxManagerService( 3530): Can't write: system_app_crash
E/DropBoxManagerService( 3530): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3530): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3530): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3530): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3530): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3530): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3530): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3530): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3530): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3530): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3530): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3530): 	... 5 more
,I/Process (12523): Sending signal. PID: 12523 SIG: 9
,I/ActivityManager( 3530): Killing 12239:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12555): TimaSignature is unavailable
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(12555): Added TimaKeyStore provider
,I/EventHub( 3530): Removing device '/dev/input/event8' due to inotify event,
,E/Zygote  (12571): MountEmulatedStorage()
,E/Zygote  (12571): v2
I/libpersona(12571): KNOX_SDCARD checking this for 10035
I/libpersona(12571): KNOX_SDCARD not a persona
,I/SELinux (12571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3530): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12571 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux (12571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3530): Killing 8869:com.android.settings/1000 (adj 13): bgCount ##31
,E/SELinux (12571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3530): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager( 3530): Process com.sec.android.widgetapp.locationwidget (pid 12523)(adj 9) has died(205,1204)
,D/TimaKeyStoreProvider(12571): TimaSignature is unavailable
,D/ActivityThread(12571): Added TimaKeyStore provider
,D/ResourcesManager(12555): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12555): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12555): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12555): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12555): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12555): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12555): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3530): Removing device '/dev/input/event11' due to inotify event
,D/WifiService( 3530): Client connection lost with reason: 4
,D/ResourcesManager(12571): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/EventHub( 3530): Removing device '/dev/input/event12' due to inotify event
,D/ContactProvider(12464): getAllContactInfoList End
,I/syncContacts(12464): thread: 1723, sync time = 366
,D/Mms/MmsApp(12555): [start]    onCreate() consume time = 0.0
,I/FeatureConfig(12571): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/Mms/ArtClassLoader(12555): init before art
,D/Mms/ArtClassLoader(12555): init [DONE] art
,I/EventHub( 3530): Removing device '/dev/input/event13' due to inotify event
,D/Mms/TelephonyPermission(12555): start operation mode monitor
,D/ResourcesManager(12555): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/EventHub( 3530): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12571): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12571): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12571): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12571): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12571): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/Mms/TelephonyPermission(12555): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12555): isDefault true
,D/Mms/MmsApp(12555): onCreate() com.android.mms
W/ResourcesManager(12571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3530): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12571): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12571): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  (12589): MountEmulatedStorage()
E/Zygote  (12589): v2
I/libpersona(12589): KNOX_SDCARD checking this for 10036
I/libpersona(12589): KNOX_SDCARD not a persona
,I/SELinux (12589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3530): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12589 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux (12589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12589): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12571): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/Mms/MmsApp(12555): [start]    initCountryIso consume time = 158.373083
,D/CountryDetector( 3530): The first listener is added
,D/TimaKeyStoreProvider(12589): TimaSignature is unavailable
,D/ResourcesManager(12571): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ActivityThread(12589): Added TimaKeyStore provider
,D/Mms/MmsApp(12555): [end]    initCountryIso consume time = 22.374167
D/Mms/MmsConfig(12555): [start]    MmsConfig.init() consume time = 0.211375
W/ResourcesManager(12571): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/Mms/MmsConfig(12555): before partial update
,D/ResourcesManager(12571): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12571): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12571): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.

```
