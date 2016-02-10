#### Test 58752353dc32d9f_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3515): SIOP:: AP = 240, PST = 251, CUR = 66
--------- beginning of main
D/AndroidRuntime(11861): 
D/AndroidRuntime(11861): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11861): CheckJNI is OFF
D/AndroidRuntime(11861): readGMSProperty: start
D/AndroidRuntime(11861): readGMSProperty: already setted!!
D/AndroidRuntime(11861): readGMSProperty: end
D/AndroidRuntime(11861): addProductProperty: start
D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3515): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:72
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3515): stay LED for fully charged
I/MotionRecognitionService( 3515): Plugged
I/MotionRecognitionService( 3515): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
E/AffinityControl(11861): AffinityControl: registerfunction enter
V/HeadsetService( 5664): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5664): Disconnected process message: 10
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11861): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3515): inState():  stateMachine is null !!
I/PersonaManagerService( 3515): PersonaId don't exist
I/ActivityManager( 3515): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3515): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3515): mDVFSHelper.acquire()
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/Zygote  (11880): MountEmulatedStorage()
E/Zygote  (11880): v2
I/libpersona(11880): KNOX_SDCARD checking this for 10653
I/libpersona(11880): KNOX_SDCARD not a persona
I/SELinux (11880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3515): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11880 uid=10653 gids={50653, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11880): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11861): Shutting down VM
D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11880): TimaSignature is unavailable
D/ActivityThread(11880): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
D/ResourcesManager(11880): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6335): updateVisibility : ActivityRecord{2cd7fffd token=android.os.BinderProxy@283442e6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11880): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11880): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11880): Loading: webviewchromium
I/LibraryLoader(11880): Time to load native libraries: 29 ms (timestamps 5488-5517)
,I/LibraryLoader(11880): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11880): Binding Chromium to main looper Looper (main, tid 1) {20b5cb02}
I/LibraryLoader(11880): Expected native library version number "",actual native library version number ""
I/chromium(11880): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11880): Initializing chromium process, renderers=0
W/art     (11880): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11880): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11880): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11880): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11880): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11880): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11880): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11880): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11880): CordovaWebView is running on device made by: samsung
W/art     (11880): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11880): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11880): performCreate Call secproduct feature valuefalse
D/Activity(11880): performCreate Call debug elastic valuetrue
W/ActivityManager( 3515): Activity pause timeout for ActivityRecord{1689fa26 u0 com.test.thalitest/.MainActivity t26}
D/OpenGLRenderer(11880): Render dirty regions requested: true
D/ActivityManager( 3515): post active user change for 0
D/KnoxTimeoutHandler( 3515): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3515): handleActiveUserChange for user 0
V/ActivityThread(11880): updateVisibility : ActivityRecord{1942b5b9 token=android.os.BinderProxy@11baf038 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11880): Initialized EGL, version 1.4
I/OpenGLRenderer(11880): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278762736 
D/OpenGLRenderer(11880): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11880): Enabling debug mode 0
D/mali_winsys(11880): new_window_surface returns 0x3000,  [1440x2560]-format:1
D/InputMethodManagerService( 3515): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3515): mDVFSHelper.release()
I/Timeline( 3515): Timeline: Activity_windows_visible id: ActivityRecord{1689fa26 u0 com.test.thalitest/.MainActivity t26} time:225980
I/art     ( 3515): Explicit concurrent mark sweep GC freed 56820(3MB) AllocSpace objects, 44(704KB) LOS objects, 24% free, 49MB/65MB, paused 2.008ms total 167.906ms
W/IInputConnectionWrapper(11880): showStatusIcon on inactive InputConnection
I/Timeline(11880): Timeline: Activity_idle id: android.os.BinderProxy@11baf038 time:226144
W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium(11880): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11880): 
,D/JsMessageQueue(11880): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11880): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358474112
,I/chromium(11880): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11880): Initializing JXcore engine
W/jxcore-log(11880): JXcore engine is ready
,E/auditd  ( 4616): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3515): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3515): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11880): Starting JXcore engine
,W/jxcore-log(11880): Platform android
W/jxcore-log(11880): 
W/jxcore-log(11880): Process ARCH arm
W/jxcore-log(11880): 
,I/jxcore-log(11880): JXcore Cordova bridge is ready!
I/jxcore-log(11880): 
,W/jxcore-log(11880): JXcore engine is started
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11880): Toggling radios to true
I/jxcore-log(11880): 
,D/BluetoothAdapter(11880): enable()
D/BluetoothAdapter(11880): enable(): BT is already enabled..!
,D/WifiService( 3515): New client listening to asynchronous messages
,I/WifiManager(11880): packageName : com.test.thalitest
,D/SecContentProvider( 3515): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3515): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3515): mCursor = null
D/WifiService( 3515): setWifiEnabled: true pid=11880, uid=10653
E/WifiService( 3515): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3515): Permission Denial: getCurrentUser() from pid=11880, uid=10653 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3515): Failed getting userId using ActivityManagerNative
W/WifiService( 3515): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11880, uid=10653 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3515): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3515): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3515): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3515): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3515): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3515): name = wifi_on
,I/WifiService( 3515): disconnect: pid=11880, uid=10653
,I/wpa_supplicant( 3829): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11880): Radios toggled
I/jxcore-log(11880): 
,I/jxcore-log(11880): My device name is: samsung-SM-N910C
I/jxcore-log(11880): 
,I/wpa_supplicant( 3829): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3829): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3515): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3829): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): Disconnected - do not scan
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3515): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3515): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3515): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3515): do suspend true
,D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3515): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3515): updateNetworkInfo()
E/ConnectivityService( 3515): updateNetworkInfo()
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,E/WifiStateMachine( 3515): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3829): First Scan Start
E/WifiStateMachine( 3515): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3515): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/wpa_supplicant( 3829): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3515): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3515): do suspend true
,D/NearbySettings( 8882): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8882): MountReceiver.onReceive - Start HandlerThread
,I/Hs20UtilService( 4116): Starting #8
D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/NearbySettings( 8882): MountReceiver.onReceive - Create mPrefHandler
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8882): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8882): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3515): New client listening to asynchronous messages
,I/NearbySettings( 8882): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8882): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8882): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3515): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3515): Not allowed due to - mEnabled false
D/ConnectivityService( 3515): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3515): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3515): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3515): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 4778): CM callback handler got msg 524292
,D/WifiStateMachine( 3515): updateConfiguredNetworkExpiration - currTime: 1455113690142
D/WifiStateMachine( 3515): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/EntConnectivity( 3515): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3515): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
I/SignOutReceiver(11513): NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 3515): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3515): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService( 3515): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/WifiStateMachine( 3515): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3515): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3515): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/Tethering( 3515): MasterInitialState.processMessage what=3
D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
V/NetworkStats( 3515): updateIfacesLocked()
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/SmartBondingService( 3515): getSBEnabled() enabled =false
V/NetworkStats( 3515): performPollLocked(flags=0x1)
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3515): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
V/NetworkStats( 3515): performPollLocked() took 8ms
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
V/NetworkStats( 3515): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,I/Hs20UtilService( 4116): Starting #9
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8882): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8882): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8882): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8882): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8882): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11513): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,I/wpa_supplicant( 3829): Scan aborted because the firmware maybe busy.
I/wpa_supplicant( 3829): Therefore we will repeat the scan command after 1 seconds.
I/wpa_supplicant( 3829): wlan0: Setting scan request: 1 sec 0 usec
,D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3515): updateDataUsageMap
,I/ApplicationPolicy( 3515): updateDataUsageMap  idList is null 
D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3515): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3515): No Active Data Connection
,I/DBG_DM  ( 6335): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6335): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,W/fb4a(:<default>):UserScope(10965): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/Zygote  (12024): MountEmulatedStorage()
I/libpersona(12024): KNOX_SDCARD checking this for 1000
E/Zygote  (12024): v2
I/libpersona(12024): KNOX_SDCARD not a persona
W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
I/SELinux (12024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
I/SELinux (12024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12024): TimaSignature is unavailable
,D/ActivityThread(12024): Added TimaKeyStore provider
,D/ResourcesManager(12024): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12024): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12024): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12024): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12024): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12024): sales region : global
I/PCWCLIENTTRACE_PushUtil(12024): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12024): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12024): noConnectivity : true
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12040): MountEmulatedStorage()
E/Zygote  (12040): v2
I/libpersona(12040): KNOX_SDCARD checking this for 10135
I/libpersona(12040): KNOX_SDCARD not a persona
,I/SELinux (12040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12040): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12040 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11106:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 428us total 10.384ms
,D/TimaKeyStoreProvider(12040): TimaSignature is unavailable
,D/ActivityThread(12040): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 249us total 8.058ms
D/ResourcesManager(12040): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 480us total 8.207ms
,I/MusicStore(12040): Database version: 104
,D/ResourcesManager(12040): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12040): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12040): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12040): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12040): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12040): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@277794f8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12040): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12040): GMSCore installation verified
,I/ConfigStore(12040): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12040): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12040): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12040): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3515): getStreamVolume 3 index 0
,I/MediaRouter(12040): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12065): MountEmulatedStorage()
E/Zygote  (12065): v2
I/libpersona(12065): KNOX_SDCARD checking this for 10002
I/libpersona(12065): KNOX_SDCARD not a persona
,I/SELinux (12065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12065 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(12040): type=WIFI subType= reason=null isConnected=false
D/TimaKeyStoreProvider(12065): TimaSignature is unavailable
,D/ActivityThread(12065): Added TimaKeyStore provider
,I/ActivityManager( 3515): Killing 10950:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/ResourcesManager(12065): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3515): Killing 11124:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12084): MountEmulatedStorage()
E/Zygote  (12084): v2
I/libpersona(12084): KNOX_SDCARD checking this for 1000
I/libpersona(12084): KNOX_SDCARD not a persona
,I/SELinux (12084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12084): TimaSignature is unavailable
,D/ActivityThread(12084): Added TimaKeyStore provider
,D/ResourcesManager(12084): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(12084): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12084): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12084): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12084): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12084): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12100): MountEmulatedStorage()
,E/Zygote  (12100): v2
I/libpersona(12100): KNOX_SDCARD checking this for 10012
I/libpersona(12100): KNOX_SDCARD not a persona
,I/SELinux (12100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12100): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12100 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12100): TimaSignature is unavailable
,D/ActivityThread(12100): Added TimaKeyStore provider
,D/ResourcesManager(12100): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3515): Killing 11182:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,I/FOTA_Client(12100): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/lowmemorykiller( 2828): Error writing /proc/11182/oom_score_adj; errno=22
I/wpa_supplicant( 3829): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 3829): Scan requested (ret=0) - scan timeout 30 seconds
,I/FOTA_Client(12100): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12100): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12116): MountEmulatedStorage()
E/Zygote  (12116): v2
I/libpersona(12116): KNOX_SDCARD checking this for 10021
I/libpersona(12116): KNOX_SDCARD not a persona
,I/SELinux (12116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12116 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11216:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12116): TimaSignature is unavailable
,D/ActivityThread(12116): Added TimaKeyStore provider
,D/ResourcesManager(12116): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12116): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 10 15:14:51 GMT+01:00 2016
,I/KLMS-2.4.521: (12116): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12116): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12116): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12116): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12116): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12116): StateImplV2(): networkChangeListener().END
,E/Zygote  (12132): MountEmulatedStorage()
I/libpersona(12132): KNOX_SDCARD checking this for 10038
E/Zygote  (12132): v2
I/libpersona(12132): KNOX_SDCARD not a persona
I/SELinux (12132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3515): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12132 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (12132): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3515): Killing 11166:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12132): TimaSignature is unavailable
,D/ActivityThread(12132): Added TimaKeyStore provider
,D/ResourcesManager(12132): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12132): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12148): MountEmulatedStorage()
I/libpersona(12148): KNOX_SDCARD checking this for 1000
E/Zygote  (12148): v2
I/libpersona(12148): KNOX_SDCARD not a persona
,I/SELinux (12148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12148): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12148 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11231:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11231/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12148): TimaSignature is unavailable
,D/ActivityThread(12148): Added TimaKeyStore provider
,D/ResourcesManager(12148): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12168): MountEmulatedStorage()
E/Zygote  (12168): v2
I/libpersona(12168): KNOX_SDCARD checking this for 10039
I/libpersona(12168): KNOX_SDCARD not a persona
,I/SELinux (12168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12168): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12168 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11142:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12168): TimaSignature is unavailable
,D/ActivityThread(12168): Added TimaKeyStore provider
,D/ResourcesManager(12168): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12168): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12168): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12168): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12168): PushLog.txt file is not deleted.
D/SPPClientService(12168): PushLog.txt file is not deleted.
D/SPPClientService(12168): ============PushLog. stop!
,I/SA      (11268): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11268): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11268): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11268): [SLFUCHKMGR] constructor called
,E/SPPClientService(12168): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11268): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11268): [OR] == isSIMCardReady false ==
,I/SA      (11268): [SCU] == networkStateCheck == false
I/SA      (11268): [OR] onReceive END
,V/DownloadManager( 5386): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3515): Killing 11315:com.facebook.system/u0a10 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/11315/oom_score_adj; errno=22
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12188): MountEmulatedStorage()
I/libpersona(12188): KNOX_SDCARD checking this for 10067
E/Zygote  (12188): v2
I/libpersona(12188): KNOX_SDCARD not a persona
,I/SELinux (12188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12188 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12188): TimaSignature is unavailable
,D/ActivityThread(12188): Added TimaKeyStore provider
,D/ResourcesManager(12188): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12188): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12188): Other Intent
,I/ActivityManager( 3515): Killing 11352:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/accuweather( 5111): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5111): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5111): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5111): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5111): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5111): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5111): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12204): MountEmulatedStorage()
I/libpersona(12204): KNOX_SDCARD checking this for 1000
E/Zygote  (12204): v2
I/libpersona(12204): KNOX_SDCARD not a persona
,I/SELinux (12204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12204): TimaSignature is unavailable
,D/ActivityThread(12204): Added TimaKeyStore provider
,D/ResourcesManager(12204): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12204): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12204): premStatus:2
,I/KnoxUsageLogPro(12204): isEulaShown : false
I/KnoxUsageLogPro(12204): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12219): MountEmulatedStorage()
I/libpersona(12219): KNOX_SDCARD checking this for 10090
E/Zygote  (12219): v2
I/libpersona(12219): KNOX_SDCARD not a persona
,I/SELinux (12219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12219): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12219 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3515): Killing 11333:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12219): TimaSignature is unavailable
,D/ActivityThread(12219): Added TimaKeyStore provider
,D/ResourcesManager(12219): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12235): MountEmulatedStorage()
I/libpersona(12235): KNOX_SDCARD checking this for 10127
E/Zygote  (12235): v2
I/libpersona(12235): KNOX_SDCARD not a persona
,I/SELinux (12235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12235): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12235 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11375:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8750(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 555us total 10.469ms
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 254us total 7.939ms
,D/TimaKeyStoreProvider(12235): TimaSignature is unavailable
,D/ActivityThread(12235): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 506us total 8.600ms
,D/ResourcesManager(12235): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12235): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12235): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12235): stopCheckCategoryVersion
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12251): MountEmulatedStorage()
I/libpersona(12251): KNOX_SDCARD checking this for 10136
E/Zygote  (12251): v2
I/libpersona(12251): KNOX_SDCARD not a persona
,I/SELinux (12251): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12251): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12251): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12251 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3515): Killing 11393:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12251): TimaSignature is unavailable
,D/ActivityThread(12251): Added TimaKeyStore provider
,D/ResourcesManager(12251): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl(12251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12251): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12251): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12251): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12251): Loading: webviewchromium
,I/LibraryLoader(12251): Time to load native libraries: 2 ms (timestamps 9604-9606)
I/LibraryLoader(12251): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12251): Binding Chromium to main looper Looper (main, tid 1) {160d08a4}
,I/LibraryLoader(12251): Expected native library version number "",actual native library version number ""
,I/chromium(12251): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12251): Initializing chromium process, renderers=0
,W/art     (12251): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12251): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(12251): Requires BLUETOOTH permission
I/chromium(12251): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12251): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12251): Starting up...
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12319): MountEmulatedStorage()
E/Zygote  (12319): v2
I/libpersona(12319): KNOX_SDCARD checking this for 10150
I/libpersona(12319): KNOX_SDCARD not a persona
,I/SELinux (12319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12319 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3515): Killing 11404:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12319): TimaSignature is unavailable
,D/ActivityThread(12319): Added TimaKeyStore provider
,D/ResourcesManager(12319): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12319): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12319): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12319): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12319): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12319): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12319): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12335): MountEmulatedStorage()
E/Zygote  (12335): v2
I/libpersona(12335): KNOX_SDCARD checking this for 10178
I/libpersona(12335): KNOX_SDCARD not a persona
,I/SELinux (12335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12335 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11425:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12335): TimaSignature is unavailable
,D/ActivityThread(12335): Added TimaKeyStore provider
,D/ResourcesManager(12335): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12335): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12335): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12335): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12335): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12335): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,E/Zygote  (12358): MountEmulatedStorage()
E/Zygote  (12358): v2
I/libpersona(12358): KNOX_SDCARD checking this for 10082
I/libpersona(12358): KNOX_SDCARD not a persona
,I/SELinux (12358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12358): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12358 uid=10082 gids={50082, 9997} abi=armeabi-v7a
D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12358): TimaSignature is unavailable
,D/ActivityThread(12358): Added TimaKeyStore provider
,E/Zygote  (12374): MountEmulatedStorage()
E/Zygote  (12374): v2
I/libpersona(12374): KNOX_SDCARD checking this for 1000
I/libpersona(12374): KNOX_SDCARD not a persona
,I/SELinux (12374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11534:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3515): Killing 11553:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12374): TimaSignature is unavailable
,D/ActivityThread(12374): Added TimaKeyStore provider
,D/ResourcesManager(12358): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12374): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12358): onCreate
D/BadgeProvider(12358): DatabaseHelper
,I/ActivityManager( 3515): Killing 11570:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/BadgeProvider(12358): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12358): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12358): sendNotify, [notify] : null
D/BadgeProvider(12358): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12358): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12358): update, [UpdateCount] : 1
,D/Launcher.Model( 4002): reloadBadges entered.
,I/iu.Environment( 4778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4778): num queued entries: 0
,I/iu.UploadsManager( 4778): num updated entries: 0
I/iu.SyncManager( 4778): NEXT; no task
,W/ActivityManager( 3515): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12392): MountEmulatedStorage()
I/libpersona(12392): KNOX_SDCARD checking this for 10013
E/Zygote  (12392): v2
I/libpersona(12392): KNOX_SDCARD not a persona
,I/SELinux (12392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12392): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12392 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12392): TimaSignature is unavailable
,D/ActivityThread(12392): Added TimaKeyStore provider
,D/ResourcesManager(12392): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3515): Killing 11608:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11880): 
,I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11880): 
I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11880): 
I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11880): 
I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11880): 
I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11880): 
,I/wpa_supplicant( 3829): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3829): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3829): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3829): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3515): [1,455,113,694,673 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3515): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@678795b sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3515): setDetailed state send new extra info
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3515): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3829): Associated with C0.AA.48
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3829): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3829): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3829): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3829): Blacklist: Clear (temp) 
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3515): Network connection established
,D/WifiNative-HAL( 3515): callSECApiVoid - ID [50]
E/WifiStateMachine( 3515): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3515): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3515): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3515): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3515): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3515): hsengiv:checkWhatTypeOfNetwork and the value is false
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService( 3515): updateNetworkInfo()
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/Hs20UtilService( 4116): Starting #10
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8882): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8882): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8882): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8882): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11513): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3515): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3515): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3515): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3515): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3515): do suspend false
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
,E/dhcpcd  (12409): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12409): version 5.5.6 starting
,E/dhcpcd  (12409): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12409): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12409): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12409): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12409): bssid match
I/dhcpcd  (12409): wlan0: rebinding lease of 192.168.1.124
,W/ProcessCpuTracker( 3515): Skipping unknown process pid 12410
,D/WearableService( 4668): callingUid 10014, callindPid: 4668
,D/ResourcesManager(12040): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12040): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12040): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12040): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12040): Conditions not met for autocaching.
I/MusicLeanback(12040): Stop autocaching.
,D/WearableClient(12040): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12040): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12040): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12040): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12040): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils(12040): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12040): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@322347d0 that was originally bound here
E/ActivityThread(12040): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@322347d0 that was originally bound here
E/ActivityThread(12040): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12040): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12040): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12040): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12040): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12040): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12040): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12040): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12040): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12040): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12040): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12040): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12040): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12040): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12040): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12040): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12040): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12040): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12040): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12040): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12040): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12040): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12040): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12040): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12040): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/dhcpcd  (12409): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11880): 
,I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(11880): 
,I/dhcpcd  (12409): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11880): 
,I/jxcore-log(11880): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11880): 
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3515): do suspend true
,D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3515): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3515): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3515): Not connected state, yet.
E/WifiStateMachine( 3515): VerifyingLinkState enter
,D/WifiStateMachine( 3515): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3515): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3515): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3515): callSECApiInt - ID [210]
,E/WifiStateMachine( 3515): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3515): updateNetworkInfo()
,D/ConnectivityService( 3515): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3515): Adding iface wlan0 to network 503
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine( 3515): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3515): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3515): Now, connected state.
E/WifiStateMachine( 3515): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3515): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4116): Starting #11
,I/Hs20UtilService( 4116): Message received 5007
,I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3515): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3515): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService( 3515): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 3515): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiStateMachine( 3515): REQUEST_POWER_SAVE_ON
,D/ConnectivityService( 3515): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3515): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3515): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/NearbySettings( 8882): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8882): MountReceiver.onReceive - Keep current state
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11513): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4116): Starting #12
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8882): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8882): DMSUtil.isNetworkConnected - flag-null, state-null
V/        ( 2845): QcRouteController
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,V/        ( 2845): QcRouteController
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8882): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8882): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8882): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11513): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4116): Starting #13
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8882): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8882): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3515): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3515): LTETest block dns file not exists
,D/ConnectivityService( 3515): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3515): updateNetworkInfo()
E/ConnectivityService( 3515): updateNetworkInfo()
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3515): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3515):    accepting network in place of null
,I/WifiStateMachine( 3515): callSECApi what=220
D/WifiStateMachine( 3515): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/CSLegacyTypeTracker( 3515): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker( 3515): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3982): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out( 3515): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 3515): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3515): MasterInitialState.processMessage what=3
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
D/EntConnectivity( 3515): Not allowed due to - mEnabled false
D/ConnectivityService( 3515): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
,D/ConnectivityManager.CallbackHandler( 4778): CM callback handler got msg 524290
V/NetworkStats( 3515): updateIfacesLocked()
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
V/NetworkStats( 3515): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3515): UpdateStatsForKnox
,V/NetworkStats( 3515): performPollLocked() took 3ms
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
V/NetworkStats( 3515): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,I/SignOutReceiver(11513): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,I/System.out( 3515): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PowerManagerService( 3515): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3515
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 14:14:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455113696721], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455113696708]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Validated
D/ConnectivityService( 3515): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3515): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4778): CM callback handler got msg 524290
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,I/PowerManagerService( 3515): [PWL] Off : 140s ago
I/PowerManagerService( 3515): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3515): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3515): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3515, ws=null) (elapsedTime=6584)
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11880): Test app app.js loaded
I/jxcore-log(11880): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11880): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20aeef46 added. We now have 1 listener(s)
,I/jxcore-log(11880): BLE advertisement is supported
I/jxcore-log(11880): 
,I/chromium(11880): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11880): --= Surplus to requirements =--
I/jxcore-log(11880): 
I/jxcore-log(11880): ****TEST TOOK:  ms ****
I/jxcore-log(11880): 
I/jxcore-log(11880): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11880): 
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 69556(3MB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 49MB/65MB, paused 1.178ms total 73.900ms
,I/GAV4    (12251): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 3515): SIOP:: AP = 280, PST = 251, CUR = 65
,D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3515): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3515): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3515): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
,D/AndroidRuntime(12478): 
D/AndroidRuntime(12478): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12478): CheckJNI is OFF
,D/AndroidRuntime(12478): readGMSProperty: start
D/AndroidRuntime(12478): readGMSProperty: already setted!!
,I/DBG_DM  ( 6335): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/AndroidRuntime(12478): readGMSProperty: end
D/AndroidRuntime(12478): addProductProperty: start
I/DBG_DM  ( 6335): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5352): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5352): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,I/NetworkMonitor(12040): type=WIFI subType= reason=null isConnected=true
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):UserScope(10965): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10965): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,I/PCWCLIENTTRACE_PushUtil(12024): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12024): sales region : global
I/PCWCLIENTTRACE_PushUtil(12024): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12024): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3515): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3515): mCursor = null
,I/DIAGMON_AGENT(12084): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12084): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/AffinityControl(12478): AffinityControl: registerfunction enter
,I/FOTA_Client(12100): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/AndroidRuntime(12478): Calling main entry com.android.commands.pm.Pm
,I/FOTA_Client(12100): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12100): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/PersonaManagerService( 3515): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3515): START PACKAGE DELETE: observer{299137836}
D/PackageManager( 3515): pkg{<packageName>}
D/PackageManager( 3515): user{0}
D/PackageManager( 3515): caller{2000}
D/PackageManager( 3515): flags{3}
D/PersonaManagerService( 3515): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3515): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3515): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3515): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3515): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3515): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3515): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3515): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3515): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3515): !@killApplicatoin: 10653, uninstall pkg
,I/ActivityManager( 3515): Force stopping com.test.thalitest appid=10653 user=-1: uninstall pkg
I/ActivityManager( 3515): Killing 11880:com.test.thalitest/u0a653 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3515):   Force finishing activity ActivityRecord{1689fa26 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3515): mDVFSHelper.acquire()
,W/PackageSettings( 3515): Skipping PackageSetting{25b29f6f com.example.hello/10563} due to missing metadata
,I/KLMS-2.4.521: (12116): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 10 15:14:57 GMT+01:00 2016
,D/WifiService( 3515): Client connection lost with reason: 4
,I/WindowState( 3515): WIN DEATH: Window{3f275dc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/9)
I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/9)
,D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3515): Force stopping com.test.thalitest appid=10653 user=0: pkg removed
,I/ActivityManager( 3515):   Force finishing activity ActivityRecord{1689fa26 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3515): Duplicate finish request for ActivityRecord{1689fa26 u0 com.test.thalitest/.MainActivity t26 f}
,I/art     ( 4056): Explicit concurrent mark sweep GC freed 35680(2MB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 794us total 20.678ms
,I/art     ( 9106): Explicit concurrent mark sweep GC freed 24238(1423KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 486us total 19.086ms
,I/DBG_DM  ( 6335): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/KLMS-2.4.521: (12116): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 4778): Explicit concurrent mark sweep GC freed 24857(1459KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 1.056ms total 54.007ms
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onCreate()
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/KLMS-2.4.521: (12116): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12116): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/DBG_DM  ( 6335): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 13
,I/KLMS-2.4.521: (12116): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/InputReader( 3515): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/SamsungIME( 4497): mOCRHelper is null
W/GeofencerStateMachine( 4668): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6335): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (12116): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/LWLocationManager(11589): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11589): getLastUiLocationId() : mLastUiLocationId = -100
,I/KLMS-2.4.521: (12116): StateImplV2(): networkChangeListener().START
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/KLMS-2.4.521: (12116): NetworkChangeOperations(): uploadRequestLog().START 
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,W/ResourceType( 5352): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5352): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/KLMS-2.4.521: (12116): NetworkChangeOperations(): uploadRequestLog().END 
,D/SecContentProvider2( 3515): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3515): mCursor = null
D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/SO_AGENT(12132): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ApplicationPolicy( 3515): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/KLMS-2.4.521: (12116): StateImplV2(): networkChangeListener().END
I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 13
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6335): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6335): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6335): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6335): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6335): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3515): post active user change for 0
D/KnoxTimeoutHandler( 3515): postActiveUserChange for user 0
,I/DBG_DM  ( 6335): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
I/KLMS-2.4.521: (12116): KLMSIntentService(): onDestroy()
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/EnterpriseDeviceManagerService( 3515): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3515): Admin package name: com.google.android.gms
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/RegisteredServicesCache( 3971): empty dynamic service
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
V/ActivityThread( 6335): updateVisibility : ActivityRecord{2cd7fffd token=android.os.BinderProxy@283442e6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/art     ( 3515): Explicit concurrent mark sweep GC freed 21173(1671KB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 49MB/65MB, paused 8.167ms total 99.923ms
,E/SPPClientService(12168): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/PackageManager( 3515): delete codoeFile: 
,I/AASAUninstall( 3515):  com.test.thalitest not target!
,D/PackageManager( 3515): result of delete: 1{299137836}
,D/InputMethodManagerService( 3515): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/AndroidRuntime(12478): Shutting down VM
D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4255, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3515): online:4, current avg:-267, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1508
D/BatteryService( 3515): stay LED for fully charged
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Books/Books.apk
,W/InputMethodManagerService( 3515): Got RemoteException sending setActive(false) notification to pid 11880 uid 10653
I/SA      (11268): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11268): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11268): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/SA      (11268): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11268): [OR] == isSIMCardReady false ==
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/SA      (11268): [SCU] == networkStateCheck == true
,I/SA      (11268): [DM] getCountryCodeFromCSC : PL
I/SA      (11268): isChinaCountryCode : false
I/SA      (11268): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11268): [OR] == networkStateCheck true ==
,I/SA      (11268): [OR] GetMyCountryZoneTask
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/Timeline( 6335): Timeline: Activity_idle id: android.os.BinderProxy@283442e6 time:235220
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/SA      (11268): [OR] onReceive END
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SA      (11268): [SRS] prepareGetMyCountryZone
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/SA      (11268): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SA      (11268): [SSP] query invoked
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/SA      (11268): [TPMU] GetMccFromDB : null
I/SA      (11268): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11268): [TPM] isNoProxy(default) : true
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,V/DownloadManager( 5386): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/PackageManager( 3515): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ActivityManager( 3515): mDVFSHelper.release()
D/SecContentProvider2( 3515): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3515): mCursor = null
I/Timeline( 3515): Timeline: Activity_windows_visible id: ActivityRecord{17ab8dce u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:235246
,D/ConnectivityService( 3515): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManagerService( 3515): PackageReceiver onReceive()
,I/HarmonyEASService( 3515): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3515): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 3515): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3515): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3515): uID is 10653
V/EnterpriseBillingPolicy( 3515): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3515): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3515): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3515): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3515): getBillingProfileForVpnEngine - end - null
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,I/SCloudBackupReceiver(12188): Other Intent
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/KnoxTimeoutHandler( 3515): handleActiveUserChange for user 0
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,D/accuweather( 5111): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11589): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5664): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5664): Disconnected process message: 10
,D/TaskPersister( 3515): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3515): removeObsoleteFile: deleting file=24_task.xml
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/accuweather( 5111): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5111): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5111): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5111): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/MotionRecognitionService( 3515): Plugged
I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/accuweather( 5111): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5111): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/StatusBar( 3693): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/KnoxUsageLogPro(12204): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12204): premStatus:2
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
,I/KnoxUsageLogPro(12204): isEulaShown : false
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
,D/PanelView( 3693): There is/are notification(s) 
I/KnoxUsageLogPro(12204): KnoxUsageReceiver onReceive : not Processible, just return
W/ResourceType( 3515): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/ResourcesManager(11589): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11589): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KeyguardWallpaperUpdator(12235): cancelUpdateWallpaper
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KeyguardWallpaperUpdator(12235): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12235): stopCheckCategoryVersion
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
W/ResourcesManager( 3515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/QuickConnect(12319): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
I/QuickConnect(12319): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12319): PeriphStartReceiver.onReceive - no need to start
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3515): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3515): onPackageRemoved : com.test.thalitest
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/iu.Environment( 4778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/iu.UploadsManager( 4778): num queued entries: 0
,I/iu.UploadsManager( 4778): num updated entries: 0
,I/iu.SyncManager( 4778): NEXT; no task
,D/ResourcesManager(11589): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/WaitQueueForNetworkActivate(12392): notifyNetworkActivated
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl(12392): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3515): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,I/SA      (11268): [RC New] Execute method=[GET] start
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
I/SA      (11268): [RC New] Security=[true]
,I/System.out(11268): Thread-1555(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11268): Thread-1555(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11268): Thread-1555(ApacheHTTPLog):isShipBuild true
I/System.out(11268): Thread-1555(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/hcjo    (12392): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12392): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12392): exit::IDLE
D/InitializeManagerStateMachine(12392): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12392): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12392): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12392): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12392): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12392): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12392): entry::SUCCESS
D/hcjo    (12392): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  (12515): MountEmulatedStorage()
E/Zygote  (12515): v2
I/libpersona(12515): KNOX_SDCARD checking this for 10063
I/libpersona(12515): KNOX_SDCARD not a persona
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/ActivityManager( 3515): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12515 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/hcjo    (12392): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12392): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12392): exit::SUCCESS
D/InitializeManagerStateMachine(12392): entry::IDLE
,I/SELinux (12515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/TimaKeyStoreProvider(12515): TimaSignature is unavailable
,D/ActivityThread(12515): Added TimaKeyStore provider
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(12515): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12515): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12515): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12515): packagename:com.test.thalitest
,I/KLMS-2.4.521: (12116): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 10 15:14:57 GMT+01:00 2016
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3515): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3515): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3515): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3515): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/UsbHostManager( 3515): displayNotification : [09h,00h,00h]
,I/KLMS-2.4.521: (12116): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3515): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3515): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/UsbHostManager( 3515): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3515): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3515): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
I/KLMS-2.4.521: (12116): KLMSIntentService(): onCreate()
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12116): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12116): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12116): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12116): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12116): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,E/Zygote  (12537): MountEmulatedStorage()
E/Zygote  (12537): v2
I/libpersona(12537): KNOX_SDCARD checking this for 10106
I/libpersona(12537): KNOX_SDCARD not a persona
,I/SELinux (12537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12537 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12537): TimaSignature is unavailable
,D/ActivityThread(12537): Added TimaKeyStore provider
,D/RCPManager(12204):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3515):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3515): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(11589): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(12537): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12116): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11589): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/UsbHostManager( 3515): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3515): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,E/Zygote  (12553): MountEmulatedStorage()
E/Zygote  (12553): v2
I/libpersona(12553): KNOX_SDCARD checking this for 10050
I/libpersona(12553): KNOX_SDCARD not a persona
,I/SELinux (12553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/elm:14491(12537): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12537): ELMEngine.ELMEngine( context ).
,I/SELinux (12553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/elm:14491(12537): MDMBridge.setEnterpriseBridge()
,I/ActivityManager( 3515): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12553 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12116): KLMSIntentService(): onDestroy()
,I/EventHub( 3515): Removing device '/dev/input/event10' due to inotify event
,D/elm:14491(12537): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12537): ElmAgentService : onCreate()
D/elm:14491(12537): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12537): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12537): MDMBridge.getInstance()
D/elm:14491(12537): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider(12553): TimaSignature is unavailable
,D/ActivityThread(12553): Added TimaKeyStore provider
,D/elm:14491(12537): MDMBridge.getAllLicenseInfoFromSDK()
,I/EventHub( 3515): Removing device '/dev/input/event7' due to inotify event
,E/Zygote  (12570): MountEmulatedStorage()
E/Zygote  (12570): v2
I/libpersona(12570): KNOX_SDCARD checking this for 10101
I/libpersona(12570): KNOX_SDCARD not a persona
,I/SELinux (12570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3515): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12570 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12570): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/EventHub( 3515): Removing device '/dev/input/event8' due to inotify event
,D/elm:14491(12537): ElmAgentService : onDestroy().
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3515): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12553): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/TimaKeyStoreProvider(12570): TimaSignature is unavailable
,D/ActivityThread(12570): Added TimaKeyStore provider
,W/ResourcesManager(12553): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12553): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12553): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12553): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12553): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12553): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12553): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12553): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3515): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(11589): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,E/Zygote  (12586): MountEmulatedStorage()
E/Zygote  (12586): v2
I/libpersona(12586): KNOX_SDCARD checking this for 10183
I/libpersona(12586): KNOX_SDCARD not a persona
,I/SELinux (12586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12586 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager(11589): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/EventHub( 3515): Removing device '/dev/input/event12' due to inotify event
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.791ms total 52.087ms
,I/EventHub( 3515): Removing device '/dev/input/event13' due to inotify event
,I/ActivityManager( 3515): Killing 11624:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/EventHub( 3515): Removing device '/dev/input/event14' due to inotify event
,D/TimaKeyStoreProvider(12586): TimaSignature is unavailable
,D/ActivityThread(12586): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 3.937ms total 52.209ms
,D/ResourcesManager(12570): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.781ms total 44.088ms
,E/Zygote  (12601): MountEmulatedStorage()
E/Zygote  (12601): v2
I/libpersona(12601): KNOX_SDCARD checking this for 10019
I/libpersona(12601): KNOX_SDCARD not a persona
,I/SELinux (12601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3515): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12601 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (12601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
