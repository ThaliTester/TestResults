#### Test 56818254e6f5c3b_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3495): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3495): stay LED for fully charged
I/MotionRecognitionService( 3495): Plugged
I/MotionRecognitionService( 3495): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/SSRM:n  ( 3495): SIOP:: AP = 260, PST = 289, CUR = 49
V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5577): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11550): 
D/AndroidRuntime(11550): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11550): CheckJNI is OFF
D/AndroidRuntime(11550): readGMSProperty: start
D/AndroidRuntime(11550): readGMSProperty: already setted!!
D/AndroidRuntime(11550): readGMSProperty: end
D/AndroidRuntime(11550): addProductProperty: start
E/AffinityControl(11550): AffinityControl: registerfunction enter
D/AndroidRuntime(11550): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3495): inState():  stateMachine is null !!
I/PersonaManagerService( 3495): PersonaId don't exist
I/ActivityManager( 3495): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3495): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3495): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3495): mDVFSHelper.acquire()
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (11568): MountEmulatedStorage()
I/libpersona(11568): KNOX_SDCARD checking this for 10610
E/Zygote  (11568): v2
I/libpersona(11568): KNOX_SDCARD not a persona
I/SELinux (11568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3495): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11568 uid=10610 gids={50610, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11568): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11550): Shutting down VM
D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11568): TimaSignature is unavailable
D/ActivityThread(11568): Added TimaKeyStore provider
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11568): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6265): updateVisibility : ActivityRecord{27695e5a token=android.os.BinderProxy@16402cef {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory(11568): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11568): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11568): Loading: webviewchromium
,I/LibraryLoader(11568): Time to load native libraries: 7 ms (timestamps 5115-5122)
,I/LibraryLoader(11568): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11568): Binding Chromium to main looper Looper (main, tid 1) {1d412855}
,I/LibraryLoader(11568): Expected native library version number "",actual native library version number ""
,I/chromium(11568): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11568): Initializing chromium process, renderers=0
,W/art     (11568): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11568): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11568): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11568): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11568): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11568): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11568): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11568): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11568): CordovaWebView is running on device made by: samsung
,W/art     (11568): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11568): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 3495): Activity pause timeout for ActivityRecord{1cf7b9f5 u0 com.test.thalitest/.MainActivity t26}
,D/Activity(11568): performCreate Call secproduct feature valuefalse
D/Activity(11568): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11568): Render dirty regions requested: true
,D/ActivityManager( 3495): post active user change for 0
D/KnoxTimeoutHandler( 3495): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3495): handleActiveUserChange for user 0
,V/ActivityThread(11568): updateVisibility : ActivityRecord{3a9dd0c5 token=android.os.BinderProxy@42e8ce0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2851): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3495): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3495): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11568): Initialized EGL, version 1.4
,I/OpenGLRenderer(11568): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278775024 
,D/OpenGLRenderer(11568): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11568): Enabling debug mode 0
,D/mali_winsys(11568): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3495): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3495): mDVFSHelper.release()
I/Timeline( 3495): Timeline: Activity_windows_visible id: ActivityRecord{1cf7b9f5 u0 com.test.thalitest/.MainActivity t26} time:115544
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 50859(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 49MB/65MB, paused 3.679ms total 168.528ms
,W/IInputConnectionWrapper(11568): showStatusIcon on inactive InputConnection
,I/Timeline(11568): Timeline: Activity_idle id: android.os.BinderProxy@42e8ce0 time:115719
,I/chromium(11568): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11568): 
,D/JsMessageQueue(11568): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11568): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359522048
,I/chromium(11568): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11568): Initializing JXcore engine
W/jxcore-log(11568): JXcore engine is ready
,E/auditd  ( 4604): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3495): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3495): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11568): Starting JXcore engine
,W/jxcore-log(11568): Platform android
W/jxcore-log(11568): 
W/jxcore-log(11568): Process ARCH arm
W/jxcore-log(11568): 
,I/jxcore-log(11568): JXcore Cordova bridge is ready!
I/jxcore-log(11568): 
W/jxcore-log(11568): JXcore engine is started
,I/jxcore-log(11568): Toggling radios to true
I/jxcore-log(11568): 
,D/BluetoothAdapter(11568): enable()
,D/BluetoothAdapter(11568): enable(): BT is already enabled..!
,D/WifiService( 3495): New client listening to asynchronous messages
,I/WifiManager(11568): packageName : com.test.thalitest
,D/SecContentProvider( 3495): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3495): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3495): mCursor = null
,D/WifiService( 3495): setWifiEnabled: true pid=11568, uid=10610
E/WifiService( 3495): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3495): Permission Denial: getCurrentUser() from pid=11568, uid=10610 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3495): Failed getting userId using ActivityManagerNative
W/WifiService( 3495): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11568, uid=10610 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3495): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3495): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3495): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3495): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3495): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3495): name = wifi_on
I/WifiService( 3495): disconnect: pid=11568, uid=10610
,I/wpa_supplicant( 3835): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11568): Radios toggled
I/jxcore-log(11568): 
,I/jxcore-log(11568): My device name is: samsung-SM-N910C
I/jxcore-log(11568): 
,I/wpa_supplicant( 3835): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3835): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3495): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3835): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3835): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3835): Disconnected - do not scan
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3495): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3495): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3495): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3495): do suspend true
,D/WifiP2pService( 3495): InactiveState{ what=143375 }
,D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3495): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3495): updateNetworkInfo()
,D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3495): updateNetworkInfo()
D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
I/Hs20UtilService( 4110): Starting #8
I/Hs20UtilService( 4110): Message received 5007
E/WifiStateMachine( 3495): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3692): applyOpen
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3692): applyOpen
I/wpa_supplicant( 3835): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3835): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3835): First Scan Start
E/WifiStateMachine( 3495): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3495): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/wpa_supplicant( 3835): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3495): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3495): do suspend true
E/Zygote  (11653): MountEmulatedStorage()
E/Zygote  (11653): v2
I/libpersona(11653): KNOX_SDCARD checking this for 1000
I/libpersona(11653): KNOX_SDCARD not a persona
D/WifiP2pService( 3495): InactiveState{ what=143375 }
D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
I/SELinux (11653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11653): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.android.settings for broadcast com.android.settings/.nearby.MountReceiver: pid=11653 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3495): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3495): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
D/ConnectivityService( 3495): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3495): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 6860): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3495): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3495): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine( 3495): updateConfiguredNetworkExpiration - currTime: 1454085744643
D/WifiStateMachine( 3495): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3495): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3495): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3495): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3495): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3495): Not allowed due to - mEnabled false
D/Tethering( 3495): MasterInitialState.processMessage what=3
D/ConnectivityService( 3495): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/TimaKeyStoreProvider(11653): TimaSignature is unavailable
V/NetworkStats( 3495): updateIfacesLocked()
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): performPollLocked(flags=0x1)
,D/ActivityThread(11653): Added TimaKeyStore provider
D/NetworkStatsFactory( 3495): UpdateStatsForKnox
,D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
V/NetworkStats( 3495): performPollLocked() took 4ms
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,V/NetworkStats( 3495): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
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
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,D/ResourcesManager(11653): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(11653): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(11653): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11653): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(11653): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11653): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11653): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/MySettingsProvider(11653): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog(11653): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider(11653): onCreate():(mDB == null)? false:true  =true
,D/NearbySettings(11653): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(11653): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings(11653): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings(11653): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11653): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3495): New client listening to asynchronous messages
,I/NearbySettings(11653): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11653): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(11653): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 3495): Killing 10955:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/10955/oom_score_adj; errno=22
,I/SignOutReceiver(11267): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4110): Starting #9
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings(11653): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11653): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11653): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11653): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11653): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11267): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3495): updateDataUsageMap
I/ApplicationPolicy( 3495): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3495): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3495): No Active Data Connection
,I/DBG_DM  ( 6265): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6265): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11688): MountEmulatedStorage()
E/Zygote  (11688): v2
I/libpersona(11688): KNOX_SDCARD checking this for 1000
I/libpersona(11688): KNOX_SDCARD not a persona
,I/SELinux (11688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11688): TimaSignature is unavailable
,D/ActivityThread(11688): Added TimaKeyStore provider
,D/ResourcesManager(11688): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11688): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11688): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11688): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11688): sales region : global
I/PCWCLIENTTRACE_PushUtil(11688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11688): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11688): noConnectivity : true
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11704): MountEmulatedStorage()
E/Zygote  (11704): v2
I/libpersona(11704): KNOX_SDCARD checking this for 10135
I/libpersona(11704): KNOX_SDCARD not a persona
,I/SELinux (11704): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11704): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11704): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11704 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 10254:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11704): TimaSignature is unavailable
,D/ActivityThread(11704): Added TimaKeyStore provider
,D/ResourcesManager(11704): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11704): Database version: 104
,D/ResourcesManager(11704): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11704): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11704): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11704): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@555d959: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11704): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11704): GMSCore installation verified
,I/ConfigStore(11704): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11704): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11704): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11704): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3495): getStreamVolume 3 index 0
,I/MediaRouter(11704): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11729): MountEmulatedStorage()
E/Zygote  (11729): v2
I/libpersona(11729): KNOX_SDCARD checking this for 10002
I/libpersona(11729): KNOX_SDCARD not a persona
,I/SELinux (11729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11729 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11704): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11729): TimaSignature is unavailable
I/ActivityManager( 3495): Killing 10939:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
D/ActivityThread(11729): Added TimaKeyStore provider
,D/ResourcesManager(11729): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3495): Killing 9832:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/lowmemorykiller( 2828): Error writing /proc/9832/oom_score_adj; errno=22
,E/Zygote  (11749): MountEmulatedStorage()
I/libpersona(11749): KNOX_SDCARD checking this for 1000
E/Zygote  (11749): v2
I/libpersona(11749): KNOX_SDCARD not a persona
,I/SELinux (11749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11749): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11749 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11749): TimaSignature is unavailable
,D/ActivityThread(11749): Added TimaKeyStore provider
,D/ResourcesManager(11749): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11749): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11749): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11749): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11749): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11749): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 3835): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3835): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3835): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3835): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3495): [1,454,085,745,700 ms] noteScanEnd no scan source
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3495): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1c276288 sup_state=SCANNING debouncing=false
,E/Zygote  (11765): MountEmulatedStorage()
I/libpersona(11765): KNOX_SDCARD checking this for 10012
E/Zygote  (11765): v2
I/libpersona(11765): KNOX_SDCARD not a persona
I/SELinux (11765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11765): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11765 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3495): setDetailed state send new extra info
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,D/TimaKeyStoreProvider(11765): TimaSignature is unavailable
,D/ActivityThread(11765): Added TimaKeyStore provider
,D/ResourcesManager(11765): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3495): Killing 10976:com.policydm/1000 (adj 15): bgCount ##31
,I/FOTA_Client(11765): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11765): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 3835): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3495): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3835): Associated with C0.AA.48
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,I/FOTA_Client(11765): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3835): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,E/Zygote  (11781): MountEmulatedStorage()
I/libpersona(11781): KNOX_SDCARD checking this for 10021
E/Zygote  (11781): v2
I/libpersona(11781): KNOX_SDCARD not a persona
I/SELinux (11781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/wpa_supplicant( 3835): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/SELinux (11781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 3835): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager( 3495): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11781 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3835): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3835): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3835): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3835): Blacklist: Clear (temp) 
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager( 3495): Killing 10991:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/lowmemorykiller( 2828): Error writing /proc/10991/oom_score_adj; errno=22
,E/WifiStateMachine( 3495): Network connection established
,D/WifiNative-HAL( 3495): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3495): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3495): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3495): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3495): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3495): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3495): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3495): updateNetworkInfo()
,D/TimaKeyStoreProvider(11781): TimaSignature is unavailable
,D/ActivityThread(11781): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3495): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3495): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3495): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(11781): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/CommandListener( 2846): Setting iface cfg
E/WifiStateMachine( 3495): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/KLMS-2.4.521: (11781): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 17:42:25 GMT+01:00 2016
,I/KLMS-2.4.521: (11781): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11781): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11781): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11781): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11781): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11781): StateImplV2(): networkChangeListener().END
,E/Zygote  (11798): MountEmulatedStorage()
I/libpersona(11798): KNOX_SDCARD checking this for 10038
E/Zygote  (11798): v2
I/libpersona(11798): KNOX_SDCARD not a persona
I/SELinux (11798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11798): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11798 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onDestroy()
,I/art     ( 2885): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 518us total 11.273ms
,I/ActivityManager( 3495): Killing 10861:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11798): TimaSignature is unavailable
,D/ActivityThread(11798): Added TimaKeyStore provider
,I/art     ( 2885): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 256us total 8.378ms
,D/ResourcesManager(11798): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/art     ( 2885): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 468us total 9.268ms
,I/SO_AGENT(11798): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11813): MountEmulatedStorage()
I/libpersona(11813): KNOX_SDCARD checking this for 1000
E/Zygote  (11813): v2
I/libpersona(11813): KNOX_SDCARD not a persona
I/SELinux (11813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11813 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11006:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3495): do suspend false
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,D/WifiP2pService( 3495): InactiveState{ what=143375 }
,D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
D/TimaKeyStoreProvider(11813): TimaSignature is unavailable
,D/ActivityThread(11813): Added TimaKeyStore provider
,D/ResourcesManager(11813): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/SPPClientService(11052): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      (11131): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11131): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      (11131): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11131): [SLFUCHKMGR] constructor called
,E/SPPClientService(11052): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11131): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11131): [OR] == isSIMCardReady false ==
,I/SA      (11131): [SCU] == networkStateCheck == false
I/SA      (11131): [OR] onReceive END
,I/ActivityManager( 3495): Killing 11088:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,V/DownloadManager( 5696): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11836): MountEmulatedStorage()
E/Zygote  (11836): v2
,I/libpersona(11836): KNOX_SDCARD checking this for 10067
I/libpersona(11836): KNOX_SDCARD not a persona
I/SELinux (11836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11836 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11836): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11836): TimaSignature is unavailable
,D/ActivityThread(11836): Added TimaKeyStore provider
,D/ResourcesManager(11836): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11836): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11836): Other Intent
,I/ActivityManager( 3495): Killing 11028:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5441): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5441): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5441): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5441): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5441): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5441): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5441): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11852): MountEmulatedStorage()
I/libpersona(11852): KNOX_SDCARD checking this for 1000
E/Zygote  (11852): v2
I/libpersona(11852): KNOX_SDCARD not a persona
,I/SELinux (11852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11852): TimaSignature is unavailable
,D/ActivityThread(11852): Added TimaKeyStore provider
,D/ResourcesManager(11852): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11852): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(11852): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11852): premStatus:2
,I/KnoxUsageLogPro(11852): isEulaShown : false
I/KnoxUsageLogPro(11852): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  (11867): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11867): version 5.5.6 starting
,E/dhcpcd  (11867): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  (11870): MountEmulatedStorage()
E/Zygote  (11870): v2
I/libpersona(11870): KNOX_SDCARD checking this for 10090
I/libpersona(11870): KNOX_SDCARD not a persona
,I/SELinux (11870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11870): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=11870 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11074:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11870): TimaSignature is unavailable
,D/ActivityThread(11870): Added TimaKeyStore provider
,I/dhcpcd  (11867): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11867): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11867): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11867): bssid match
,I/dhcpcd  (11867): wlan0: rebinding lease of 192.168.1.124
,D/ResourcesManager(11870): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11890): MountEmulatedStorage()
I/libpersona(11890): KNOX_SDCARD checking this for 10127
E/Zygote  (11890): v2
I/libpersona(11890): KNOX_SDCARD not a persona
I/SELinux (11890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11890 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11165:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11890): TimaSignature is unavailable
,D/ActivityThread(11890): Added TimaKeyStore provider
,D/ResourcesManager(11890): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(11890): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11890): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11890): stopCheckCategoryVersion
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11906): MountEmulatedStorage()
E/Zygote  (11906): v2
I/libpersona(11906): KNOX_SDCARD checking this for 10136
I/libpersona(11906): KNOX_SDCARD not a persona
,I/SELinux (11906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11906): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11906 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11149:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11906): TimaSignature is unavailable
,D/ActivityThread(11906): Added TimaKeyStore provider
,D/ResourcesManager(11906): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11906): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(11906): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11906): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11906): Loading: webviewchromium
,I/LibraryLoader(11906): Time to load native libraries: 3 ms (timestamps 9000-9003)
I/LibraryLoader(11906): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11906): Binding Chromium to main looper Looper (main, tid 1) {1e01b215}
,I/LibraryLoader(11906): Expected native library version number "",actual native library version number ""
I/chromium(11906): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11906): Initializing chromium process, renderers=0
,W/art     (11906): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11906): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(11906): Requires BLUETOOTH permission
I/chromium(11906): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11906): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11906): Starting up...
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11974): MountEmulatedStorage()
I/libpersona(11974): KNOX_SDCARD checking this for 10150
E/Zygote  (11974): v2
I/libpersona(11974): KNOX_SDCARD not a persona
,I/SELinux (11974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=11974 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11202:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11974): TimaSignature is unavailable
,D/ActivityThread(11974): Added TimaKeyStore provider
,D/ResourcesManager(11974): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(11974): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11974): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11974): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(11974): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11974): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(11974): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11989): MountEmulatedStorage()
I/libpersona(11989): KNOX_SDCARD checking this for 10178
E/Zygote  (11989): v2
I/libpersona(11989): KNOX_SDCARD not a persona
,I/SELinux (11989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11989): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=11989 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11217:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11989): TimaSignature is unavailable
,D/ActivityThread(11989): Added TimaKeyStore provider
,D/ResourcesManager(11989): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(11989): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(11989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11989): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11989): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11989): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(11989): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,E/Zygote  (12012): MountEmulatedStorage()
I/libpersona(12012): KNOX_SDCARD checking this for 10082
E/Zygote  (12012): v2
I/libpersona(12012): KNOX_SDCARD not a persona
,I/SELinux (12012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12012): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12012 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12012): TimaSignature is unavailable
,D/ActivityThread(12012): Added TimaKeyStore provider
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12012): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12012): onCreate
D/BadgeProvider(12012): DatabaseHelper
,E/Zygote  (12028): MountEmulatedStorage()
I/libpersona(12028): KNOX_SDCARD checking this for 1000
E/Zygote  (12028): v2
I/libpersona(12028): KNOX_SDCARD not a persona
,I/SELinux (12028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11285:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3495): Killing 11233:com.samsung.helphub/1000 (adj 13): bgCount ##32
,D/BadgeProvider(12012): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider(12028): TimaSignature is unavailable
,D/ActivityThread(12028): Added TimaKeyStore provider
,D/BadgeProvider(12012): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12012): sendNotify, [notify] : null
D/BadgeProvider(12012): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12012): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12012): update, [UpdateCount] : 1
,D/Launcher.Model( 3999): reloadBadges entered.
,D/ResourcesManager(12028): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/ActivityManager( 3495): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3495): Killing 11302:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/iu.Environment( 6860): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6860): num queued entries: 0
,I/iu.UploadsManager( 6860): num updated entries: 0
I/iu.SyncManager( 6860): NEXT; no task
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12046): MountEmulatedStorage()
E/Zygote  (12046): v2
I/libpersona(12046): KNOX_SDCARD checking this for 10013
I/libpersona(12046): KNOX_SDCARD not a persona
,I/SELinux (12046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12046 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12046): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     ( 2885): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 280us total 10.870ms
,D/TimaKeyStoreProvider(12046): TimaSignature is unavailable
,D/ActivityThread(12046): Added TimaKeyStore provider
,I/art     ( 2885): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 371us total 8.507ms
,D/ResourcesManager(12046): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
I/art     ( 2885): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 271us total 8.491ms
,I/ActivityManager( 3495): Killing 11320:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4110): Starting #10
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings(11653): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11653): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11653): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11653): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11653): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11267): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (11867): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11867): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11568): 
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3495): do suspend true
,D/WifiP2pService( 3495): InactiveState{ what=143375 }
,D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3495): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3495): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3495): Not connected state, yet.
E/WifiStateMachine( 3495): VerifyingLinkState enter
,D/WifiStateMachine( 3495): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3495): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3495): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3495): callSECApiInt - ID [210]
E/WifiStateMachine( 3495): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3495): updateNetworkInfo()
,D/ConnectivityService( 3495): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3495): Adding iface wlan0 to network 503
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine( 3495): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4110): Starting #11
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings(11653): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 3495): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3495): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/NearbySettings(11653): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3495): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3495): Unexpected mtu value: 0, wlan0
V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3495): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3495): Now, connected state.
E/WifiStateMachine( 3495): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3495): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3495): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3495): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3495): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3495): REQUEST_POWER_SAVE_ON
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/SignOutReceiver(11267): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/Hs20UtilService( 4110): Starting #12
,I/Hs20UtilService( 4110): Message received 5007
,D/NearbySettings(11653): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11653): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/        ( 2846): QcRouteController
,I/NearbySettings(11653): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11653): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11653): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11653): MountReceiver.mPrefHandler - 7002
V/        ( 2846): QcRouteController
,I/SignOutReceiver(11267): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
,D/ConnectivityService( 3495): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3495): LTETest block dns file not exists
I/Hs20UtilService( 4110): Starting #13
D/ConnectivityService( 3495): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3495): updateNetworkInfo()
D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3495): updateNetworkInfo()
D/ConnectivityService( 3495): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3495): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Connected
I/Hs20UtilService( 4110): Message received 5007
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3495):    accepting network in place of null
D/TelephonyNetworkFactory( 3982): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NearbySettings(11653): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings(11653): MountReceiver.onReceive - Keep current state
,E/CSLegacyTypeTracker( 3495): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3495): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,I/System.out( 3495): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3495): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3495): MasterInitialState.processMessage what=3
D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
,D/ConnectivityService( 3495): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
V/NetworkStats( 3495): updateIfacesLocked()
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3495): UpdateStatsForKnox
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 6860): CM callback handler got msg 524290
V/NetworkStats( 3495): performPollLocked() took 3ms
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
I/WifiStateMachine( 3495): callSECApi what=220
D/WifiStateMachine( 3495): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
I/SignOutReceiver(11267): NETWORK_STATE_CHANGED_ACTION
I/SurfaceFlinger( 2851): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3495): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3495
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11568): 
,I/System.out( 3495): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11568): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 16:42:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454085747988], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454085747972]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Validated
,D/ConnectivityService( 3495): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3495): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3495): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3495): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6860): CM callback handler got msg 524290
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
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11568): 
,D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3495): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3495): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
,D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3495): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6265): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6265): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5216): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5216): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11704): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11688): sales region : global
I/PCWCLIENTTRACE_PushUtil(11688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11688): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 68229(3MB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 49MB/65MB, paused 1.206ms total 77.960ms
,D/SecContentProvider2( 3495): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3495): mCursor = null
,I/DIAGMON_AGENT(11749): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11749): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11765): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11765): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11765): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11781): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 17:42:28 GMT+01:00 2016
,I/KLMS-2.4.521: (11781): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11781): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11781): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(11798): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11781): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11781): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11781): StateImplV2(): networkChangeListener().START
I/KLMS-2.4.521: (11781): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11781): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11781): StateImplV2(): networkChangeListener().END
E/SPPClientService(11052): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onDestroy()
,I/SA      (11131): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11131): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11131): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11131): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11131): [OR] == isSIMCardReady false ==
,I/SA      (11131): [SCU] == networkStateCheck == true
I/SA      (11131): [DM] getCountryCodeFromCSC : PL
I/SA      (11131): isChinaCountryCode : false
I/SA      (11131): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11131): [OR] == networkStateCheck true ==
I/SA      (11131): [OR] GetMyCountryZoneTask
,I/SA      (11131): [OR] onReceive END
I/SA      (11131): [SRS] prepareGetMyCountryZone
,I/SA      (11131): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11131): [SSP] query invoked
,V/DownloadManager( 5696): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11131): [TPMU] GetMccFromDB : null
I/SA      (11131): [SCU] getMccFromPreferece mcc = 260
I/SA      (11131): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(11836): Other Intent
,D/accuweather( 5441): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5441): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5441): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5441): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5441): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5441): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5441): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(11852): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(11852): premStatus:2
,I/KnoxUsageLogPro(11852): isEulaShown : false
I/KnoxUsageLogPro(11852): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(11890): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11890): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11890): stopCheckCategoryVersion
,D/QuickConnect(11974): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(11974): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(11974): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,I/iu.Environment( 6860): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6860): num queued entries: 0
I/iu.UploadsManager( 6860): num updated entries: 0
,I/iu.SyncManager( 6860): NEXT; no task
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10014
,D/WaitQueueForNetworkActivate(12046): notifyNetworkActivated
,W/ContextImpl(12046): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3495): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12046): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12046): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12046): exit::IDLE
D/InitializeManagerStateMachine(12046): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12046): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12046): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12046): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12046): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12046): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12046): entry::SUCCESS
D/hcjo    (12046): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12046): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12046): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12046): exit::SUCCESS
D/InitializeManagerStateMachine(12046): entry::IDLE
,I/SA      (11131): [RC New] Execute method=[GET] start
,I/SA      (11131): [RC New] Security=[true]
,I/System.out(11131): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11131): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11131): Thread-1540(ApacheHTTPLog):isShipBuild true
I/System.out(11131): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3495): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11131): [RC New] [v2liruge] api execute + 595
I/SA      (11131): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11131): AsyncTask #1 calls detatch()
,I/SA      (11131): [TPMU] getNetworkMcc : 
,I/SA      (11131): [SCU] saveMccToPreferece Start
I/SA      (11131): [SCU] RegionMCC : 260
I/SA      (11131): [SSP] query invoked
,I/SA      (11131): [TPMU] GetMccFromDB : null
I/SA      (11131): [SCU] getMccFromPreferece mcc = 260
I/SA      (11131): [SCU] saveMccToPreferece End
,I/SA      (11131): [RC New] executeRequest [v2liruge] end. 615
I/SA      (11131): [RC New] Execute end
I/SA      (11131): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11131): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3495): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
,D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3495): route cmd failed: 
W/NetworkManagementService( 3495): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3495): '
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3495): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3495): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3495): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3495): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3495): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityService( 3495): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6860): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6860): CM callback handler got msg 524295
,I/dhcpcd  (11867): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4628): callingUid 10014, callindPid: 4628
,D/ResourcesManager(11704): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11704): Using the GMSCore's GoogleHttpClient
,D/WearableClient(11704): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(11704): Conditions not met for autocaching.
I/MusicLeanback(11704): Stop autocaching.
,D/WearableClient(11704): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11704): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11704): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11704): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils(11704): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11704): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@163482db that was originally bound here
E/ActivityThread(11704): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@163482db that was originally bound here
E/ActivityThread(11704): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11704): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11704): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11704): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11704): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11704): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11704): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11704): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11704): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11704): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11704): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11704): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11704): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11704): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11704): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11704): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11704): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11704): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11704): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11704): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11704): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11704): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11704): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11704): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11704): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3495): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3495): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log(11568): Test app app.js loaded
I/jxcore-log(11568): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11568): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11568): BLE advertisement is supported
I/jxcore-log(11568): 
,I/chromium(11568): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV4    (11906): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger( 2851): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2851): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3495): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3495) eventTime = 123943
,D/PowerManagerService( 3495): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3495 (0x0)
D/PowerManagerService( 3495): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3495, ws=WorkSource{10060}) (elapsedTime=3494)
,V/AlarmManager( 3495): waitForAlarm result :4
,D/SSRM:n  ( 3495): SIOP:: AP = 300, PST = 286, CUR = -237
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3495): online:4, current avg:-237, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:124
D/BatteryService( 3495): stay LED for fully charged
D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3495): [PWL] Off : 30s ago
,D/PackageManager( 3495): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11688): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11688): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11688): ================================================
,I/CSTORAGE(11688):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11688): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11688): [GetString-S]
E/art     (11688): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11688): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11688): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11688): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11688): sales region : global
I/PCWCLIENTTRACE_PushUtil(11688): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11688): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11867): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/dhcpcd  (11867): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11867): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12046): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12046): exit::IDLE
D/PreloadUpdateManagerStateMachine(12046): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12046): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12046): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine(12046): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12046): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12046): entry::IDLE
,E/Watchdog( 3495): !@Sync 4
,D/SSRM:n  ( 3495): SIOP:: AP = 280, PST = 279, CUR = -237
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:-33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:92
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3495): stay LED for fully charged
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3495): SIOP:: AP = 260, PST = 277, CUR = -33
,I/PowerManagerService( 3495): [PWL] Off : 50s ago
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3495): stay LED for fully charged
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3495): waitForAlarm result :8
,D/SSRM:n  ( 3495): SIOP:: AP = 260, PST = 272, CUR = 38
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/BatteryService( 3495): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3495): Skipping unknown process pid 12251
,E/Watchdog( 3495): !@Sync 5
,D/SSRM:n  ( 3495): SIOP:: AP = 260, PST = 271, CUR = 56
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3495): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3495): [PWL] Off : 75s ago
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 270, CUR = 62
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3495): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3495): stay LED for fully charged
,I/MotionRecognitionService( 3495): Plugged
I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4628): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 268, CUR = 60
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3495): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3495): stay LED for fully charged
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3495): !@Sync 6
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 265, CUR = 55
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3495): stay LED for fully charged
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3495): [PWL] Off : 105s ago
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 264, CUR = 55
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3495): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
D/BatteryService( 3495): stay LED for fully charged
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3495): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3495): waitForAlarm result :8
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 263, CUR = 50,
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
,D/BatteryService( 3495): stay LED for fully charged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3495): !@Sync 7
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 261, CUR = 46
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/BatteryService( 3495): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3495): [PWL] Off : 140s ago
,D/SSRM:n  ( 3495): SIOP:: AP = 250, PST = 258, CUR = 44
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3495): Plugged
,I/MotionRecognitionService( 3495): setPowerConnected  = true
,D/BatteryService( 3495): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5577): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5577): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11568): --= Surplus to requirements =--
I/jxcore-log(11568): 
I/jxcore-log(11568): ****TEST TOOK:  ms ****
I/jxcore-log(11568): 
I/jxcore-log(11568): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11568): 
,D/AndroidRuntime(12341): 
D/AndroidRuntime(12341): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12341): CheckJNI is OFF
,D/AndroidRuntime(12341): readGMSProperty: start
D/AndroidRuntime(12341): readGMSProperty: already setted!!
D/AndroidRuntime(12341): readGMSProperty: end
D/AndroidRuntime(12341): addProductProperty: start
,E/AffinityControl(12341): AffinityControl: registerfunction enter
,D/AndroidRuntime(12341): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3495): START PACKAGE DELETE: observer{234028306}
D/PackageManager( 3495): pkg{<packageName>}
D/PackageManager( 3495): user{0}
D/PackageManager( 3495): caller{2000}
D/PackageManager( 3495): flags{3}
D/PersonaManagerService( 3495): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3495): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3495): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3495): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3495): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 3495): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3495): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3495): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3495): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3495): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3495): !@killApplicatoin: 10610, uninstall pkg
I/ActivityManager( 3495): Force stopping com.test.thalitest appid=10610 user=-1: uninstall pkg
,I/ActivityManager( 3495): Killing 11568:com.test.thalitest/u0a610 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3495):   Force finishing activity ActivityRecord{1cf7b9f5 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3495): mDVFSHelper.acquire()
,W/PackageSettings( 3495): Skipping PackageSetting{3f31fc0c com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3495): Force stopping com.test.thalitest appid=10610 user=0: pkg removed
,I/ActivityManager( 3495):   Force finishing activity ActivityRecord{1cf7b9f5 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3495): Duplicate finish request for ActivityRecord{1cf7b9f5 u0 com.test.thalitest/.MainActivity t26 f}
,D/WifiService( 3495): Client connection lost with reason: 4
,I/WindowState( 3495): WIN DEATH: Window{3e891d63 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 2851): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2851): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2851): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/art     ( 8938): Explicit concurrent mark sweep GC freed 29254(1641KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.710ms total 49.219ms
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 6860): Explicit concurrent mark sweep GC freed 27858(1580KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.494ms total 75.958ms
,I/art     ( 4049): Explicit concurrent mark sweep GC freed 33132(2032KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.326ms total 46.703ms
I/InputReader( 3495): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/SamsungIME( 4466): mOCRHelper is null
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,W/GeofencerStateMachine( 4628): Ignoring removeGeofence because network location is disabled.
,D/LWLocationManager(11340): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(11340): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12359): MountEmulatedStorage()
E/Zygote  (12359): v2
I/libpersona(12359): KNOX_SDCARD checking this for 10063
I/libpersona(12359): KNOX_SDCARD not a persona
,I/SELinux (12359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3495): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12359 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 5216): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5216): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/EnterpriseDeviceManagerService( 3495): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3495): Admin package name: com.google.android.gms
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager( 3495): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SecContentProvider2( 3495): uri = 14 selection = getSealedState
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3495): mCursor = null
,D/ApplicationPolicy( 3495): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3495): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/TimaKeyStoreProvider(12359): TimaSignature is unavailable
,D/ActivityThread(12359): Added TimaKeyStore provider
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 40686(3MB) AllocSpace objects, 43(688KB) LOS objects, 24% free, 49MB/65MB, paused 2.603ms total 155.605ms
,I/art     ( 3495): WaitForGcToComplete blocked for 155.866ms for cause Explicit
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6265): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6265): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6265): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3495): post active user change for 0
,D/KnoxTimeoutHandler( 3495): postActiveUserChange for user 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SurfaceFlinger( 2851): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3495): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
V/ActivityThread( 6265): updateVisibility : ActivityRecord{27695e5a token=android.os.BinderProxy@16402cef {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
,D/PackageManager( 3495): delete codoeFile: 
,I/AASAUninstall( 3495):  com.test.thalitest not target!
,D/PackageManager( 3495): result of delete: 1{234028306}
,D/AndroidRuntime(12341): Shutting down VM
,D/StatusBarManagerService( 3495): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(12359): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/VRSetupWizardStub/PackageIntentReceiver(12359): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12359): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12359): packagename:com.test.thalitest
,D/SecContentProvider2( 3495): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3495): mCursor = null
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11781): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 29 17:44:25 GMT+01:00 2016
,D/RegisteredServicesCache( 3967): empty dynamic service
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (11781): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3495): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3495): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11781): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (11781): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/InputMethodManagerService( 3495): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,E/Zygote  (12377): MountEmulatedStorage()
E/Zygote  (12377): v2
I/libpersona(12377): KNOX_SDCARD checking this for 10106
I/libpersona(12377): KNOX_SDCARD not a persona
,I/SELinux (12377): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12377): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12377 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12377): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11781): KLMSIntentService(): PACKAGE_REMOVED
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 3495): Got RemoteException sending setActive(false) notification to pid 11568 uid 10610
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (11781): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11781): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/Timeline( 6265): Timeline: Activity_idle id: android.os.BinderProxy@16402cef time:237791
,W/ActivityManager( 3495): mDVFSHelper.release()
I/Timeline( 3495): Timeline: Activity_windows_visible id: ActivityRecord{3a2e4739 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:237796
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 6303(297KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 5.097ms total 174.328ms
,D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/RCPManager(11852):  in createShortcut() for packageName: com.test.thalitest userId0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3495):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3495): queryAllProviders():  providerCallBack is not register for 0
D/TimaKeyStoreProvider(12377): TimaSignature is unavailable
,D/ActivityThread(12377): Added TimaKeyStore provider
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11340): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  (12395): MountEmulatedStorage()
,E/Zygote  (12395): v2
I/libpersona(12395): KNOX_SDCARD checking this for 10050
I/libpersona(12395): KNOX_SDCARD not a persona
,I/SELinux (12395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourceType( 3495): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SELinux (12395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12395 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(11340): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11340): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11340): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11340): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/ResourcesManager(11340): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager( 3495): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3495): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3495): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3495): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/TimaKeyStoreProvider(12395): TimaSignature is unavailable
,D/ActivityThread(12395): Added TimaKeyStore provider
,D/ResourcesManager(12377): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,E/Zygote  (12410): MountEmulatedStorage()
I/libpersona(12410): KNOX_SDCARD checking this for 10183
E/Zygote  (12410): v2
I/libpersona(12410): KNOX_SDCARD not a persona
,I/SELinux (12410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12410 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
E/SELinux (12410): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.521: (11781): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:14491(12377): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12377): ELMEngine.ELMEngine( context ).
D/elm:14491(12377): MDMBridge.setEnterpriseBridge()
,D/TimaKeyStoreProvider(12410): TimaSignature is unavailable
,D/ActivityThread(12410): Added TimaKeyStore provider
,D/elm:14491(12377): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/elm:14491(12377): ElmAgentService : onCreate()
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/elm:14491(12377): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12395): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager(11340): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14491(12377): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12377): MDMBridge.getInstance()
D/elm:14491(12377): MDMBridge.getAllLicenseInfoFromSDK()
,W/ResourcesManager(12395): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12395): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12395): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12395): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12395): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12395): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/elm:14491(12377): MDMBridge.getAllLicenseInfoFromSDK()
,W/ResourcesManager(12395): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12395): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12427): MountEmulatedStorage()
E/Zygote  (12427): v2
I/libpersona(12427): KNOX_SDCARD checking this for 10101
I/libpersona(12427): KNOX_SDCARD not a persona
,I/SELinux (12427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3495): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12427 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12427): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11781): KLMSIntentService(): onDestroy()
,D/elm:14491(12377): ElmAgentService : onDestroy().
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11340): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11340): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/libpersona(12439): KNOX_SDCARD checking this for 10019
E/Zygote  (12439): MountEmulatedStorage()
I/libpersona(12439): KNOX_SDCARD not a persona
E/Zygote  (12439): v2
I/SELinux (12439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12439 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(12410): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/TimaKeyStoreProvider(12427): TimaSignature is unavailable
,D/ActivityThread(12427): Added TimaKeyStore provider
,D/ResourcesManager(11340): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/SQLiteLog(12410): (284) automatic index on shooting_modes(title_id)
,D/TimaKeyStoreProvider(12439): TimaSignature is unavailable
,I/ActivityManager( 3495): Killing 11357:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
D/ActivityThread(12439): Added TimaKeyStore provider
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/ActivityManager( 3495): Killing 11372:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/SQLiteLog(12395): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,D/ResourcesManager(12427): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/SQLiteDatabase(12395): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12395): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12395): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12395): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12395): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12395): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12395): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(12439): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
E/SharedPreferencesImpl(12395): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/PackageManager( 3495): findPreferredActivity: No PreferredActivities set
E/Zygote  (12462): MountEmulatedStorage()
E/Zygote  (12462): v2
I/libpersona(12462): KNOX_SDCARD checking this for 10190
D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
I/libpersona(12462): KNOX_SDCARD not a persona
I/SELinux (12462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3495): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12462 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11340): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
I/ActivityManager( 3495): Killing 11340:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12439): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12439): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12439): onReceive() : package name is not s health. Return !!!
,I/ActivityManager( 3495): Killing 10798:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3495): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/UsbHostManager( 3495): displayNotification : [0ah,00h,00h]
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3495): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3495): displayNotification : [0ah,00h,01h]
D/TimaKeyStoreProvider(12462): TimaSignature is unavailable
D/ActivityThread(12462): Added TimaKeyStore provider
,D/UsbHostManager( 3495): usbDeviceRemoved : /dev/bus/usb/001/003
D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
,D/UsbHostManager( 3495): displayNotification : [09h,00h,00h]
E/UsbHostManager( 3495): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3495): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Books/Books.apk
,D/DocsApplication(12427): Installing DEX configuration.
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/DexInstaller(12427): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12427): Provided clientMode=RELEASE, packageInfo=PackageInfo{1e256312 com.google.android.apps.docs}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/TAG     (12427): onCreate()
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/CrossAppStateProvider(12427): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/NearbySource(12395): Nearby Source Create!
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/UsbHostManager( 3495): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3495): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/NearbyContext(12395): Nearby Context Create!
,D/ResourcesManager(12462): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/UsbSettingsManager( 3495): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3495): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/PCWCLIENTTRACE_PushUtil(11688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11688): sales region : global
I/PCWCLIENTTRACE_PushUtil(11688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11688): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12462): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12462): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/EventHub( 3495): Removing device '/dev/input/event10' due to inotify event
,I/TapandpayWidget:Utils(12462): Clear T&P info.
,D/RCPManagerService( 3495): PackageReceiver onReceive()
I/HarmonyEASService( 3495): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3495): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/TapandpayWidget:TanpandpayAppWidgetProvider(12462): Widget is not attached.
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3495): Removing device '/dev/input/event7' due to inotify event
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12395): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12395): Samsung link source created
,I/EventHub( 3495): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  (12485): MountEmulatedStorage()
E/Zygote  (12485): v2
I/libpersona(12485): KNOX_SDCARD checking this for 10035
I/libpersona(12485): KNOX_SDCARD not a persona
,I/SELinux (12485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12485 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (12485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3495): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager( 3495): Killing 10412:com.android.vending/u0a31 (adj 13): bgCount ##31
,E/SQLiteLog(12395): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3495): Removing device '/dev/input/event11' due to inotify event
,E/SQLiteDatabase(12395): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12395): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12395): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12395): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12395): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12395): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12395): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12395): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12395): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12395): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12395): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12395): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12395): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12395): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12395): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12395): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12395): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12395): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12395): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12395): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12395): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12395): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12395): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12395): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12395): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12395): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12395): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12395): Opened local.db in read-only mode
I/EventHub( 3495): Removing device '/dev/input/event12' due to inotify event
D/TimaKeyStoreProvider(12485): TimaSignature is unavailable
D/ActivityThread(12485): Added TimaKeyStore provider
D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/PackageBroadcastService( 6860): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6860): Clearing selected account for com.test.thalitest
D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/EventHub( 3495): Removing device '/dev/input/event13' due to inotify event
,D/ResourcesManager(12485): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/EventHub( 3495): Removing device '/dev/input/event14' due to inotify event
,E/SQLiteLog( 6860): (10) POSIX Error : 9 SQLite Error : 3850
,E/SharedPreferencesImpl(12395): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
E/SQLiteLog( 6860): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 6860): disk I/O error (code 3850)
E/DriveAsyncService( 6860): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6860): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6860): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6860): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6860): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6860): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6860): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6860): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6860): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6860): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6860): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6860): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6860): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6860): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6860): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6860): 	at java.lang.Thread.run(Thread.java:818)
,D/ContactProvider(12395): getAllContactInfoList Start
,I/LocationSettingsChecker( 6860): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 6860): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6860): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6860): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6860): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6860): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6860): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6860): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6860): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6860): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6860): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6860): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6860): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6860): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/FeatureConfig(12485): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,E/SQLiteOpenHelper( 6860): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6860): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6860): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6860): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6860): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6860): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6860): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6860): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6860): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6860): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6860): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6860): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6860): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6860): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 6860): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/ChimeraCfgMgr( 6860): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6860): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 6860): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6860): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 6860): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6860): Process: com.google.android.gms, PID: 6860
E/AndroidRuntime( 6860): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6860): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6860): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6860): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6860): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6860): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6860): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6860): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6860): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6860): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6860): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6860): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ResourcesManager(12485): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk,
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12485): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12485): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12485): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12485): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12485): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12485): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk

```
