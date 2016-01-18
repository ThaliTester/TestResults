#### Test 563583788793eb6_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AndroidRuntime(11700): 
D/AndroidRuntime(11700): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11700): CheckJNI is OFF
D/AndroidRuntime(11700): readGMSProperty: start
D/AndroidRuntime(11700): readGMSProperty: already setted!!
D/AndroidRuntime(11700): readGMSProperty: end
D/AndroidRuntime(11700): addProductProperty: start
E/AffinityControl(11700): AffinityControl: registerfunction enter
D/AndroidRuntime(11700): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3515): inState():  stateMachine is null !!
I/PersonaManagerService( 3515): PersonaId don't exist
I/ActivityManager( 3515): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager( 3515): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3515): mDVFSHelper.acquire()
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/Zygote  (11722): MountEmulatedStorage()
I/libpersona(11722): KNOX_SDCARD checking this for 10586
E/Zygote  (11722): v2
I/libpersona(11722): KNOX_SDCARD not a persona
I/SELinux (11722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11722): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11722 uid=10586 gids={50586, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime(11700): Shutting down VM
D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11722): TimaSignature is unavailable
D/ActivityThread(11722): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11722): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6227): updateVisibility : ActivityRecord{2e8b2c9e token=android.os.BinderProxy@2a6988a3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory(11722): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11722): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11722): Loading: webviewchromium
,I/LibraryLoader(11722): Time to load native libraries: 5 ms (timestamps 7372-7377)
I/LibraryLoader(11722): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11722): Binding Chromium to main looper Looper (main, tid 1) {140c7c29}
,I/LibraryLoader(11722): Expected native library version number "",actual native library version number ""
,I/chromium(11722): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11722): Initializing chromium process, renderers=0
,W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11722): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11722): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11722): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11722): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11722): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11722): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11722): CordovaWebView is running on device made by: samsung
,W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11722): performCreate Call secproduct feature valuefalse
D/Activity(11722): performCreate Call debug elastic valuetrue
W/ActivityManager( 3515): Activity pause timeout for ActivityRecord{26896ff5 u0 com.test.thalitest/.MainActivity t26}
D/OpenGLRenderer(11722): Render dirty regions requested: true
,D/ActivityManager( 3515): post active user change for 0
D/KnoxTimeoutHandler( 3515): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3515): handleActiveUserChange for user 0
,V/ActivityThread(11722): updateVisibility : ActivityRecord{cdfc199 token=android.os.BinderProxy@147bd944 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11722): Initialized EGL, version 1.4
,I/OpenGLRenderer(11722): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1279688432 
,D/OpenGLRenderer(11722): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11722): Enabling debug mode 0
,D/mali_winsys(11722): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3515): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3515): mDVFSHelper.release()
I/Timeline( 3515): Timeline: Activity_windows_visible id: ActivityRecord{26896ff5 u0 com.test.thalitest/.MainActivity t26} time:137731
,W/IInputConnectionWrapper(11722): showStatusIcon on inactive InputConnection
,I/Timeline(11722): Timeline: Activity_idle id: android.os.BinderProxy@147bd944 time:137733
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/JsMessageQueue(11722): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11722): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11722): 
,D/jxcore_app_log(11722): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361619200
,I/chromium(11722): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11722): Initializing JXcore engine
W/jxcore-log(11722): JXcore engine is ready
,E/auditd  ( 4622): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3515): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3515): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11722): Starting JXcore engine
,W/jxcore-log(11722): Platform android
W/jxcore-log(11722): 
W/jxcore-log(11722): Process ARCH arm
W/jxcore-log(11722): 
I/jxcore-log(11722): JXcore Cordova bridge is ready!
I/jxcore-log(11722): 
W/jxcore-log(11722): JXcore engine is started
I/jxcore-log(11722): Toggling radios to true
I/jxcore-log(11722): 
D/BluetoothAdapter(11722): enable()
D/BluetoothAdapter(11722): enable(): BT is already enabled..!
D/WifiService( 3515): New client listening to asynchronous messages
I/WifiManager(11722): packageName : com.test.thalitest
D/SecContentProvider( 3515): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3515): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3515): mCursor = null
D/WifiService( 3515): setWifiEnabled: true pid=11722, uid=10586
E/WifiService( 3515): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3515): Permission Denial: getCurrentUser() from pid=11722, uid=10586 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3515): Failed getting userId using ActivityManagerNative
W/WifiService( 3515): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11722, uid=10586 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3515): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3515): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3515): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3515): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3515): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3515): name = wifi_on
I/WifiService( 3515): disconnect: pid=11722, uid=10586
I/wpa_supplicant( 3827): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log(11722): Radios toggled
I/jxcore-log(11722): 
I/jxcore-log(11722): My device name is: samsung-SM-N910C
I/jxcore-log(11722): 
I/wpa_supplicant( 3827): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3827): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3515): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3827): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3827): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3827): Disconnected - do not scan
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3515): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3515): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3515): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3515): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3515): do suspend true
D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
D/CommandListener( 2845): Clearing all IP addresses on wlan0
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/WifiStateMachine( 3515): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3515): updateNetworkInfo()
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3515): updateNetworkInfo()
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
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
I/Hs20UtilService( 4078): Starting #8
I/Hs20UtilService( 4078): Message received 5007
E/WifiStateMachine( 3515): Start Disconnecting Watchdog 1
I/wpa_supplicant( 3827): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3827): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3827): First Scan Start
E/WifiStateMachine( 3515): ConnectModeState: Network connection lost 
I/wpa_supplicant( 3827): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3515): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3515): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3515): do suspend true
D/NearbySettings( 8646): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8646): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8646): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 8646): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8646): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiService( 3515): New client listening to asynchronous messages
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8646): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8646): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11385): NETWORK_STATE_CHANGED_ACTION
D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/ConnectivityService( 3515): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3515): Not allowed due to - mEnabled false
E/WifiStateMachine( 3515): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3515): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
D/WifiStateMachine( 3515): updateConfiguredNetworkExpiration - currTime: 1453134314295
D/WifiStateMachine( 3515): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker( 3515): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 6742): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3515): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3515): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 3975): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3515): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3515): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3515): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/EntConnectivity( 3515): Not allowed due to - mEnabled false
D/ConnectivityService( 3515): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering( 3515): MasterInitialState.processMessage what=3
D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
V/NetworkStats( 3515): updateIfacesLocked()
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
V/NetworkStats( 3515): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3515): UpdateStatsForKnox
I/Hs20UtilService( 4078): Starting #9
I/Hs20UtilService( 4078): Message received 5007
V/NetworkStats( 3515): performPollLocked() took 3ms
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
V/NetworkStats( 3515): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
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
D/NearbySettings( 8646): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8646): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8646): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8646): MountReceiver.mPrefHandler - 7002
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
I/SignOutReceiver(11385): NETWORK_STATE_CHANGED_ACTION
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3975): FileWriteThread : threadType = 3
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
,I/DBG_DM  ( 6227): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6227): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11824): MountEmulatedStorage()
I/libpersona(11824): KNOX_SDCARD checking this for 10110
E/Zygote  (11824): v2
I/libpersona(11824): KNOX_SDCARD not a persona
,I/SELinux (11824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3515): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11824 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11824): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11824): TimaSignature is unavailable
,D/ActivityThread(11824): Added TimaKeyStore provider
,D/ResourcesManager(11824): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11824): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11824): not using cross-dex optimization: ART in use
,I/art     (11824): Thread[1,tid=11824,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11824): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11824): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11824): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11824): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11824): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11824): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11824): loading pre-built fallback odex files
V/MultiDexClassLoader(11824): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11824): released odex store lock
D/DexLibLoader(11824): DexLibLoader.loadAll took 16 ms
,W/ca      (11824): Verify
,W/LightSharedPreferencesImpl(11824): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11824): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11824): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11824): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11824): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11824): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11824): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11824): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11824): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11824): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11824): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11824): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11824): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11824): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11824): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11824): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11824): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11824): 	... 10 more
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11849): MountEmulatedStorage()
E/Zygote  (11849): v2
I/libpersona(11849): KNOX_SDCARD checking this for 1000
I/libpersona(11849): KNOX_SDCARD not a persona
,I/SELinux (11849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 10978:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11824): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11824): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11849): TimaSignature is unavailable
D/ActivityThread(11849): Added TimaKeyStore provider
,D/ResourcesManager(11849): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11849): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11849): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11849): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11849): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11849): sales region : global
I/PCWCLIENTTRACE_PushUtil(11849): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11849): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11849): noConnectivity : true
,W/appmanager(:<default>):QuickExperimentControllerImpl(11824): Exposure of experiment com.facebook.common.network.l@34080494 occurred when no user was logged in
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11872): MountEmulatedStorage()
E/Zygote  (11872): v2
I/libpersona(11872): KNOX_SDCARD checking this for 10135
I/libpersona(11872): KNOX_SDCARD not a persona
I/SELinux (11872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11872): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11872 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 10993:com.policydm/1000 (adj 15): bgCount ##31
,W/BroadcastQueue( 3515): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{367389af u0 ReceiverList{38e79d8e 11824 com.facebook.appmanager/10110/u0 remote:2d182989}}
,W/BroadcastQueue( 3515): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{367389af u0 ReceiverList{38e79d8e 11824 com.facebook.appmanager/10110/u0 remote:2d182989}}
,D/TimaKeyStoreProvider(11872): TimaSignature is unavailable
,D/ActivityThread(11872): Added TimaKeyStore provider
,D/ResourcesManager(11872): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3515): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2e2fec54 u0 ReceiverList{1404ffa7 11824 com.facebook.appmanager/10110/u0 remote:3acdd066}}
,I/MusicStore(11872): Database version: 104
,D/ResourcesManager(11872): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11872): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11872): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11872): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11872): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11872): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c488bed: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11872): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11872): GMSCore installation verified
,I/ConfigStore(11872): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11872): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11824): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11824): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11872): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11872): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11824): Exposure of experiment com.facebook.imagepipeline.a.g@3f7e1cb2 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11824): Exposure of experiment com.facebook.imagepipeline.a.d@18bb7d5f occurred when no user was logged in
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3515): getStreamVolume 3 index 0
,I/MediaRouter(11872): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3827): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 3827): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3827): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3827): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3515): [1,453,134,315,350 ms] noteScanEnd no scan source
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/art     (11824): Explicit concurrent mark sweep GC freed 47161(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 778us total 24.178ms
,W/appmanager(:<default>):m(11824): No feature status reporters found; is this dead code?
,E/WifiStateMachine( 3515): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@351eca6c sup_state=SCANNING debouncing=false
,E/Zygote  (11908): MountEmulatedStorage()
,E/Zygote  (11908): v2
I/libpersona(11908): KNOX_SDCARD checking this for 10002
I/libpersona(11908): KNOX_SDCARD not a persona
,I/ActivityManager( 3515): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11908 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3515): setDetailed state send new extra info
E/SELinux (11908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11872): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11908): TimaSignature is unavailable
,D/ActivityThread(11908): Added TimaKeyStore provider
I/ActivityManager( 3515): Killing 11008:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/ResourcesManager(11908): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 3827): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/ActivityManager( 3515): Killing 11045:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,I/wpa_supplicant( 3827): Associated with C0.AA.48
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3515): setDetailed state send new extra info"NG700"
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,I/wpa_supplicant( 3827): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  (11928): MountEmulatedStorage()
I/libpersona(11928): KNOX_SDCARD checking this for 1000
E/Zygote  (11928): v2
I/libpersona(11928): KNOX_SDCARD not a persona
I/SELinux (11928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11928): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 3827): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/ActivityManager( 3515): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 3827): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3827): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3827): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 3827): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3827): Blacklist: Clear (temp) 
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 373us total 12.368ms
,E/WifiStateMachine( 3515): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3515): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3515): Network connection established
,D/WifiNative-HAL( 3515): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3515): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 395us total 8.662ms
,E/WifiStateMachine( 3515): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/TimaKeyStoreProvider(11928): TimaSignature is unavailable
,D/ActivityThread(11928): Added TimaKeyStore provider
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 53990(2MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 1.730ms total 90.574ms
,D/ConnectivityService( 3515): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3515): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3515): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3515): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3515): updateNetworkInfo()
I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 372us total 8.465ms
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3515): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3515): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3515): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3515): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(11928): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3515): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3515): mCursor = null
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(11928): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11928): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11928): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3515): do suspend false
,I/DIAGMON_AGENT(11928): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11928): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3515): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3515): InactiveState{ what=143375 }
,D/SecContentProvider2( 3515): mCursor = null
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11946): MountEmulatedStorage()
E/Zygote  (11946): v2
I/libpersona(11946): KNOX_SDCARD checking this for 10012
I/libpersona(11946): KNOX_SDCARD not a persona
,I/SELinux (11946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11946): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11946 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11946): TimaSignature is unavailable
,D/ActivityThread(11946): Added TimaKeyStore provider
,D/ResourcesManager(11946): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3515): Killing 11029:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,I/FOTA_Client(11946): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/lowmemorykiller( 2827): Error writing /proc/11029/oom_score_adj; errno=22
,I/FOTA_Client(11946): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11946): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11962): MountEmulatedStorage()
I/libpersona(11962): KNOX_SDCARD checking this for 10021
E/Zygote  (11962): v2
I/libpersona(11962): KNOX_SDCARD not a persona
I/SELinux (11962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11962): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11962 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11061:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11962): TimaSignature is unavailable
,D/ActivityThread(11962): Added TimaKeyStore provider
,D/ResourcesManager(11962): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11962): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 17:25:15 GMT+01:00 2016
,I/KLMS-2.4.521: (11962): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11962): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11962): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11962): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11962): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11962): StateImplV2(): networkChangeListener().END
,E/Zygote  (11979): MountEmulatedStorage()
I/libpersona(11979): KNOX_SDCARD checking this for 10038
E/Zygote  (11979): v2
I/libpersona(11979): KNOX_SDCARD not a persona
I/SELinux (11979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11979): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11979 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3515): Killing 10843:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/10843/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11979): TimaSignature is unavailable
,D/ActivityThread(11979): Added TimaKeyStore provider
D/ResourcesManager(11979): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/dhcpcd  (11994): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11994): version 5.5.6 starting
,E/dhcpcd  (11994): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SO_AGENT(11979): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11999): MountEmulatedStorage()
I/libpersona(11999): KNOX_SDCARD checking this for 1000
E/Zygote  (11999): v2
I/libpersona(11999): KNOX_SDCARD not a persona
I/SELinux (11999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11083:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,I/dhcpcd  (11994): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11994): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11994): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11994): bssid match
I/dhcpcd  (11994): wlan0: rebinding lease of 192.168.1.124
,D/TimaKeyStoreProvider(11999): TimaSignature is unavailable
,D/ActivityThread(11999): Added TimaKeyStore provider
,D/ResourcesManager(11999): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12021): MountEmulatedStorage()
I/libpersona(12021): KNOX_SDCARD checking this for 10039
E/Zygote  (12021): v2
I/libpersona(12021): KNOX_SDCARD not a persona
I/SELinux (12021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12021): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12021 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11099:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12021): TimaSignature is unavailable
,D/ActivityThread(12021): Added TimaKeyStore provider
,D/ResourcesManager(12021): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12021): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12021): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12021): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12021): PushLog.txt file is not deleted.
D/SPPClientService(12021): PushLog.txt file is not deleted.
D/SPPClientService(12021): ============PushLog. stop!
,I/SA      (11184): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11184): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11184): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11184): [SLFUCHKMGR] constructor called
,E/SPPClientService(12021): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11184): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11184): [OR] == isSIMCardReady false ==
,I/SA      (11184): [SCU] == networkStateCheck == false
I/SA      (11184): [OR] onReceive END
,I/ActivityManager( 3515): Killing 11150:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12041): MountEmulatedStorage()
I/libpersona(12041): KNOX_SDCARD checking this for 10067
E/Zygote  (12041): v2
I/libpersona(12041): KNOX_SDCARD not a persona
,I/SELinux (12041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12041 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12041): TimaSignature is unavailable
,D/ActivityThread(12041): Added TimaKeyStore provider
,D/ResourcesManager(12041): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12041): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12041): Other Intent
,I/ActivityManager( 3515): Killing 11120:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11120/oom_score_adj; errno=22
,D/accuweather( 5209): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5209): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5209): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5209): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5209): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5209): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5209): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12057): MountEmulatedStorage()
I/libpersona(12057): KNOX_SDCARD checking this for 1000
E/Zygote  (12057): v2
I/libpersona(12057): KNOX_SDCARD not a persona
,I/SELinux (12057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12057 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12057): TimaSignature is unavailable
,D/ActivityThread(12057): Added TimaKeyStore provider
,D/ResourcesManager(12057): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12057): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12057): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12057): premStatus:2
,I/KnoxUsageLogPro(12057): isEulaShown : false
I/KnoxUsageLogPro(12057): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12072): MountEmulatedStorage()
E/Zygote  (12072): v2
I/libpersona(12072): KNOX_SDCARD checking this for 10090
I/libpersona(12072): KNOX_SDCARD not a persona
,I/SELinux (12072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12072): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12072 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11241:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12072): TimaSignature is unavailable
,D/ActivityThread(12072): Added TimaKeyStore provider
,D/ResourcesManager(12072): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12088): MountEmulatedStorage()
E/Zygote  (12088): v2
I/libpersona(12088): KNOX_SDCARD checking this for 10127
I/libpersona(12088): KNOX_SDCARD not a persona
,I/SELinux (12088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12088 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3515): Killing 11262:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12088): TimaSignature is unavailable
,D/ActivityThread(12088): Added TimaKeyStore provider
,D/ResourcesManager(12088): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12088): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12088): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12088): stopCheckCategoryVersion
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  (11994): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,E/Zygote  (12105): MountEmulatedStorage()
I/libpersona(12105): KNOX_SDCARD checking this for 10136
E/Zygote  (12105): v2
I/libpersona(12105): KNOX_SDCARD not a persona
,I/SELinux (12105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12105): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12105 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11226:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12105): TimaSignature is unavailable
,D/ActivityThread(12105): Added TimaKeyStore provider
,D/ResourcesManager(12105): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/dhcpcd  (11994): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12105): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12105): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12105): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12105): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12105): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12105): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12105): Loading: webviewchromium
,I/LibraryLoader(12105): Time to load native libraries: 3 ms (timestamps 1543-1546)
I/LibraryLoader(12105): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12105): Binding Chromium to main looper Looper (main, tid 1) {322ef9e9}
,I/LibraryLoader(12105): Expected native library version number "",actual native library version number ""
I/chromium(12105): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12105): Initializing chromium process, renderers=0
,W/art     (12105): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12105): Requires BLUETOOTH permission
,W/chromium(12105): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12105): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12105): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12105): Starting up...
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12194): MountEmulatedStorage()
E/Zygote  (12194): v2
I/libpersona(12194): KNOX_SDCARD checking this for 10150
I/libpersona(12194): KNOX_SDCARD not a persona
,I/SELinux (12194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12194): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12194 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11278:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8746(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 468us total 10.792ms
,D/TimaKeyStoreProvider(12194): TimaSignature is unavailable
,D/ActivityThread(12194): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 435us total 8.460ms
,D/ResourcesManager(12194): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12194): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12194): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12194): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.707ms
,D/QuickConnect(12194): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12194): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12194): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12209): MountEmulatedStorage()
I/libpersona(12209): KNOX_SDCARD checking this for 10178
E/Zygote  (12209): v2
I/libpersona(12209): KNOX_SDCARD not a persona
,I/SELinux (12209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12209 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11294:com.samsung.helphub/1000 (adj 13): bgCount ##31
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3515): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3515): do suspend true
,D/TimaKeyStoreProvider(12209): TimaSignature is unavailable
,D/ActivityThread(12209): Added TimaKeyStore provider
D/WifiP2pService( 3515): InactiveState{ what=143375 }
D/WifiP2pService( 3515): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3515): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3515): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3515): Not connected state, yet.
E/WifiStateMachine( 3515): VerifyingLinkState enter
,D/ResourcesManager(12209): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3515): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3515): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3515): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3515): callSECApiInt - ID [210]
W/ResourcesManager(12209): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/WifiStateMachine( 3515): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
W/ResourcesManager(12209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12209): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/ConnectivityService( 3515): updateNetworkInfo()
W/ResourcesManager(12209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12209): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12209): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService( 3515): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3515): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3515): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3515): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3515): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3515): Now, connected state.
E/WifiStateMachine( 3515): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3515): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3515): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
,D/ConnectivityService( 3515): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3515): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3515): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3515): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3515): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3515): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3515): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3515): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,E/Zygote  (12249): MountEmulatedStorage()
I/libpersona(12249): KNOX_SDCARD checking this for 10082
E/Zygote  (12249): v2
I/libpersona(12249): KNOX_SDCARD not a persona
D/ConnectivityService( 3515): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3515): LTETest block dns file not exists
,I/SELinux (12249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
E/SELinux (12249): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12249 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/ConnectivityService( 3515): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3515): updateNetworkInfo()
E/ConnectivityService( 3515): updateNetworkInfo()
D/ConnectivityService( 3515): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3515): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3515):    accepting network in place of null
,D/TelephonyNetworkFactory( 3975): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3515): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3515): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3515): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3515): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/Tethering( 3515): MasterInitialState.processMessage what=3
,D/EntConnectivity( 3515): Not allowed due to - mEnabled false
D/ConnectivityService( 3515): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6742): CM callback handler got msg 524290
,D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
V/NetworkStats( 3515): updateIfacesLocked()
V/NetworkStats( 3515): performPollLocked(flags=0x1)
,D/TimaKeyStoreProvider(12249): TimaSignature is unavailable
,D/ActivityThread(12249): Added TimaKeyStore provider
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3515): UpdateStatsForKnox
V/NetworkStats( 3515): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
V/NetworkStats( 3515): performPollLocked() took 8ms
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,E/Zygote  (12267): MountEmulatedStorage()
E/Zygote  (12267): v2
I/libpersona(12267): KNOX_SDCARD checking this for 1000
I/libpersona(12267): KNOX_SDCARD not a persona
,I/SELinux (12267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12267): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12267 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 11406:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3515): Killing 11423:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/ResourcesManager(12249): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
D/NtpTrustedTime( 3515): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider(12267): TimaSignature is unavailable
,D/ActivityThread(12267): Added TimaKeyStore provider
,D/BadgeProvider(12249): onCreate
D/BadgeProvider(12249): DatabaseHelper
,D/ResourcesManager(12267): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12249): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 4000): reloadBadges entered.
D/BadgeProvider(12249): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12249): sendNotify, [notify] : null
I/ActivityManager( 3515): Killing 11441:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
D/BadgeProvider(12249): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12249): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12249): update, [UpdateCount] : 1
,I/System.out( 3515): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 3515): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 16:25:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453134316887], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453134316866]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3515): Validated
,D/ConnectivityService( 3515): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3515): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 6742): CM callback handler got msg 524290
,E/Zygote  (12285): MountEmulatedStorage()
I/libpersona(12285): KNOX_SDCARD checking this for 10013
E/Zygote  (12285): v2
I/libpersona(12285): KNOX_SDCARD not a persona
,I/SELinux (12285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3515): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12285 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12285): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/TimaKeyStoreProvider(12285): TimaSignature is unavailable
,D/ActivityThread(12285): Added TimaKeyStore provider
,D/ResourcesManager(12285): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12285): notifyNetworkActivated
,W/ContextImpl(12285): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3515): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12285): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine(12285): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12285): exit::IDLE
D/InitializeManagerStateMachine(12285): entry::NETWORK_CHECK
D/InitializeManagerStateMachine(12285): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12285): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12285): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12285): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12285): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12285): entry::SUCCESS
D/hcjo    (12285): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12285): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12285): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12285): exit::SUCCESS
D/InitializeManagerStateMachine(12285): entry::IDLE
,I/ActivityManager( 3515): Killing 11489:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4078): Starting #10
,I/Hs20UtilService( 4078): Message received 5007
,D/NearbySettings( 8646): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8646): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8646): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8646): MountReceiver.onReceive - Keep current state
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11722): 
,I/SignOutReceiver(11385): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4078): Starting #11
,I/Hs20UtilService( 4078): Message received 5007
,D/NearbySettings( 8646): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8646): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11385): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4078): Starting #12
,D/NearbySettings( 8646): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8646): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 4078): Message received 5007
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8646): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8646): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8646): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11385): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4078): Starting #13
,I/Hs20UtilService( 4078): Message received 5007
,D/NearbySettings( 8646): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8646): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3515): callSECApi what=220
D/WifiStateMachine( 3515): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11385): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3515): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3515
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/ConnectivityService( 3515): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3515): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3515): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3515): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3515): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6227): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6227): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11872): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5365): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5365): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11849): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11849): sales region : global
I/PCWCLIENTTRACE_PushUtil(11849): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11849): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11928): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11928): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3515): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3515): mCursor = null
,I/FOTA_Client(11946): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11946): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11946): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11962): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 17:25:17 GMT+01:00 2016
,I/KLMS-2.4.521: (11962): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11962): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11962): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11962): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(11979): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11962): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11962): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11962): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11962): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11962): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onDestroy()
,E/SPPClientService(12021): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11184): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11184): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11184): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11184): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11184): [OR] == isSIMCardReady false ==
,I/SA      (11184): [SCU] == networkStateCheck == true
I/SA      (11184): [DM] getCountryCodeFromCSC : PL
I/SA      (11184): isChinaCountryCode : false
I/SA      (11184): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11184): [OR] == networkStateCheck true ==
,I/SA      (11184): [OR] GetMyCountryZoneTask
I/SA      (11184): [OR] onReceive END
I/SA      (11184): [SRS] prepareGetMyCountryZone
,I/SA      (11184): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11184): [SSP] query invoked
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11184): [TPMU] GetMccFromDB : null
I/SA      (11184): [SCU] getMccFromPreferece mcc = 260
I/SA      (11184): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12041): Other Intent
,D/accuweather( 5209): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5209): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5209): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5209): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5209): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5209): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5209): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12057): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12057): premStatus:2
,I/KnoxUsageLogPro(12057): isEulaShown : false
I/KnoxUsageLogPro(12057): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12088): cancelUpdateWallpaper
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11722): 
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11722): 
,D/KeyguardWallpaperUpdator(12088): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12088): stopCheckCategoryVersion
,D/QuickConnect(12194): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12194): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12194): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,D/RCPManagerService( 3515): exchangeData() failure , invalid userId
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11722): 
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11722): 
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11722): 
,D/hcjo    (12285): AutoUpdateManager:IDLE:execute
,I/jxcore-log(11722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11722): 
,D/InitializeManagerStateMachine(12285): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12285): exit::IDLE
D/InitializeManagerStateMachine(12285): entry::NETWORK_CHECK
D/InitializeManagerStateMachine(12285): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12285): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12285): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12285): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12285): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12285): entry::SUCCESS
D/hcjo    (12285): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12285): AutoUpdateTriggerManager:IDLE:notifyNextTime,
D/hcjo    (12285): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12285): exit::SUCCESS
D/InitializeManagerStateMachine(12285): entry::IDLE
,I/SA      (11184): [RC New] Execute method=[GET] start
,E/WifiStateMachine( 3515): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3515): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3515): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
D/SmartBondingService( 3515): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3515): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
D/SmartBondingService( 3515): getSBEnabled() enabled =false
,I/SA      (11184): [RC New] Security=[true]
,I/System.out(11184): Thread-1545(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11184): Thread-1545(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11184): Thread-1545(ApacheHTTPLog):isShipBuild true
I/System.out(11184): Thread-1545(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3515): route cmd failed: 
W/NetworkManagementService( 3515): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3515): '
W/NetworkManagementService( 3515): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3515): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3515): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3515): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3515): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3515): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3515): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3515): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3515): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3515): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3515): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3515): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3515): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
D/ConnectivityService( 3515): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 6742): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6742): CM callback handler got msg 524295
,D/ConnectivityService( 3515): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/jxcore-log(11722): Test app app.js loaded
I/jxcore-log(11722): 
,I/chromium(11722): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SA      (11184): [RC New] [v2liruge] api execute + 617
,I/SA      (11184): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11184): AsyncTask #1 calls detatch()
,I/SA      (11184): [TPMU] getNetworkMcc : ,
,I/SA      (11184): [SCU] saveMccToPreferece Start
I/SA      (11184): [SCU] RegionMCC : 260
I/SA      (11184): [SSP] query invoked
,I/SA      (11184): [TPMU] GetMccFromDB : null
,I/SA      (11184): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11184): [SCU] saveMccToPreferece End
,I/SA      (11184): [RC New] executeRequest [v2liruge] end. 706
,I/SA      (11184): [RC New] Execute end
,I/SA      (11184): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11184): [OR] GetMyCountryZoneTask Success
,D/SSRM:n  ( 3515): SIOP:: AP = 290, PST = 277, CUR = 71
,I/PowerManagerService( 3515): [PWL] Off : 50s ago
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:-172, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:117
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11722): setDiscoveryMode: Mode set to BLE
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11722): BLE advertisement is supported
I/jxcore-log(11722): 
,W/ProcessCpuTracker( 3515): Skipping unknown process pid 12330
,I/dhcpcd  (11994): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine( 3515): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3515): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 4652): callingUid 10014, callindPid: 4652
,D/ResourcesManager(11872): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11872): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11872): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11872): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11872): Conditions not met for autocaching.
I/MusicLeanback(11872): Stop autocaching.
,D/WearableClient(11872): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11872): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11872): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11872): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11872): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11872): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11872): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@d30a565 that was originally bound here
E/ActivityThread(11872): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@d30a565 that was originally bound here
E/ActivityThread(11872): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11872): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11872): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11872): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11872): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11872): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11872): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11872): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11872): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11872): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11872): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11872): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11872): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11872): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11872): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11872): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11872): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11872): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11872): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11872): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11872): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11872): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11872): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11872): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11872): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3515): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3515) eventTime = 145684
,D/PowerManagerService( 3515): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3515 (0x0)
D/PowerManagerService( 3515): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3515, ws=WorkSource{10060}) (elapsedTime=3478)
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 55317(3MB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 2.587ms total 151.328ms
I/art     ( 3515): WaitForGcToComplete blocked for 137.109ms for cause HeapTrim
,I/GAV4    (12105): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 3515): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11849): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11849): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11849): ================================================
,I/CSTORAGE(11849):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11849): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11849): [GetString-S]
E/art     (11849): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11849): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11849): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11849): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11849): sales region : global
I/PCWCLIENTTRACE_PushUtil(11849): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11849): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11994): wlan0: sending IPv6 Router Solicitation
,W/ProcessCpuTracker( 3515): Skipping unknown process pid 12421
,D/PreloadUpdateManagerStateMachine(12285): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12285): exit::IDLE
D/PreloadUpdateManagerStateMachine(12285): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12285): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12285): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12285): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12285): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12285): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12285): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12285): exit::IDLE
D/PreloadUpdateManagerStateMachine(12285): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12285): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12285): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12285): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12285): entry::IDLE
,I/dhcpcd  (11994): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  (11994): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3515): SIOP:: AP = 280, PST = 279, CUR = -172
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:-7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:89
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3515): Waited long enough for: ServiceRecord{b5e9a6a u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3515): !@Sync 5
,D/SSRM:n  ( 3515): SIOP:: AP = 260, PST = 273, CUR = -7
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3515): stay LED for fully charged
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3515): [PWL] Off : 75s ago
,D/SSRM:n  ( 3515): SIOP:: AP = 260, PST = 267, CUR = 49
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:83
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4652): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3515): SIOP:: AP = 260, PST = 266, CUR = 65
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:69, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3515): !@Sync 6
,D/SSRM:n  ( 3515): SIOP:: AP = 250, PST = 265, CUR = 69
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:69
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3515): [PWL] Off : 105s ago
,D/SSRM:n  ( 3515): SIOP:: AP = 250, PST = 263, CUR = 67
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:64, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3515): SIOP:: AP = 250, PST = 260, CUR = 64
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3515): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3515): stay LED for fully charged
,I/MotionRecognitionService( 3515): Plugged
I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3515): waitForAlarm result :4
,V/AlarmManager( 3515): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 3515): <AppSync3 Whitelist>
,V/AlarmManager( 3515): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,I/EventLogService( 6742): Aggregate from 1453132503982 (log), 1453132503982 (data)
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3515): !@Sync 7
,D/SSRM:n  ( 3515): SIOP:: AP = 250, PST = 259, CUR = 61
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3515): [PWL] Off : 140s ago
,D/SSRM:n  ( 3515): SIOP:: AP = 250, PST = 258, CUR = 58
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3515): stay LED for fully charged
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3515): SIOP:: AP = 250, PST = 256, CUR = 55
,V/AlarmManager( 3515): waitForAlarm result :8
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3515): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3515): stay LED for fully charged
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3515): !@Sync 8
,D/SSRM:n  ( 3515): SIOP:: AP = 240, PST = 253, CUR = 55
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,D/BatteryService( 3515): stay LED for fully charged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3515): SIOP:: AP = 240, PST = 252, CUR = 51
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3515): [PWL] Off : 180s ago
,D/SSRM:n  ( 3515): SIOP:: AP = 240, PST = 251, CUR = 51
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3515): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3515): stay LED for fully charged
,I/MotionRecognitionService( 3515): Plugged
I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3515): !@Sync 9
,D/SSRM:n  ( 3515): SIOP:: AP = 240, PST = 250, CUR = 48
,D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3515): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3515): Plugged
,I/MotionRecognitionService( 3515): setPowerConnected  = true
,D/BatteryService( 3515): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5607): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11722): --= Surplus to requirements =--
I/jxcore-log(11722): 
I/jxcore-log(11722): ****TEST TOOK:  ms ****
I/jxcore-log(11722): 
I/jxcore-log(11722): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11722): 
,D/AndroidRuntime(12608): 
D/AndroidRuntime(12608): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12608): CheckJNI is OFF
,D/AndroidRuntime(12608): readGMSProperty: start
D/AndroidRuntime(12608): readGMSProperty: already setted!!
,D/AndroidRuntime(12608): readGMSProperty: end
D/AndroidRuntime(12608): addProductProperty: start
,E/AffinityControl(12608): AffinityControl: registerfunction enter
,D/AndroidRuntime(12608): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3515): START PACKAGE DELETE: observer{723766693}
D/PackageManager( 3515): pkg{<packageName>}
D/PackageManager( 3515): user{0}
D/PackageManager( 3515): caller{2000}
D/PackageManager( 3515): flags{3}
,D/PersonaManagerService( 3515): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3515): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3515): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3515): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3515): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3515): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3515): !@killApplicatoin: 10586, uninstall pkg
D/PackageManagerService( 3515): deletePackage- pkg:com.test.thalitest, edmuserId:0
I/ActivityManager( 3515): Force stopping com.test.thalitest appid=10586 user=-1: uninstall pkg
D/PackageManagerService( 3515): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,I/ActivityManager( 3515): Killing 11722:com.test.thalitest/u0a586 (adj 0): stop com.test.thalitest
D/ApplicationPolicy( 3515): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3515): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3515):   Force finishing activity ActivityRecord{26896ff5 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3515): mDVFSHelper.acquire()
,W/PackageSettings( 3515): Skipping PackageSetting{39ae1ab0 com.example.hello/10563} due to missing metadata
,D/WifiService( 3515): Client connection lost with reason: 4
,I/WindowState( 3515): WIN DEATH: Window{1bd0363 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3515): Force stopping com.test.thalitest appid=10586 user=0: pkg removed
,I/ActivityManager( 3515):   Force finishing activity ActivityRecord{26896ff5 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3515): Duplicate finish request for ActivityRecord{26896ff5 u0 com.test.thalitest/.MainActivity t26 f}
,I/art     ( 8853): Explicit concurrent mark sweep GC freed 26068(1506KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.189ms total 43.839ms
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 33123(2031KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.337ms total 39.588ms
,I/DBG_DM  ( 6227): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 6742): Explicit concurrent mark sweep GC freed 29964(1727KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 1.861ms total 88.448ms
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/SamsungIME( 4503): mOCRHelper is null
,I/InputReader( 3515): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4652): Ignoring removeGeofence because network location is disabled.
,D/LWLocationManager(11467): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11467): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6227): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 6227): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/Zygote  (12632): MountEmulatedStorage()
,E/Zygote  (12632): v2
I/libpersona(12632): KNOX_SDCARD checking this for 10063
I/libpersona(12632): KNOX_SDCARD not a persona
,I/ActivityManager( 3515): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12632 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 5365): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5365): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/SecContentProvider2( 3515): uri = 14 selection = getSealedState
D/SecContentProvider2( 3515): mCursor = null
,D/ApplicationPolicy( 3515): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,D/TimaKeyStoreProvider(12632): TimaSignature is unavailable
,D/ActivityThread(12632): Added TimaKeyStore provider
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6227): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6227): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6227): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 27658(2MB) AllocSpace objects, 48(768KB) LOS objects, 24% free, 49MB/65MB, paused 5.617ms total 186.535ms
I/art     ( 3515): WaitForGcToComplete blocked for 160.757ms for cause Explicit
D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/DBG_DM  ( 6227): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6227): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3515): post active user change for 0
,D/KnoxTimeoutHandler( 3515): postActiveUserChange for user 0
,I/DBG_DM  ( 6227): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(12632): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6227): updateVisibility : ActivityRecord{2e8b2c9e token=android.os.BinderProxy@2a6988a3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12632): onReceive()
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/VRSetupWizardStub/PackageIntentReceiver(12632): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12632): packagename:com.test.thalitest
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3515): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3515): mCursor = null
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/KLMS-2.4.521: (11962): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 17:27:44 GMT+01:00 2016
,D/InputMethodManagerService( 3515): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.4.521: (11962): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3515): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3515): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,W/InputMethodManagerService( 3515): Got RemoteException sending setActive(false) notification to pid 11722 uid 10586
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onCreate()
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/Timeline( 6227): Timeline: Activity_idle id: android.os.BinderProxy@2a6988a3 time:289773
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  (12652): MountEmulatedStorage()
I/libpersona(12652): KNOX_SDCARD checking this for 10106
E/Zygote  (12652): v2
I/libpersona(12652): KNOX_SDCARD not a persona
,I/SELinux (12652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3515): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12652 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 3515): mDVFSHelper.release()
I/Timeline( 3515): Timeline: Activity_windows_visible id: ActivityRecord{2c9022d2 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:289782
,I/KLMS-2.4.521: (11962): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11962): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/EnterpriseDeviceManagerService( 3515): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3515): Admin package name: com.google.android.gms
,D/RCPManager(12057):  in createShortcut() for packageName: com.test.thalitest userId0
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/RCPManagerService( 3515):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3515): queryAllProviders():  providerCallBack is not register for 0
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11962): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(11467): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/TimaKeyStoreProvider(12652): TimaSignature is unavailable
,D/ActivityThread(12652): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11962): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (11962): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  (12667): MountEmulatedStorage()
,E/Zygote  (12667): v2
I/libpersona(12667): KNOX_SDCARD checking this for 10050
I/libpersona(12667): KNOX_SDCARD not a persona
,I/SELinux (12667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/ActivityManager( 3515): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12667 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/KLMS-2.4.521: (11962): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/SELinux (12667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 7669(387KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.923ms total 203.106ms
,D/TimaKeyStoreProvider(12667): TimaSignature is unavailable
,D/ActivityThread(12667): Added TimaKeyStore provider
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager(12652): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/RegisteredServicesCache( 3961): empty dynamic service
D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12667): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11467): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  (12683): MountEmulatedStorage()
E/Zygote  (12683): v2
I/libpersona(12683): KNOX_SDCARD checking this for 10183
I/libpersona(12683): KNOX_SDCARD not a persona
,I/SELinux (12683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(12667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12667): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SELinux (12683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/SELinux (12683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager( 3515): delete codoeFile: 
,I/ActivityManager( 3515): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12683 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/AASAUninstall( 3515):  com.test.thalitest not target!
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/PackageManager( 3515): result of delete: 1{723766693}
,D/elm:14491(12652): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12652): ELMEngine.ELMEngine( context ).
D/AndroidRuntime(12608): Shutting down VM
,D/elm:14491(12652): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14491(12652): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12652): ElmAgentService : onCreate()
,D/elm:14491(12652): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12683): TimaSignature is unavailable
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/elm:14491(12652): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12652): MDMBridge.getInstance()
D/elm:14491(12652): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ActivityThread(12683): Added TimaKeyStore provider
,D/elm:14491(12652): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/ResourcesManager(11467): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11467): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11467): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11467): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/Zygote  (12699): MountEmulatedStorage()
E/Zygote  (12699): v2
I/libpersona(12699): KNOX_SDCARD checking this for 10101
I/libpersona(12699): KNOX_SDCARD not a persona
I/SELinux (12699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux (12699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager( 3515): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12699 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12699): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider(12699): TimaSignature is unavailable
E/Zygote  (12715): MountEmulatedStorage()
E/Zygote  (12715): v2
I/libpersona(12715): KNOX_SDCARD checking this for 10019
I/libpersona(12715): KNOX_SDCARD not a persona
D/ActivityThread(12699): Added TimaKeyStore provider
I/SELinux (12715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux (12715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12715 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (11962): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11467): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491(12652): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider(12715): TimaSignature is unavailable
,I/ActivityManager( 3515): Killing 11505:com.android.calendar/u0a164 (adj 13): bgCount ##31
I/KLMS-2.4.521: (11962): KLMSIntentService(): onDestroy()
,D/ResourcesManager(11467): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/ActivityManager( 3515): Killing 11467:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/ActivityThread(12715): Added TimaKeyStore provider
,D/ResourcesManager(12699): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12683): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/PackageManager( 3515): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager(12715): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/ResourceType( 3515): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySource(12667): Nearby Source Create!
D/NearbyContext(12667): Nearby Context Create!
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteLog(12683): (284) automatic index on shooting_modes(title_id)
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12667): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12667): Samsung link source created
,W/ResourcesManager( 3515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/Zygote  (12733): MountEmulatedStorage()
I/libpersona(12733): KNOX_SDCARD checking this for 10190
E/Zygote  (12733): v2
I/libpersona(12733): KNOX_SDCARD not a persona
D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
I/SELinux (12733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3515): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12733 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (12733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 995us total 32.481ms
D/RCPManagerService( 3515): PackageReceiver onReceive()
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 3515): Killing 10785:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/HarmonyEASService( 3515): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3515): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3515): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 3515): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3515): uID is 10586
V/EnterpriseBillingPolicy( 3515): Removed Packageuid is0
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12715): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12715): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12715): onReceive() : package name is not s health. Return !!!
,V/EnterpriseBillingPolicyStorage( 3515): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3515): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3515): getBillingProfileForVpnEngine - start - com.test.thalitest
D/DocsApplication(12699): Installing DEX configuration.
D/TimaKeyStoreProvider(12733): TimaSignature is unavailable
,V/EnterpriseBillingPolicyStorage( 3515): getBillingProfileForVpnEngine - end - null
D/ActivityThread(12733): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 385us total 16.134ms
,D/UsbSettingsManager( 3515): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3515): onPackageRemoved : com.test.thalitest
,D/WifiDisplayAdapter( 3515): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/DexInstaller(12699): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12699): Provided clientMode=RELEASE, packageInfo=PackageInfo{175157d6 com.google.android.apps.docs}
,D/TAG     (12699): onCreate()
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 441us total 13.763ms
,D/KnoxTimeoutHandler( 3515): handleActiveUserChange for user 0
,D/CrossAppStateProvider(12699): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12733): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/StatusBar( 3691): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Zygote  (12750): MountEmulatedStorage()
E/Zygote  (12750): v2
I/libpersona(12750): KNOX_SDCARD checking this for 10022
I/libpersona(12750): KNOX_SDCARD not a persona
,I/SELinux (12750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
I/SELinux (12750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/PanelView( 3691): There is/are notification(s) 
,D/PanelView( 3691): There is/are notification(s) 
E/SELinux (12750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12750 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3691): Icon Only
I/ActivityManager( 3515): Killing 11608:com.android.vending/u0a31 (adj 13): bgCount ##31
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
,D/TaskPersister( 3515): removeObsoleteFile: deleting file=26_task.xml
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12733): onReceive()
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12733): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/TaskPersister( 3515): removeObsoleteFile: deleting file=24_task.xml
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12750): TimaSignature is unavailable
,D/ActivityThread(12750): Added TimaKeyStore provider
,I/TapandpayWidget:Utils(12733): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12733): Widget is not attached.
,E/Zygote  (12767): MountEmulatedStorage()
E/Zygote  (12767): v2
I/libpersona(12767): KNOX_SDCARD checking this for 10052
I/libpersona(12767): KNOX_SDCARD not a persona
I/SELinux (12767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3515): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12767 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (12767): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ContactProvider(12667): getAllContactInfoList Start
,I/ActivityManager( 3515): Killing 12249:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12767): TimaSignature is unavailable
D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ActivityThread(12767): Added TimaKeyStore provider
,D/ResourcesManager(12750): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12750): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6742): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6742): Clearing selected account for com.test.thalitest
,D/ResourcesManager(12767): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12767): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 6742): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager(12767): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12767): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 6742): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6742): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/ResourcesManager(12767): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12767): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/DriveAsyncService( 6742): disk I/O error (code 3850)
E/DriveAsyncService( 6742): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6742): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6742): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6742): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6742): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6742): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6742): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6742): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6742): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6742): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6742): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6742): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6742): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6742): 	at java.lang.Thread.run(Thread.java:818)
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3515): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3515): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3515): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3515): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3515): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3515): usbDeviceRemoved : /dev/bus/usb/001/003
,E/UsbHostManager( 3515): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3515): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/ChimeraCfgMgr( 6742): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6742): Module APK com.google.android.play.games already loaded
,D/MtpClient(12667): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12667): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/SQLiteLog( 6742): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6742): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6742): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 6742): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6742): 	at com.google.android.,gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6742): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/LocationWidgetApplication(12750): onCreate() : start
D/LocationWidgetApplication(12750): countryCode = POLAND
E/SQLiteLog( 6742): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6742): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 6742): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SharedPreferencesImpl( 6742): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SQLiteLog( 6742): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 6742): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6742): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 6742): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6742): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6742): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6742): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6742): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6742): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/UsbHostManager( 3515): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3515): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/SQLiteLog( 4652): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4652): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 4652): Shutting down VM
,E/AndroidRuntime( 4652): FATAL EXCEPTION: main
E/AndroidRuntime( 4652): Process: com.google.android.gms.persistent, PID: 4652
E/AndroidRuntime( 4652): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4652): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4652): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4652): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4652): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4652): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4652): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4652): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4652): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4652): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4652): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4652): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4652): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4652): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4652): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4652): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4652): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4652): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4652): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4652): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4652): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4652): 	... 9 more
D/ChimeraCfgMgr( 6742): Loading module com.google.android.gms.games from APK com.google.android.play.games
E/SQLiteOpenHelper( 6742): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6742): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6742): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6742): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6742): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6742): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6742): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6742): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6742): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6742): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 6742): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6742): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6742): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/ClearPendingStateOp( 6742): Runtime exception while performing operation
E/ClearPendingStateOp( 6742): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6742): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6742): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6742): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6742): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6742): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 6742): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 6742): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ChimeraModuleLdr( 6742): Module APK com.google.android.play.games already loaded
E/AndroidRuntime( 6742): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6742): Process: com.google.android.gms, PID: 6742
E/AndroidRuntime( 6742): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6742): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6742): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6742): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6742): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6742): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6742): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6742): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6742): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6742): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6742): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 6742): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6742): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6742): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6742): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6742): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6742): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6742): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6742): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6742): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6742): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6742): 	at java.lang.Thread.run(Thread.java:818)
I/EventHub( 3515): Removing device '/dev/input/event10' due to inotify event
,E/SQLiteLog( 6742): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6742): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6742): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 6742): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 6742): Sending signal. PID: 6742 SIG: 9
D/LocationManagerService( 3515): getProviders()=[]
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/LocationManagerService( 3515): getProviders()=[passive]
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
D/LocationManagerService( 3515): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(12750): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12750): getLastUiLocationId() : mLastUiLocationId = -100
E/SQLiteLog(12750): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12750): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12750): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12750): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12750): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12750): Shutting down VM
E/AndroidRuntime(12750): FATAL EXCEPTION: main
E/AndroidRuntime(12750): Process: com.sec.android.widgetapp.locationwidget, PID: 12750
E/AndroidRuntime(12750): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12750): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12750): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12750): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12750): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12750): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12750): 	... 9 more
,E/DropBoxManagerService( 3515): Can't write: system_app_wtf
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,I/EventHub( 3515): Removing device '/dev/input/event7' due to inotify event
,E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop199.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,D/Mms/MmsApp(12767): [start]    onCreate() consume time = 0.0
,E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,I/EventHub( 3515): Removing device '/dev/input/event8' due to inotify event
,W/ActivityManager( 3515): Process com.google.android.gms has crashed too many times: killing!
,D/Mms/ArtClassLoader(12767): init before art
,I/ActivityManager( 3515): Killing 4652:com.google.android.gms.persistent/u0a14 (adj 0): crash
,V/BackupManagerService( 3515): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3515): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
D/Mms/ArtClassLoader(12767): init [DONE] art
,D/ContactProvider(12667): getAllContactInfoList End
,E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop200.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,D/Mms/TelephonyPermission(12767): start operation mode monitor
,I/EventHub( 3515): Removing device '/dev/input/event9' due to inotify event
I/syncContacts(12667): thread: 1748, sync time = 428
,D/ResourcesManager(12767): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12767): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/EventHub( 3515): Removing device '/dev/input/event11' due to inotify event
,D/ConnectivityService( 3515): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@329d8d7c)
,D/ConnectivityService( 3515): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3515): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Process (12750): Sending signal. PID: 12750 SIG: 9
,I/ActivityManager( 3515): Process com.google.android.gms (pid 6742)(adj 0) has died(309,1198)
,W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
,I/EventHub( 3515): Removing device '/dev/input/event12' due to inotify event
I/PCWCLIENTTRACE_PushUtil(11849): SPPPushClient is installed : true
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
I/PCWCLIENTTRACE_PushUtil(11849): sales region : global
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
I/PCWCLIENTTRACE_PushUtil(11849): getPushTypeList : [SPP, GCM]
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
I/PCWCLIENTTRACE_SYSTEMReceiver(11849): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10998ms
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
,W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20998ms
,W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 30998ms
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 40998ms
,E/ActivityThread(11824): Failed to find provider info for com.facebook.appmanager.installrecord
,D/Mms/TelephonyPermission(12767): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12767): isDefault true
,D/Mms/MmsApp(12767): onCreate() com.android.mms
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12808): MountEmulatedStorage()
,E/Zygote  (12808): v2
I/libpersona(12808): KNOX_SDCARD checking this for 10031
,I/libpersona(12808): KNOX_SDCARD not a persona
,D/Mms/MmsApp(12767): [start]    initCountryIso consume time = 207.01575
,I/ActivityManager( 3515): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12808 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/GpsStatusListenerHelper( 3515): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@38193605
,D/LocationManagerService( 3515): Location listener died
I/LocationManagerService( 3515): remove 285eecca by com.google.android.gms
I/EventHub( 3515): Removing device '/dev/input/event13' due to inotify event
,D/LocationManagerService( 3515): provider request: passive ProviderRequest[ON interval=0]
,I/SELinux (12808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/LocationManagerService( 3515): Location listener died
I/LocationManagerService( 3515): remove b162168 by com.google.android.gms
E/SELinux (12808): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/LocationManagerService( 3515): provider request: passive ProviderRequest[ON interval=0]
,D/WifiService( 3515): Client connection lost with reason: 4
,I/ActivityManager( 3515): Process com.sec.android.widgetapp.locationwidget (pid 12750)(adj 9) has died(329,1198)
,D/CountryDetector( 3515): The first listener is added
,I/EventHub( 3515): Removing device '/dev/input/event14' due to inotify event
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp(12767): [end]    initCountryIso consume time = 57.683583
,D/Mms/MmsConfig(12767): [start]    MmsConfig.init() consume time = 1.24425
,D/Mms/MmsConfig(12767): before partial update
,E/Zygote  (12824): MountEmulatedStorage()
E/Zygote  (12824): v2
I/libpersona(12824): KNOX_SDCARD checking this for 10035
I/libpersona(12824): KNOX_SDCARD not a persona
,I/SELinux (12824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12824): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12808): TimaSignature is unavailable
,D/ActivityThread(12808): Added TimaKeyStore provider
,I/ActivityManager( 3515): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12824 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/Mms/MmsConfig(12767): Load Resize quality : 80
,D/Mms/MmsConfig(12767):  enable multiwindow = true

```
