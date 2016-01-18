#### Test 56151093b6ab50f_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3512): SIOP:: AP = 250, PST = 263, CUR = 38
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3512): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:72
D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3512): Plugged
I/MotionRecognitionService( 3512): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/BatteryService( 3512): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5601): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11796): 
D/AndroidRuntime(11796): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11796): CheckJNI is OFF
D/AndroidRuntime(11796): readGMSProperty: start
D/AndroidRuntime(11796): readGMSProperty: already setted!!
D/AndroidRuntime(11796): readGMSProperty: end
D/AndroidRuntime(11796): addProductProperty: start
E/AffinityControl(11796): AffinityControl: registerfunction enter
D/AndroidRuntime(11796): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3512): inState():  stateMachine is null !!
I/PersonaManagerService( 3512): PersonaId don't exist
I/ActivityManager( 3512): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3512): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3512): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3512): mDVFSHelper.acquire()
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (11814): MountEmulatedStorage()
I/libpersona(11814): KNOX_SDCARD checking this for 10582
E/Zygote  (11814): v2
I/libpersona(11814): KNOX_SDCARD not a persona
I/SELinux (11814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3512): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11814 uid=10582 gids={50582, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11814): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11796): Shutting down VM
D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11814): TimaSignature is unavailable
D/ActivityThread(11814): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11814): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6293): updateVisibility : ActivityRecord{3431107c token=android.os.BinderProxy@19fc59c9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11814): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11814): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11814): Loading: webviewchromium
I/LibraryLoader(11814): Time to load native libraries: 3 ms (timestamps 4996-4999)
I/LibraryLoader(11814): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11814): Binding Chromium to main looper Looper (main, tid 1) {1d8d293f}
,I/LibraryLoader(11814): Expected native library version number "",actual native library version number ""
I/chromium(11814): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11814): Initializing chromium process, renderers=0
,W/art     (11814): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11814): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11814): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11814): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11814): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11814): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11814): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11814): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11814): CordovaWebView is running on device made by: samsung
,W/art     (11814): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11814): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11814): performCreate Call secproduct feature valuefalse
D/Activity(11814): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11814): Render dirty regions requested: true
,D/ActivityManager( 3512): post active user change for 0
D/KnoxTimeoutHandler( 3512): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3512): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11814): Initialized EGL, version 1.4
I/OpenGLRenderer(11814): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278643952 
D/OpenGLRenderer(11814): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11814): Enabling debug mode 0
D/mali_winsys(11814): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11814): updateVisibility : ActivityRecord{2668e02f token=android.os.BinderProxy@3ed35612 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3512): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3512): mDVFSHelper.release()
I/Timeline( 3512): Timeline: Activity_windows_visible id: ActivityRecord{6ffb2eb u0 com.test.thalitest/.MainActivity t26} time:135339
,W/IInputConnectionWrapper(11814): showStatusIcon on inactive InputConnection
,I/Timeline(11814): Timeline: Activity_idle id: android.os.BinderProxy@3ed35612 time:135348
,I/chromium(11814): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11814): 
,D/JsMessageQueue(11814): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11814): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357428096
D/JX-Cordova(11814): jxcore cordova android initializing
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11814): Initializing JXcore engine
W/jxcore-log(11814): JXcore engine is ready
,W/jxcore-log(11814): Starting JXcore engine
,E/auditd  ( 4610): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3512): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3512): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11814): Platform android
W/jxcore-log(11814): 
,W/jxcore-log(11814): Process ARCH arm
W/jxcore-log(11814): 
,I/jxcore-log(11814): JXcore Cordova bridge is ready!
I/jxcore-log(11814): 
W/jxcore-log(11814): JXcore engine is started
,I/jxcore-log(11814): Toggling radios to true
I/jxcore-log(11814): 
D/BluetoothAdapter(11814): enable()
D/BluetoothAdapter(11814): enable(): BT is already enabled..!
D/WifiService( 3512): New client listening to asynchronous messages
,I/WifiManager(11814): packageName : com.test.thalitest
,D/SecContentProvider( 3512): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3512): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3512): mCursor = null
,D/WifiService( 3512): setWifiEnabled: true pid=11814, uid=10582
E/WifiService( 3512): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3512): Permission Denial: getCurrentUser() from pid=11814, uid=10582 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3512): Failed getting userId using ActivityManagerNative
W/WifiService( 3512): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11814, uid=10582 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3512): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3512): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3512): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3512): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3512): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3512): name = wifi_on
I/WifiService( 3512): disconnect: pid=11814, uid=10582
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11814): Radios toggled
I/jxcore-log(11814): 
,I/jxcore-log(11814): My device name is: samsung-SM-N910C
I/jxcore-log(11814): 
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3512): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): Disconnected - do not scan
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3512): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3512): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3512): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3512): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3512): do suspend true
,D/WifiP2pService( 3512): InactiveState{ what=143375 }
,D/WifiP2pService( 3512): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3512): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3512): updateNetworkInfo()
D/ConnectivityService( 3512): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3512): updateNetworkInfo()
E/WifiConfigStore( 3512): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3512): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3512): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3512): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3833): First Scan Start
E/WifiStateMachine( 3512): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3512): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3512): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3512): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3512): do suspend true
I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/WifiP2pService( 3512): InactiveState{ what=143375 }
,D/WifiP2pService( 3512): P2pEnabledState{ what=143375 }
,D/NearbySettings( 8821): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8821): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8821): MountReceiver.onReceive - Create mPrefHandler
I/Hs20UtilService( 4147): Starting #8
I/Hs20UtilService( 4147): Message received 5007
D/NearbySettings( 8821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8821): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3512): New client listening to asynchronous messages
,I/NearbySettings( 8821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8821): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8821): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3512): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3512): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
E/WifiStateMachine( 3512): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3512): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3512): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 3985): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3512): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SignOutReceiver(11424): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524292
,D/EntConnectivity( 3512): Not allowed due to - mEnabled false
D/ConnectivityService( 3512): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering( 3512): MasterInitialState.processMessage what=3
D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3512): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
V/NetworkStats( 3512): updateIfacesLocked()
V/NetworkStats( 3512): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3512): UpdateStatsForKnox
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/WifiStateMachine( 3512): updateConfiguredNetworkExpiration - currTime: 1453102594153
D/WifiStateMachine( 3512): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3512): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3512): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3512): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3512): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,V/NetworkStats( 3512): performPollLocked() took 5ms
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,E/WifiStateMachine( 3512): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3512): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3512): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3512): evaluateTrafficStatsPolling
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3512): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
V/NetworkStats( 3512): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
I/Hs20UtilService( 4147): Starting #9
I/Hs20UtilService( 4147): Message received 5007
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NearbySettings( 8821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8821): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8821): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8821): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11424): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3512): updateDataUsageMap
I/ApplicationPolicy( 3512): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3512): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3512): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3512): No Active Data Connection
,I/DBG_DM  ( 6293): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6293): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11903): MountEmulatedStorage()
E/Zygote  (11903): v2
I/libpersona(11903): KNOX_SDCARD checking this for 10110
I/libpersona(11903): KNOX_SDCARD not a persona
,I/SELinux (11903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11903): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11903 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11903): TimaSignature is unavailable
,D/ActivityThread(11903): Added TimaKeyStore provider
,D/ResourcesManager(11903): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11903): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11903): not using cross-dex optimization: ART in use
,I/art     (11903): Thread[1,tid=11903,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11903): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11903): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11903): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11903): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11903): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11903): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11903): loading pre-built fallback odex files
,V/MultiDexClassLoader(11903): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11903): released odex store lock
D/DexLibLoader(11903): DexLibLoader.loadAll took 18 ms
,W/ca      (11903): Verify
,W/LightSharedPreferencesImpl(11903): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11903): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11903): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11903): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11903): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11903): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11903): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11903): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11903): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11903): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11903): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11903): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11903): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11903): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11903): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11903): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11903): 	... 10 more
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11928): MountEmulatedStorage()
I/libpersona(11928): KNOX_SDCARD checking this for 1000
E/Zygote  (11928): v2
I/libpersona(11928): KNOX_SDCARD not a persona
I/SELinux (11928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3512): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11928): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Killing 11023:com.policydm/1000 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11903): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/appmanager(:<default>):b(11903): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11928): TimaSignature is unavailable
,D/ActivityThread(11928): Added TimaKeyStore provider
,D/ResourcesManager(11928): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11928): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11928): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11928): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11928): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11928): sales region : global
I/PCWCLIENTTRACE_PushUtil(11928): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11928): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11928): noConnectivity : true
,W/appmanager(:<default>):QuickExperimentControllerImpl(11903): Exposure of experiment com.facebook.common.network.l@10a216ad occurred when no user was logged in
,W/BroadcastQueue( 3512): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3e158b3e u0 ReceiverList{5977ff9 11903 com.facebook.appmanager/10110/u0 remote:3ca7b6c0}}
,W/BroadcastQueue( 3512): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3e158b3e u0 ReceiverList{5977ff9 11903 com.facebook.appmanager/10110/u0 remote:3ca7b6c0}}
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11951): MountEmulatedStorage()
E/Zygote  (11951): v2
I/libpersona(11951): KNOX_SDCARD checking this for 10135
I/libpersona(11951): KNOX_SDCARD not a persona
I/SELinux (11951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11951): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11951 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 10938:com.android.mms/u0a52 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11951): TimaSignature is unavailable
,D/ActivityThread(11951): Added TimaKeyStore provider
,D/ResourcesManager(11951): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3512): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3420ba2 u0 ReceiverList{2a45f36d 11903 com.facebook.appmanager/10110/u0 remote:204abf84}}
,D/CountryDetector( 3512): No listener is left
,I/MusicStore(11951): Database version: 104
,D/ResourcesManager(11951): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11951): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11951): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ded19a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11951): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11951): GMSCore installation verified
,I/ConfigStore(11951): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11951): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11903): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11903): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11951): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11951): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11903): Exposure of experiment com.facebook.imagepipeline.a.g@27660b62 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11903): Exposure of experiment com.facebook.imagepipeline.a.d@2d0dd4f occurred when no user was logged in
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3512): getStreamVolume 3 index 0
,I/MediaRouter(11951): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3833): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 3833): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3833): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3833): wlan0: State: SCANNING -> ASSOCIATING
E/WifiStateMachine( 3512): [1,453,102,595,187 ms] noteScanEnd no scan source
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3512): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@210ad97a sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3512): setDetailed state send new extra info
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,I/art     (11903): Explicit concurrent mark sweep GC freed 48076(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 657us total 23.698ms
,W/appmanager(:<default>):m(11903): No feature status reporters found; is this dead code?
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11986): MountEmulatedStorage()
E/Zygote  (11986): v2
I/libpersona(11986): KNOX_SDCARD checking this for 10002
I/libpersona(11986): KNOX_SDCARD not a persona
,I/SELinux (11986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11986 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 294us total 9.670ms
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(11986): TimaSignature is unavailable
,D/ActivityThread(11986): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 264us total 8.578ms
,I/NetworkMonitor(11951): type=WIFI subType= reason=null isConnected=false
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 426us total 8.264ms
,I/ActivityManager( 3512): Killing 11042:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/ResourcesManager(11986): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3833): Associated with C0.AA.48
E/WifiStateMachine( 3512): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/ActivityManager( 3512): Killing 11061:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3833): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3833): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3833): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3833): Blacklist: Clear (temp) 
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  (12007): MountEmulatedStorage()
I/libpersona(12007): KNOX_SDCARD checking this for 1000
E/Zygote  (12007): v2
I/libpersona(12007): KNOX_SDCARD not a persona
,I/SELinux (12007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine( 3512): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3512): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3512): Network connection established
,D/WifiNative-HAL( 3512): callSECApiVoid - ID [50]
E/WifiStateMachine( 3512): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3512): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/TimaKeyStoreProvider(12007): TimaSignature is unavailable
,D/ActivityThread(12007): Added TimaKeyStore provider
,D/ConnectivityService( 3512): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3512): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3512): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3512): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3512): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3512): updateNetworkInfo()
,D/ConnectivityService( 3512): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3512): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3512): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3512): ObtainingIpAddress "NG700" nid=0
I/art     ( 3512): Explicit concurrent mark sweep GC freed 61486(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 3.747ms total 91.732ms
E/WifiConfigStore( 3512): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(12007): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/CommandListener( 2845): Setting iface cfg
E/WifiStateMachine( 3512): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12007): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12007): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT(12007): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT(12007): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12007): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/WifiStateMachine( 3512): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3512): do suspend false
D/SecContentProvider2( 3512): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3512): mCursor = null
D/WifiP2pService( 3512): InactiveState{ what=143375 }
D/WifiP2pService( 3512): P2pEnabledState{ what=143375 }
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12025): MountEmulatedStorage()
I/libpersona(12025): KNOX_SDCARD checking this for 10012
E/Zygote  (12025): v2
I/libpersona(12025): KNOX_SDCARD not a persona
I/SELinux (12025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12025): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12025 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider(12025): TimaSignature is unavailable
D/ActivityThread(12025): Added TimaKeyStore provider
D/ResourcesManager(12025): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/ActivityManager( 3512): Killing 11078:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
I/FOTA_Client(12025): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(12025): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(12025): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12041): MountEmulatedStorage()
I/libpersona(12041): KNOX_SDCARD checking this for 10021
E/Zygote  (12041): v2
I/libpersona(12041): KNOX_SDCARD not a persona
I/SELinux (12041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12041 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 10892:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/10892/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12041): TimaSignature is unavailable
D/ActivityThread(12041): Added TimaKeyStore provider
D/ResourcesManager(12041): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: (12041): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 08:36:35 GMT+01:00 2016
I/KLMS-2.4.521: (12041): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12041): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12041): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12041): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12041): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12041): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (12041): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (12041): StateImplV2(): networkChangeListener().END
E/Zygote  (12057): MountEmulatedStorage()
I/libpersona(12057): KNOX_SDCARD checking this for 10038
E/Zygote  (12057): v2
I/libpersona(12057): KNOX_SDCARD not a persona
I/SELinux (12057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12057 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (12041): KLMSIntentService(): onDestroy()
I/ActivityManager( 3512): Killing 11121:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12057): TimaSignature is unavailable
D/ActivityThread(12057): Added TimaKeyStore provider
D/ResourcesManager(12057): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
I/SO_AGENT(12057): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/dhcpcd  (12072): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/Zygote  (12073): MountEmulatedStorage()
I/libpersona(12073): KNOX_SDCARD checking this for 1000
E/Zygote  (12073): v2
I/libpersona(12073): KNOX_SDCARD not a persona
I/dhcpcd  (12072): version 5.5.6 starting
I/SELinux (12073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3512): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/dhcpcd  (12072): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/ActivityManager( 3512): Killing 11157:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12073): TimaSignature is unavailable
D/ActivityThread(12073): Added TimaKeyStore provider
D/ResourcesManager(12073): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
I/dhcpcd  (12072): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12072): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12072): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12072): bssid match
I/dhcpcd  (12072): wlan0: rebinding lease of 192.168.1.124
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12099): MountEmulatedStorage()
I/libpersona(12099): KNOX_SDCARD checking this for 10039
E/Zygote  (12099): v2
I/libpersona(12099): KNOX_SDCARD not a persona
I/SELinux (12099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12099): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12099 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 11194:com.wsomacp/u0a28 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/11194/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12099): TimaSignature is unavailable
D/ActivityThread(12099): Added TimaKeyStore provider
D/ResourcesManager(12099): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService(12099): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12099): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService(12099): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
D/SPPClientService(12099): PushLog.txt file is not deleted.
D/SPPClientService(12099): PushLog.txt file is not deleted.
D/SPPClientService(12099): ============PushLog. stop!
I/SA      (11233): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11233): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11233): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11233): [SLFUCHKMGR] constructor called
E/SPPClientService(12099): [[SystemStateMonitorService]] No Active Internet
I/SA      (11233): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11233): [OR] == isSIMCardReady false ==
I/SA      (11233): [SCU] == networkStateCheck == false
I/SA      (11233): [OR] onReceive END
V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 3512): Killing 11139:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12119): MountEmulatedStorage()
I/libpersona(12119): KNOX_SDCARD checking this for 10067
E/Zygote  (12119): v2
I/libpersona(12119): KNOX_SDCARD not a persona
I/SELinux (12119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12119 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(12119): TimaSignature is unavailable
D/ActivityThread(12119): Added TimaKeyStore provider
D/ResourcesManager(12119): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/sCloudBackupApp(12119): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12119): Other Intent
I/ActivityManager( 3512): Killing 11175:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
D/accuweather( 5289): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
D/accuweather( 5289): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5289): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5289): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5289): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5289): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5289): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12135): MountEmulatedStorage()
E/Zygote  (12135): v2
I/libpersona(12135): KNOX_SDCARD checking this for 1000
I/libpersona(12135): KNOX_SDCARD not a persona
I/SELinux (12135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12135): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12135 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider(12135): TimaSignature is unavailable
D/ActivityThread(12135): Added TimaKeyStore provider
D/ResourcesManager(12135): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(12135): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/KnoxUsageLogPro(12135): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12135): premStatus:2
I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11814): 
I/KnoxUsageLogPro(12135): isEulaShown : false
I/KnoxUsageLogPro(12135): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12150): MountEmulatedStorage()
E/Zygote  (12150): v2
I/libpersona(12150): KNOX_SDCARD checking this for 10090
I/libpersona(12150): KNOX_SDCARD not a persona
I/SELinux (12150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12150): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12150 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 11102:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12150): TimaSignature is unavailable
D/ActivityThread(12150): Added TimaKeyStore provider
D/ResourcesManager(12150): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12166): MountEmulatedStorage()
I/libpersona(12166): KNOX_SDCARD checking this for 10127
E/Zygote  (12166): v2
I/libpersona(12166): KNOX_SDCARD not a persona
I/SELinux (12166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12166 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 11273:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12166): TimaSignature is unavailable
D/ActivityThread(12166): Added TimaKeyStore provider
D/ResourcesManager(12166): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
D/KeyguardWallpaperUpdator(12166): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12166): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12166): stopCheckCategoryVersion
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/Zygote  (12183): MountEmulatedStorage()
I/libpersona(12183): KNOX_SDCARD checking this for 10136
E/Zygote  (12183): v2
I/libpersona(12183): KNOX_SDCARD not a persona
I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12183): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12183 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 11289:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 564us total 10.674ms
D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
D/ActivityThread(12183): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 257us total 8.458ms
D/ResourcesManager(12183): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 323us total 8.550ms
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,I/WebViewFactory(12183): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12183): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12183): Loading: webviewchromium
,I/LibraryLoader(12183): Time to load native libraries: 3 ms (timestamps 9130-9133)
I/LibraryLoader(12183): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12183): Binding Chromium to main looper Looper (main, tid 1) {26adacff}
,I/LibraryLoader(12183): Expected native library version number "",actual native library version number ""
I/chromium(12183): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11814): 
,I/BrowserStartupController(12183): Initializing chromium process, renderers=0
,I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11814): 
W/art     (12183): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12183): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12183): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
W/AudioManagerAndroid(12183): Requires BLUETOOTH permission
I/chromium(12183): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11814): 
,I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11814): 
,I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11814): 
,I/NSApplication(12183): Starting up...
,I/jxcore-log(11814): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11814): 
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12251): MountEmulatedStorage()
E/Zygote  (12251): v2
I/libpersona(12251): KNOX_SDCARD checking this for 10150
I/libpersona(12251): KNOX_SDCARD not a persona
,I/SELinux (12251): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12251): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12251 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12251): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Killing 11309:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12251): TimaSignature is unavailable
,D/ActivityThread(12251): Added TimaKeyStore provider
,D/ResourcesManager(12251): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12251): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12251): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12251): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12251): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12251): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12251): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12266): MountEmulatedStorage()
E/Zygote  (12266): v2
I/libpersona(12266): KNOX_SDCARD checking this for 10178
I/libpersona(12266): KNOX_SDCARD not a persona
,I/SELinux (12266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12266 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3512): Killing 11324:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12266): TimaSignature is unavailable
,D/ActivityThread(12266): Added TimaKeyStore provider
,D/ResourcesManager(12266): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12266): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12266): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12266): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12266): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12266): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12266): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3512): exchangeData() failure , invalid userId
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12289): MountEmulatedStorage()
I/libpersona(12289): KNOX_SDCARD checking this for 10082
E/Zygote  (12289): v2
I/libpersona(12289): KNOX_SDCARD not a persona
I/SELinux (12289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,E/SELinux (12289): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12289 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12289): TimaSignature is unavailable
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/ActivityThread(12289): Added TimaKeyStore provider
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12305): MountEmulatedStorage()
I/libpersona(12305): KNOX_SDCARD checking this for 1000
E/Zygote  (12305): v2
I/libpersona(12305): KNOX_SDCARD not a persona
,I/SELinux (12305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3512): Killing 11339:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3512): Killing 11444:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/ResourcesManager(12289): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/TimaKeyStoreProvider(12305): TimaSignature is unavailable
,D/ActivityThread(12305): Added TimaKeyStore provider
,D/BadgeProvider(12289): onCreate
D/BadgeProvider(12289): DatabaseHelper
,D/ResourcesManager(12305): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12289): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12289): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12289): sendNotify, [notify] : null
D/BadgeProvider(12289): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12289): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12289): update, [UpdateCount] : 1
,I/ActivityManager( 3512): Killing 11461:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
D/Launcher.Model( 4001): reloadBadges entered.
,W/ActivityManager( 3512): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 4760): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4760): num queued entries: 0
,I/iu.UploadsManager( 4760): num updated entries: 0
I/iu.SyncManager( 4760): NEXT; no task
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  (12072): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,E/Zygote  (12323): MountEmulatedStorage()
I/libpersona(12323): KNOX_SDCARD checking this for 10013
E/Zygote  (12323): v2
I/libpersona(12323): KNOX_SDCARD not a persona
,I/SELinux (12323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12323): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12323 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/jxcore-log(11814): Test app app.js loaded
I/jxcore-log(11814): 
,D/TimaKeyStoreProvider(12323): TimaSignature is unavailable
,D/ActivityThread(12323): Added TimaKeyStore provider
,I/chromium(11814): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ResourcesManager(12323): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/dhcpcd  (12072): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/chromium(11814): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager( 3512): Killing 11479:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4147): Starting #10
,I/Hs20UtilService( 4147): Message received 5007
,D/NearbySettings( 8821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8821): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8821): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8821): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11424): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3512): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3512): do suspend true
,D/WifiP2pService( 3512): InactiveState{ what=143375 }
D/WifiP2pService( 3512): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3512): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3512): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3512): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3512): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3512): Not connected state, yet.
E/WifiStateMachine( 3512): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3512): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3512): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3512): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3512): callSECApiInt - ID [210]
,E/WifiStateMachine( 3512): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3512): updateNetworkInfo()
,D/ConnectivityService( 3512): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3512): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3512): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3512): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4147): Starting #11
,I/Hs20UtilService( 4147): Message received 5007
,E/WifiStateMachine( 3512): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3512): Now, connected state.
E/WifiStateMachine( 3512): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/NearbySettings( 8821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8821): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine( 3512): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3512): evaluateTrafficStatsPolling
,D/ConnectivityService( 3512): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3512): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3512): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3512): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3512): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3512): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3512): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 3512): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3512): REQUEST_POWER_SAVE_ON
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
,D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11424): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4147): Starting #12
,I/Hs20UtilService( 4147): Message received 5007
,D/NearbySettings( 8821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/        ( 2845): QcRouteController
,I/NearbySettings( 8821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8821): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8821): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11424): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4147): Starting #13
,V/        ( 2845): QcRouteController
,D/NearbySettings( 8821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8821): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 4147): Message received 5007
,I/WifiStateMachine( 3512): callSECApi what=220
D/WifiStateMachine( 3512): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11424): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3512): route cmd failed: 
W/NetworkManagementService( 3512): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3512): '
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3512): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3512): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3512): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3512): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3512): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3512): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3512): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3512): LTETest block dns file not exists
,D/ConnectivityService( 3512): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3512): updateNetworkInfo()
E/ConnectivityService( 3512): updateNetworkInfo()
D/ConnectivityService( 3512): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 3512): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3512): rematching NetworkAgentInfo [WIFI () - 503]
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/ConnectivityService( 3512):    accepting network in place of null
,D/TelephonyNetworkFactory( 3985): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3512): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3512): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3512): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3512): MasterInitialState.processMessage what=3
I/System.out( 3512): (HTTPLog)-Static: isSBSettingEnabled false
D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3512): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
D/SmartBondingService( 3512): getSBEnabled() enabled =false
,V/NetworkStats( 3512): updateIfacesLocked()
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
V/NetworkStats( 3512): performPollLocked(flags=0x1)
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/NetworkStatsFactory( 3512): UpdateStatsForKnox
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
V/NetworkStats( 3512): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
V/NetworkStats( 3512): performPollLocked() took 6ms
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,D/PowerManagerService( 3512): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3512
,D/EntConnectivity( 3512): Not allowed due to - mEnabled false
,D/ConnectivityService( 3512): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524290
,D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
D/NtpTrustedTime( 3512): currentTimeMillis() cache hit
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/System.out( 3512): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 07:36:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453102597221], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453102597200]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3512): Validated
D/ConnectivityService( 3512): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3512): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3512): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3512): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 4760): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3512): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3512): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3512): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3512): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3512): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3512): getSBEnabled() enabled =false
,D/SmartBondingService( 3512): getSBEnabled() enabled =false
,D/SmartBondingService( 3512): getSBEnabled() enabled =false
,D/SmartBondingService( 3512): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6293): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6293): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3512): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor(11951): type=WIFI subType= reason=null isConnected=true
W/ResourceType( 5384): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5384): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11928): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11928): sales region : global
I/PCWCLIENTTRACE_PushUtil(11928): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11928): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12007): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12007): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3512): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3512): mCursor = null
,I/FOTA_Client(12025): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12025): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12025): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12041): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 08:36:37 GMT+01:00 2016
,I/KLMS-2.4.521: (12041): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12041): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12041): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12041): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12041): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12041): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12041): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(12057): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12041): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12041): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12041): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12041): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12041): KLMSIntentService(): onDestroy()
,E/SPPClientService(12099): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11233): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11233): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11233): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11233): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11233): [OR] == isSIMCardReady false ==
,I/SA      (11233): [SCU] == networkStateCheck == true
,I/SA      (11233): [DM] getCountryCodeFromCSC : PL
I/SA      (11233): isChinaCountryCode : false
I/SA      (11233): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11233): [OR] == networkStateCheck true ==
,I/SA      (11233): [OR] GetMyCountryZoneTask
,I/SA      (11233): [OR] onReceive END
,I/SA      (11233): [SRS] prepareGetMyCountryZone
,I/SA      (11233): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11233): [SSP] query invoked
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11233): [TPMU] GetMccFromDB : null
I/SA      (11233): [SCU] getMccFromPreferece mcc = 260
I/SA      (11233): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12119): Other Intent
,D/accuweather( 5289): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5289): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5289): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5289): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5289): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5289): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5289): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12135): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12135): premStatus:2
,I/KnoxUsageLogPro(12135): isEulaShown : false
,I/KnoxUsageLogPro(12135): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12166): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12166): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12166): stopCheckCategoryVersion
,D/QuickConnect(12251): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12251): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12251): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,D/RCPManagerService( 3512): exchangeData() failure , invalid userId
,I/iu.Environment( 4760): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4760): num queued entries: 0
,I/iu.UploadsManager( 4760): num updated entries: 0
,I/iu.SyncManager( 4760): NEXT; no task
,D/WaitQueueForNetworkActivate(12323): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12323): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3512): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 3512): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/hcjo    (12323): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12323): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12323): exit::IDLE
D/InitializeManagerStateMachine(12323): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12323): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12323): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12323): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12323): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12323): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12323): entry::SUCCESS
D/hcjo    (12323): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12323): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12323): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12323): exit::SUCCESS
D/InitializeManagerStateMachine(12323): entry::IDLE
,I/SA      (11233): [RC New] Execute method=[GET] start
,I/SA      (11233): [RC New] Security=[true]
,I/System.out(11233): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11233): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11233): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11233): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/SA      (11233): [RC New] [v2liruge] api execute + 695
,I/SA      (11233): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11233): AsyncTask #1 calls detatch()
,I/SA      (11233): [TPMU] getNetworkMcc : 
,I/SA      (11233): [SCU] saveMccToPreferece Start
,I/SA      (11233): [SCU] RegionMCC : 260
,I/SA      (11233): [SSP] query invoked
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11814): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11814): BLE advertisement is supported
I/jxcore-log(11814): 
,I/SA      (11233): [TPMU] GetMccFromDB : null
I/SA      (11233): [SCU] getMccFromPreferece mcc = 260
I/SA      (11233): [SCU] saveMccToPreferece End
,I/SA      (11233): [RC New] executeRequest [v2liruge] end. 763
I/SA      (11233): [RC New] Execute end
,I/SA      (11233): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11233): [OR] GetMyCountryZoneTask Success
,W/ProcessCpuTracker( 3512): Skipping unknown process pid 12431,
,I/dhcpcd  (12072): wlan0: sending IPv6 Router Solicitation,
,I/WifiStateMachine( 3512): REQUEST_POWER_SAVE_ON
,D/WearableService( 4624): callingUid 10014, callindPid: 4624
,E/WifiStateMachine( 3512): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/ResourcesManager(11951): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11951): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11951): Conditions not met for autocaching.
I/MusicLeanback(11951): Stop autocaching.
,D/WearableClient(11951): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11951): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11951): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11951): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11951): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11951): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11951): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@371ebad5 that was originally bound here
E/ActivityThread(11951): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@371ebad5 that was originally bound here
E/ActivityThread(11951): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11951): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11951): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11951): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11951): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11951): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11951): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11951): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11951): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11951): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11951): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11951): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11951): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11951): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11951): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11951): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11951): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11951): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11951): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11951): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11951): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11951): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11951): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11951): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,D/PowerManagerService( 3512): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3512) eventTime = 143478
,D/PowerManagerService( 3512): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3512 (0x0)
,D/PowerManagerService( 3512): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3512, ws=WorkSource{10060}) (elapsedTime=3481)
,D/SSRM:n  ( 3512): SIOP:: AP = 280, PST = 262, CUR = 57
,I/GAV4    (12183): Thread[GAThread,5,main]: No campaign data found.
,I/art     ( 3512): Explicit concurrent mark sweep GC freed 52924(3MB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 49MB/65MB, paused 2.029ms total 160.077ms
,I/PowerManagerService( 3512): [PWL] Off : 50s ago
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:-83, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:97
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3512): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11928): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11928): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11928): ================================================
,I/CSTORAGE(11928):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11928): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11928): [GetString-S]
,E/art     (11928): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11928): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11928): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11928): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11928): sales region : global
I/PCWCLIENTTRACE_PushUtil(11928): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11928): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12072): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (12072): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12072): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12323): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12323): exit::IDLE
D/PreloadUpdateManagerStateMachine(12323): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12323): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12323): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine(12323): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12323): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12323): entry::IDLE
,D/SSRM:n  ( 3512): SIOP:: AP = 260, PST = 261, CUR = -83
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3512): waitForAlarm result :8
,E/Watchdog( 3512): !@Sync 5
,D/SSRM:n  ( 3512): SIOP:: AP = 250, PST = 257, CUR = 10
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3512): [PWL] Off : 75s ago
,I/art     ( 4624): Explicit concurrent mark sweep GC freed 61643(3MB) AllocSpace objects, 31(1312KB) LOS objects, 34% free, 30MB/46MB, paused 1.884ms total 77.235ms
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 255, CUR = 43
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4624): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 254, CUR = 52
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3512): !@Sync 6
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 253, CUR = 53
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3512): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3512): [PWL] Off : 105s ago
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 251, CUR = 50
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 250, CUR = 47
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3512): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3512): waitForAlarm result :8
,E/Watchdog( 3512): !@Sync 7
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 250, CUR = 44
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3512): [PWL] Off : 140s ago
,D/SSRM:n  ( 3512): SIOP:: AP = 240, PST = 249, CUR = 43
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3512): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 245, CUR = 40
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3512): !@Sync 8
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 243, CUR = 39
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3512): stay LED for fully charged
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 242, CUR = 38
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3512): [PWL] Off : 180s ago
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 240, CUR = 35
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3512): !@Sync 9
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 238, CUR = 35
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3512): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
,I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/BatteryService( 3512): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3512): SIOP:: AP = 230, PST = 236, CUR = 34,
,I/jxcore-log(11814): --= Surplus to requirements =--
I/jxcore-log(11814): 
I/jxcore-log(11814): ****TEST TOOK:  ms ****
I/jxcore-log(11814): 
I/jxcore-log(11814): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11814): 
,D/AndroidRuntime(12697): 
D/AndroidRuntime(12697): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BatteryService( 3512): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3512): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3512): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3512): stay LED for fully charged
,D/BatteryService( 3512): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3512): Plugged
I/MotionRecognitionService( 3512): setPowerConnected  = true
,D/AndroidRuntime(12697): CheckJNI is OFF
,D/AndroidRuntime(12697): readGMSProperty: start
D/AndroidRuntime(12697): readGMSProperty: already setted!!
,D/AndroidRuntime(12697): readGMSProperty: end
D/AndroidRuntime(12697): addProductProperty: start
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5601): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5601): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/AffinityControl(12697): AffinityControl: registerfunction enter
,D/AndroidRuntime(12697): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3512): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3512): START PACKAGE DELETE: observer{336440227}
D/PackageManager( 3512): pkg{<packageName>}
D/PackageManager( 3512): user{0}
D/PackageManager( 3512): caller{2000}
D/PackageManager( 3512): flags{3}
D/PersonaManagerService( 3512): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3512): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3512): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3512): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3512): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3512): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3512): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3512): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3512): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3512): !@killApplicatoin: 10582, uninstall pkg
I/ActivityManager( 3512): Force stopping com.test.thalitest appid=10582 user=-1: uninstall pkg
,I/ActivityManager( 3512): Killing 11814:com.test.thalitest/u0a582 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3512):   Force finishing activity ActivityRecord{6ffb2eb u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3512): mDVFSHelper.acquire()
,W/PackageSettings( 3512): Skipping PackageSetting{32215e5e com.example.hello/10563} due to missing metadata
,D/WifiService( 3512): Client connection lost with reason: 4
,I/WindowState( 3512): WIN DEATH: Window{1aede289 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/ActivityManager( 3512): Force stopping com.test.thalitest appid=10582 user=0: pkg removed
,I/ActivityManager( 3512):   Force finishing activity ActivityRecord{6ffb2eb u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3512): Duplicate finish request for ActivityRecord{6ffb2eb u0 com.test.thalitest/.MainActivity t26 f}
,D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6293): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/art     ( 9093): Explicit concurrent mark sweep GC freed 23687(1404KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.159ms total 49.962ms
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 4039): Explicit concurrent mark sweep GC freed 30985(1918KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 2.956ms total 63.315ms
,I/InputReader( 3512): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4471): mOCRHelper is null
,W/GeofencerStateMachine( 4624): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/art     ( 4760): Explicit concurrent mark sweep GC freed 27138(1547KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.712ms total 101.481ms
,I/DBG_DM  ( 6293): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6293): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/LWLocationManager(11499): getDeviceLocationId :  id = -100
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 5384): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5384): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/LocationWidgetApplication(11499): getLastUiLocationId() : mLastUiLocationId = -100
,E/Zygote  (12716): MountEmulatedStorage()
E/Zygote  (12716): v2
I/libpersona(12716): KNOX_SDCARD checking this for 10063
I/libpersona(12716): KNOX_SDCARD not a persona
,I/ActivityManager( 3512): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12716 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SELinux (12716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/EnterpriseDeviceManagerService( 3512): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3512): Admin package name: com.google.android.gms
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12716): TimaSignature is unavailable
,D/SecContentProvider2( 3512): uri = 14 selection = getSealedState
D/ActivityThread(12716): Added TimaKeyStore provider
D/SecContentProvider2( 3512): mCursor = null
,D/ApplicationPolicy( 3512): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3512): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/art     ( 3512): Explicit concurrent mark sweep GC freed 28442(2MB) AllocSpace objects, 52(832KB) LOS objects, 24% free, 49MB/65MB, paused 3.970ms total 173.550ms
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3512): WaitForGcToComplete blocked for 146.717ms for cause Explicit
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/DBG_DM  ( 6293): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6293): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6293): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
I/DBG_DM  ( 6293): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6293): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3512): post active user change for 0
D/KnoxTimeoutHandler( 3512): postActiveUserChange for user 0
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/DBG_DM  ( 6293): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(12716): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/StatusBarManagerService( 3512): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/PointerIcon( 3512): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3512): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3512): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3512): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,V/ActivityThread( 6293): updateVisibility : ActivityRecord{3431107c token=android.os.BinderProxy@19fc59c9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 3512): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12716): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12716): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12716): packagename:com.test.thalitest
D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Books/Books.apk
,I/KLMS-2.4.521: (12041): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 08:39:13 GMT+01:00 2016
,D/SecContentProvider2( 3512): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3512): mCursor = null
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/InputMethodManagerService( 3512): Got RemoteException sending setActive(false) notification to pid 11814 uid 10582
,W/ContextImpl( 3512): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (12041): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3512): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3512): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/KLMS-2.4.521: (12041): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12041): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/RCPManager(12135):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3512):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3512): queryAllProviders():  providerCallBack is not register for 0
,I/KLMS-2.4.521: (12041): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (12041): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12737): MountEmulatedStorage()
E/Zygote  (12737): v2
I/libpersona(12737): KNOX_SDCARD checking this for 10106
I/libpersona(12737): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (12041): KLMSIntentService(): PACKAGE_REMOVED
I/SELinux (12737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12737 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (12737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 3964): empty dynamic service
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12041): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12041): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/Timeline( 6293): Timeline: Activity_idle id: android.os.BinderProxy@19fc59c9 time:296464
E/Zygote  (12752): MountEmulatedStorage()
E/Zygote  (12752): v2
I/libpersona(12752): KNOX_SDCARD checking this for 10050
I/libpersona(12752): KNOX_SDCARD not a persona
,I/SELinux (12752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3512): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12752 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/SELinux (12752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager(11499): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12737): TimaSignature is unavailable
,D/ActivityThread(12737): Added TimaKeyStore provider
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  (12768): MountEmulatedStorage()
E/Zygote  (12768): v2
I/libpersona(12768): KNOX_SDCARD checking this for 10101
I/libpersona(12768): KNOX_SDCARD not a persona
,I/SELinux (12768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12768 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12768): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/art     ( 3512): Explicit concurrent mark sweep GC freed 7914(388KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 5.747ms total 218.168ms
,D/TimaKeyStoreProvider(12752): TimaSignature is unavailable
,D/ActivityThread(12752): Added TimaKeyStore provider
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11499): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11499): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11499): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ActivityManager( 3512): mDVFSHelper.release()
I/Timeline( 3512): Timeline: Activity_windows_visible id: ActivityRecord{3813711b u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:296530
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/TimaKeyStoreProvider(12768): TimaSignature is unavailable
,D/ActivityThread(12768): Added TimaKeyStore provider
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/PackageManager( 3512): delete codoeFile: 
,I/KLMS-2.4.521: (12041): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(11499): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/AASAUninstall( 3512):  com.test.thalitest not target!
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(12752): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  (12783): MountEmulatedStorage()
I/libpersona(12783): KNOX_SDCARD checking this for 10183
E/Zygote  (12783): v2
I/libpersona(12783): KNOX_SDCARD not a persona
I/SELinux (12783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/PackageManager( 3512): result of delete: 1{336440227}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/SELinux (12783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3512): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12783 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,W/ResourcesManager(12752): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager(12737): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/ResourcesManager(12752): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12752): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12752): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12752): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12752): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12752): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12752): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (12041): KLMSIntentService(): onDestroy()
,D/AndroidRuntime(12697): Shutting down VM
,I/ActivityManager( 3512): Killing 11516:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/elm:14491(12737): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12737): ELMEngine.ELMEngine( context ).
D/elm:14491(12737): MDMBridge.setEnterpriseBridge()
,D/TimaKeyStoreProvider(12783): TimaSignature is unavailable
,D/ResourcesManager(11499): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ActivityThread(12783): Added TimaKeyStore provider
,D/ResourcesManager(12768): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14491(12737): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12737): ElmAgentService : onCreate()
,D/elm:14491(12737): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(11499): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/elm:14491(12737): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12737): MDMBridge.getInstance()
D/elm:14491(12737): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491(12737): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11499): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/Zygote  (12800): MountEmulatedStorage()
E/Zygote  (12800): v2
I/libpersona(12800): KNOX_SDCARD checking this for 10019
I/libpersona(12800): KNOX_SDCARD not a persona
,I/SELinux (12800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12800): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12800 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/elm:14491(12737): ElmAgentService : onDestroy().
,I/ActivityManager( 3512): Killing 11532:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 974us total 22.741ms
,E/SQLiteLog(12783): (284) automatic index on shooting_modes(title_id)
,D/DocsApplication(12768): Installing DEX configuration.
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 342us total 19.239ms
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/TimaKeyStoreProvider(12800): TimaSignature is unavailable
,D/ActivityThread(12800): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 578us total 10.664ms
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ResourceType( 3512): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (12820): MountEmulatedStorage()
E/Zygote  (12820): v2
I/libpersona(12820): KNOX_SDCARD checking this for 10190
I/libpersona(12820): KNOX_SDCARD not a persona
,I/SELinux (12820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux (12820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3512): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12820 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (12820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PackageManager( 3512): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/DexInstaller(12768): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/PackageInfoHelper(12768): Provided clientMode=RELEASE, packageInfo=PackageInfo{16060874 com.google.android.apps.docs}
,D/TAG     (12768): onCreate()
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/CrossAppStateProvider(12768): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/TimaKeyStoreProvider(12820): TimaSignature is unavailable
,D/ActivityThread(12820): Added TimaKeyStore provider
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(11499): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 3512): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3512): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3512): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12800): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/ActivityManager( 3512): Killing 11499:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(12820): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/TapandpayWidget:TanpandpayAppWidgetProvider(12820): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12820): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3512): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/TapandpayWidget:Utils(12820): Clear T&P info.
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3512): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12800): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12800): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12800): onReceive() : package name is not s health. Return !!!
W/Resources( 3512): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TapandpayWidget:TanpandpayAppWidgetProvider(12820): Widget is not attached.
,D/UsbSettingsManager( 3512): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3512): onPackageRemoved : com.test.thalitest
,D/RCPManagerService( 3512): PackageReceiver onReceive()
I/HarmonyEASService( 3512): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/ActivityManager( 3512): Killing 10834:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/KnoxMUMContainerPolicy( 3512): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3512): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3512): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3512): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3512): uID is 10582
V/EnterpriseBillingPolicy( 3512): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3512): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3512): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3512): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3512): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3512): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3512): getBillingProfileForVpnEngine - end - null
,I/ActivityManager( 3512): Killing 11705:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/KnoxTimeoutHandler( 3512): handleActiveUserChange for user 0
,D/TaskPersister( 3512): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3512): removeObsoleteFile: deleting file=24_task.xml
,D/NearbySource(12752): Nearby Source Create!
,D/PackageBroadcastService( 4760): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4760): Clearing selected account for com.test.thalitest
,D/NearbyContext(12752): Nearby Context Create!
,D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ChimeraCfgMgr( 4760): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4760): Module APK com.google.android.play.games already loaded
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/PanelView( 3694): There is/are notification(s) 
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
,I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
,I/PCWCLIENTTRACE_PushUtil(11928): SPPPushClient is installed : true
D/ChimeraCfgMgr( 4760): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4760): Module APK com.google.android.play.games already loaded
,I/PCWCLIENTTRACE_PushUtil(11928): sales region : global
I/PCWCLIENTTRACE_PushUtil(11928): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11928): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12752): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12752): Samsung link source created
,I/LocationSettingsChecker( 4760): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4760): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Zygote  (12843): MountEmulatedStorage()
E/Zygote  (12843): v2
I/libpersona(12843): KNOX_SDCARD checking this for 10035
I/libpersona(12843): KNOX_SDCARD not a persona
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/SQLiteLog( 4760): (10) POSIX Error : 9 SQLite Error : 3850
I/ActivityManager( 3512): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12843 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SQLiteLog( 4760): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SELinux (12843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/SQLiteDatabase( 4760): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4760): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4760): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4760): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4760): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4760): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4760): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4760): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4760): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4760): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 4760): Runtime exception while performing operation
E/ClearPendingStateOp( 4760): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4760): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4760): 	at android.con,tent.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 4760): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4760): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 4760): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4760): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4760): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4760): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4760): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4760): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4760): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4760): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4760): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4760): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4760): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4760): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4760): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 4760): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4760): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4760): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4760): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4760): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4760): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4760): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 4760): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4760): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4760): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4760): 	at java.lang.Thread.run(Thread.java:818)
I/SELinux (12843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/SQLiteOpenHelper( 4760): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4760): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4760): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 4760): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 4760): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 4760): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4760): Process: com.google.android.gms, PID: 4760
E/AndroidRuntime( 4760): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4760): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4760): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4760): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4760): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4760): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4760): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4760): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4760): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4760): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/ApplicationPolicy( 3512): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/SQLiteLog( 4760): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 4760): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4760): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4760): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4760): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4760): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4760): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4760): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4760): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/WifiDisplayAdapter( 3512): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/PhenotypeInitializer( 4760): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 4760): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 4760): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 4760): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4760): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 4760): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 4760): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4760): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4760): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4760): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 4760): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider(12843): TimaSignature is unavailable
E/DropBoxManagerService( 3512): Can't write: system_app_wtf
E/DropBoxManagerService( 3512): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3512): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3512): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3512): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3512): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3512): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3512): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3512): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3512): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3512): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3512): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3512): 	... 5 more
D/ActivityThread(12843): Added TimaKeyStore provider
E/DropBoxManagerService( 3512): Can't write: system_app_crash
E/DropBoxManagerService( 3512): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3512): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3512): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3512): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3512): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3512): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3512): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3512): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3512): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3512): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3512): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3512): 	... 5 more
E/NetworkScheduler.SchedulerReceiver( 4624): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4624): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/SQLiteLog( 4760): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4760): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 4760): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
I/Process ( 4760): Sending signal. PID: 4760 SIG: 9
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3512): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3512): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3512): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3512): displayNotification : [0ah,00h,01h]
D/ContactProvider(12752): getAllContactInfoList Start
,D/UsbHostManager( 3512): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3512): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3512): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityThread(11903): Failed to find provider info for com.facebook.appmanager.installrecord
,D/UsbHostManager( 3512): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3512): displayNotification : [09h,00h,00h]
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12843): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/MtpClient(12752): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12752): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/Zygote  (12870): MountEmulatedStorage()
E/Zygote  (12870): v2
I/libpersona(12870): KNOX_SDCARD checking this for 10031
I/libpersona(12870): KNOX_SDCARD not a persona
,I/SELinux (12870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/SharedPreferencesImpl(12752): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/UsbHostManager( 3512): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3512): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/SELinux (12870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12870): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12870 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
I/EventHub( 3512): Removing device '/dev/input/event10' due to inotify event
,D/ConnectivityService( 3512): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d15cb5a)
,D/ConnectivityService( 3512): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 3512): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/EventHub( 3512): Removing device '/dev/input/event7' due to inotify event
,D/TimaKeyStoreProvider(12870): TimaSignature is unavailable
E/Zygote  (12890): MountEmulatedStorage()
I/libpersona(12890): KNOX_SDCARD checking this for 10052
E/Zygote  (12890): v2
I/libpersona(12890): KNOX_SDCARD not a persona
,I/SELinux (12890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ActivityThread(12870): Added TimaKeyStore provider
,I/SELinux (12890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12890): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3512): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12890 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 3512): Process com.google.android.gms (pid 4760)(adj 0) has died(272,1194)
,W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
,W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10998ms
,W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10997ms
W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
,W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20996ms
,W/ActivityManager( 3512): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20994ms
,I/EventHub( 3512): Removing device '/dev/input/event8' due to inotify event
,I/FeatureConfig(12843): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/TimaKeyStoreProvider(12890): TimaSignature is unavailable
,D/ActivityThread(12890): Added TimaKeyStore provider
,I/EventHub( 3512): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12870): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/EventHub( 3512): Removing device '/dev/input/event11' due to inotify event
,I/ActivityManager( 3512): Killing 12289:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(12843): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/EventHub( 3512): Removing device '/dev/input/event12' due to inotify event
,W/ResourcesManager(12843): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12843): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12843): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3512): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12890): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/EventHub( 3512): Removing device '/dev/input/event13' due to inotify event
,W/ResourcesManager(12890): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12890): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12890): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12843): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12843): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager(12843): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
E/Zygote  (12907): MountEmulatedStorage()
I/libpersona(12907): KNOX_SDCARD checking this for 10036
E/Zygote  (12907): v2
I/libpersona(12907): KNOX_SDCARD not a persona
,W/ResourcesManager(12843): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.,
,I/SELinux (12907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27,
,W/ResourcesManager(12843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
,W/ResourcesManager(12843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager(12843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/ResourcesManager(12843): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/SELinux (12907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/EventHub( 3512): Removing device '/dev/input/event14' due to inotify event,
E/SELinux (12907): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/SQLiteLog(12768): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,I/ActivityManager( 3512): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12907 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/SQLiteDatabase(12768): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12768): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12768): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12768): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12768): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12768): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12768): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12768): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12768): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12768): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12768): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12768): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12768): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12768): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12768): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12768): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12768): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12768): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12768): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12768): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12768): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12768): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12768): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12768): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 3512): Killing 8821:com.android.settings/1000 (adj 13): bgCount ##31
E/SQLiteOpenHelper(12768): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12768): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12768): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12768): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12768): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12768): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLite,OpenHelper(12768): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12768): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12768): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12768): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12768): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12768): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12768): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12768): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12768): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12768): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12768): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12768): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12768): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12768): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12768): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12768): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12768): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12768): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12768): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12768): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12768): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12768): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12768): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ResourcesManager(12843): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/SQLiteOpenHelper(12768): Opened ClientFlag.db in read-only mode
,D/ResourcesManager(12843): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ContactProvider(12752): getAllContactInfoList End
D/TimaKeyStoreProvider(12907): TimaSignature is unavailable
,I/syncContacts(12752): thread: 1753, sync time = 613
,D/ActivityThread(12907): Added TimaKeyStore provider
,D/ResourcesManager(12843): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12843): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12843): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiService( 3512): Client connection lost with reason: 4
,E/SQLiteLog(12768): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12768): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12768): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12768): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12768): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12768): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12768): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12768): 	at aFp.run(AbstractDatabaseInstance.java:471)
,E/AndroidRuntime(12768): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12768): Process: com.google.android.apps.docs, PID: 12768
E/AndroidRuntime(12768): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12768): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12768): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12768): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12768): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12768): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12768): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12768): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12768): 	at aFp.run(AbstractDatabaseInstance.java:471)

```
