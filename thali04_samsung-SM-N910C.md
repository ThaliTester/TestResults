#### Test 57924002a578a80_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
I/PowerManagerService( 3531): [PWL] Off : 140s ago
D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 248, CUR = 35
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
--------- beginning of main
D/AndroidRuntime(11604): 
D/AndroidRuntime(11604): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11604): CheckJNI is OFF
D/AndroidRuntime(11604): readGMSProperty: start
D/AndroidRuntime(11604): readGMSProperty: already setted!!
D/AndroidRuntime(11604): readGMSProperty: end
D/AndroidRuntime(11604): addProductProperty: start
E/AffinityControl(11604): AffinityControl: registerfunction enter
D/AndroidRuntime(11604): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3531): inState():  stateMachine is null !!
I/PersonaManagerService( 3531): PersonaId don't exist
I/ActivityManager( 3531): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3531): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3531): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3531): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3531): mDVFSHelper.acquire()
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11623): MountEmulatedStorage()
I/libpersona(11623): KNOX_SDCARD checking this for 10622
E/Zygote  (11623): v2
I/libpersona(11623): KNOX_SDCARD not a persona
I/SELinux (11623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3531): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11623 uid=10622 gids={50622, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11623): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11604): Shutting down VM
D/PointerIcon( 3531): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3531): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3531): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3531): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11623): TimaSignature is unavailable
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8760(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 851us total 24.078ms
D/ActivityThread(11623): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 843us total 18.404ms
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6210): updateVisibility : ActivityRecord{1477d460 token=android.os.BinderProxy@3f97b89d {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager(11623): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 857us total 20.851ms
,I/WebViewFactory(11623): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11623): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11623): Loading: webviewchromium
,I/LibraryLoader(11623): Time to load native libraries: 6 ms (timestamps 5787-5793)
,I/LibraryLoader(11623): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11623): Binding Chromium to main looper Looper (main, tid 1) {7ef9d33}
,I/LibraryLoader(11623): Expected native library version number "",actual native library version number ""
,I/chromium(11623): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11623): Initializing chromium process, renderers=0
,W/art     (11623): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11623): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11623): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11623): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11623): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11623): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11623): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11623): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11623): CordovaWebView is running on device made by: samsung
,W/art     (11623): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11623): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 3531): Activity pause timeout for ActivityRecord{3e87e26b u0 com.test.thalitest/.MainActivity t26}
,D/Activity(11623): performCreate Call secproduct feature valuefalse
D/Activity(11623): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11623): Render dirty regions requested: true
,D/ActivityManager( 3531): post active user change for 0
D/KnoxTimeoutHandler( 3531): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3531): handleActiveUserChange for user 0
,V/ActivityThread(11623): updateVisibility : ActivityRecord{3eda3923 token=android.os.BinderProxy@e582516 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3531): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3531): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3531): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3531): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3531): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3531): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11623): Initialized EGL, version 1.4
I/OpenGLRenderer(11623): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278840560 
D/OpenGLRenderer(11623): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11623): Enabling debug mode 0
D/mali_winsys(11623): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3531): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3531): Timeline: Activity_windows_visible id: ActivityRecord{3e87e26b u0 com.test.thalitest/.MainActivity t26} time:236191
W/ActivityManager( 3531): mDVFSHelper.release()
,I/art     ( 3531): Explicit concurrent mark sweep GC freed 60693(3MB) AllocSpace objects, 46(736KB) LOS objects, 24% free, 48MB/64MB, paused 3.895ms total 174.312ms
,W/IInputConnectionWrapper(11623): showStatusIcon on inactive InputConnection
I/Timeline(11623): Timeline: Activity_idle id: android.os.BinderProxy@e582516 time:236362
,I/chromium(11623): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11623): 
,D/JsMessageQueue(11623): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11623): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361619200
,I/chromium(11623): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11623): Initializing JXcore engine
W/jxcore-log(11623): JXcore engine is ready
,E/auditd  ( 4607): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3531): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3531): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11623): Starting JXcore engine
,W/jxcore-log(11623): Platform android
W/jxcore-log(11623): 
W/jxcore-log(11623): Process ARCH arm
W/jxcore-log(11623): 
,I/jxcore-log(11623): JXcore Cordova bridge is ready!
I/jxcore-log(11623): 
W/jxcore-log(11623): JXcore engine is started
,I/jxcore-log(11623): Toggling radios to true
I/jxcore-log(11623): 
,D/BluetoothAdapter(11623): enable()
,D/BluetoothAdapter(11623): enable(): BT is already enabled..!
,D/WifiService( 3531): New client listening to asynchronous messages
,I/WifiManager(11623): packageName : com.test.thalitest
,D/SecContentProvider( 3531): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3531): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3531): mCursor = null
,D/WifiService( 3531): setWifiEnabled: true pid=11623, uid=10622
E/WifiService( 3531): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3531): Permission Denial: getCurrentUser() from pid=11623, uid=10622 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3531): Failed getting userId using ActivityManagerNative
W/WifiService( 3531): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11623, uid=10622 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3531): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3531): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3531): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3531): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3531): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3531): name = wifi_on
,I/WifiService( 3531): disconnect: pid=11623, uid=10622
,I/wpa_supplicant( 3835): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11623): Radios toggled
I/jxcore-log(11623): 
,I/jxcore-log(11623): My device name is: samsung-SM-N910C
I/jxcore-log(11623): 
,I/wpa_supplicant( 3835): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3835): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3531): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3835): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3835): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3835): Disconnected - do not scan
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3531): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3531): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3531): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3531): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3531): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3531): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3531): do suspend true
,D/WifiP2pService( 3531): InactiveState{ what=143375 }
D/WifiP2pService( 3531): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3531): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3531): updateNetworkInfo()
D/ConnectivityService( 3531): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3531): updateNetworkInfo()
D/ConnectivityService( 3531): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3531): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3531): evaluateTrafficStatsPolling
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
,D/NearbySettings( 8793): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 8793): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8793): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8793): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 4112): Starting #8
V/NearbySettings( 8793): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 4112): Message received 5007
E/WifiStateMachine( 3531): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3835): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3835): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3835): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3835): First Scan Start
,E/WifiStateMachine( 3531): ConnectModeState: Network connection lost 
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine( 3531): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/wpa_supplicant( 3835): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3531): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3531): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3531): do suspend true
,D/WifiService( 3531): New client listening to asynchronous messages
,I/NearbySettings( 8793): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8793): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8793): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 3531): InactiveState{ what=143375 }
,D/WifiP2pService( 3531): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
I/SignOutReceiver(11241): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3531): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3531): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3531): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3531): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3531): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3531): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3531): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine( 3531): updateConfiguredNetworkExpiration - currTime: 1454460318899
D/WifiStateMachine( 3531): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3531): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3531): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 4758): CM callback handler got msg 524292
E/WifiStateMachine( 3531): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3531): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3531): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 3531): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3531): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3531): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3531): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3531): MasterInitialState.processMessage what=3
D/EntConnectivity( 3531): Not allowed due to - mEnabled false
D/SmartBondingService( 3531): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3531): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3531): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
V/NetworkStats( 3531): updateIfacesLocked()
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
V/NetworkStats( 3531): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
D/SmartBondingService( 3531): getSBEnabled() enabled =false
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3531): UpdateStatsForKnox
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
V/NetworkStats( 3531): performPollLocked() took 4ms
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
,D/SmartBondingService( 3531): getNetworkEnabled : wifi : true mobile : false
I/Hs20UtilService( 4112): Starting #9
I/Hs20UtilService( 4112): Message received 5007
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
V/NetworkStats( 3531): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
,D/NearbySettings( 8793): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8793): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8793): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8793): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8793): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11241): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,I/wpa_supplicant( 3835): Scan aborted because the firmware maybe busy.
I/wpa_supplicant( 3835): Therefore we will repeat the scan command after 1 seconds.
I/wpa_supplicant( 3835): wlan0: Setting scan request: 1 sec 0 usec
,D/ConnectivityService( 3531): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3531): updateDataUsageMap
I/ApplicationPolicy( 3531): updateDataUsageMap  idList is null 
D/SmartBondingService( 3531): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3531): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3531): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/SLocation( 3531): No Active Data Connection
I/DBG_DM  ( 6210): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 6210): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  (11737): MountEmulatedStorage()
I/libpersona(11737): KNOX_SDCARD checking this for 10110
E/Zygote  (11737): v2
I/libpersona(11737): KNOX_SDCARD not a persona
,I/SELinux (11737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11737): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11737 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11737): TimaSignature is unavailable
,D/ActivityThread(11737): Added TimaKeyStore provider
,D/ResourcesManager(11737): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11737): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11737): not using cross-dex optimization: ART in use
,I/art     (11737): Thread[1,tid=11737,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11737): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11737): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11737): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11737): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11737): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11737): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11737): loading pre-built fallback odex files
V/MultiDexClassLoader(11737): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11737): released odex store lock
D/DexLibLoader(11737): DexLibLoader.loadAll took 15 ms
,W/ca      (11737): Verify
,W/LightSharedPreferencesImpl(11737): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11737): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11737): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11737): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11737): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11737): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11737): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11737): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11737): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11737): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11737): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11737): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11737): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11737): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11737): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11737): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11737): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11737): 	... 10 more
,I/PCWCLIENTTRACE_PushUtil(10909): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10909): sales region : global
I/PCWCLIENTTRACE_PushUtil(10909): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10909): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(10909): noConnectivity : true
W/appmanager(:<default>):b(11737): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/appmanager(:<default>):b(11737): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11764): MountEmulatedStorage()
I/libpersona(11764): KNOX_SDCARD checking this for 10135
E/Zygote  (11764): v2
I/libpersona(11764): KNOX_SDCARD not a persona
I/SELinux (11764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11764): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11764 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 10925:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/10925/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11764): TimaSignature is unavailable
,D/ActivityThread(11764): Added TimaKeyStore provider
,D/ResourcesManager(11764): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11737): Exposure of experiment com.facebook.common.network.l@35c3ca41 occurred when no user was logged in
,W/BroadcastQueue( 3531): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{abf10be u0 ReceiverList{1b85ab79 11737 com.facebook.appmanager/10110/u0 remote:350d6040}}
,W/BroadcastQueue( 3531): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{abf10be u0 ReceiverList{1b85ab79 11737 com.facebook.appmanager/10110/u0 remote:350d6040}}
,I/MusicStore(11764): Database version: 104
,W/BroadcastQueue( 3531): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{113c9922 u0 ReceiverList{2f8446ed 11737 com.facebook.appmanager/10110/u0 remote:83104}}
,D/ResourcesManager(11764): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11764): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11764): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11764): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11764): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11764): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@eaa4a57: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11764): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11764): GMSCore installation verified
,I/ConfigStore(11764): Config Database version: 1
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11764): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/WifiDisplayAdapter( 3531): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 3531): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService( 3531): getStreamVolume 3 index 0
I/MediaRouter(11764): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11737): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11737): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
E/Zygote  (11804): MountEmulatedStorage()
E/Zygote  (11804): v2
I/libpersona(11804): KNOX_SDCARD checking this for 10002
I/libpersona(11804): KNOX_SDCARD not a persona
I/SELinux (11804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11804): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11804 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WifiDisplayAdapter( 3531): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/NetworkMonitor(11764): type=WIFI subType= reason=null isConnected=false
D/TimaKeyStoreProvider(11804): TimaSignature is unavailable
I/ActivityManager( 3531): Killing 10198:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
D/ActivityThread(11804): Added TimaKeyStore provider
W/appmanager(:<default>):QuickExperimentControllerImpl(11737): Exposure of experiment com.facebook.imagepipeline.a.g@2b1e166 occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(11737): Exposure of experiment com.facebook.imagepipeline.a.d@1c97fc43 occurred when no user was logged in
D/ResourcesManager(11804): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
I/art     (11737): Explicit concurrent mark sweep GC freed 42501(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 819us total 22.101ms
W/appmanager(:<default>):m(11737): No feature status reporters found; is this dead code?
I/ActivityManager( 3531): Killing 9796:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11826): MountEmulatedStorage()
I/libpersona(11826): KNOX_SDCARD checking this for 1000
E/Zygote  (11826): v2
I/libpersona(11826): KNOX_SDCARD not a persona
I/SELinux (11826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11826): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11826 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider(11826): TimaSignature is unavailable
D/ActivityThread(11826): Added TimaKeyStore provider
I/wpa_supplicant( 3835): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3835): Scan requested (ret=0) - scan timeout 30 seconds
D/ResourcesManager(11826): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/DIAGMON_AGENT(11826): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/DIAGMON_AGENT(11826): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT(11826): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT(11826): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11826): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11842): MountEmulatedStorage()
I/libpersona(11842): KNOX_SDCARD checking this for 10012
E/Zygote  (11842): v2
I/libpersona(11842): KNOX_SDCARD not a persona
I/SELinux (11842): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11842): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11842): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11842 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider(11842): TimaSignature is unavailable
D/ActivityThread(11842): Added TimaKeyStore provider
D/ResourcesManager(11842): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
I/ActivityManager( 3531): Killing 10940:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/10940/oom_score_adj; errno=22
I/FOTA_Client(11842): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(11842): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(11842): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11858): MountEmulatedStorage()
E/Zygote  (11858): v2
I/libpersona(11858): KNOX_SDCARD checking this for 10021
I/libpersona(11858): KNOX_SDCARD not a persona
I/SELinux (11858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3531): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11858 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (11858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Killing 10955:com.policydm/1000 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/10955/oom_score_adj; errno=22
D/TimaKeyStoreProvider(11858): TimaSignature is unavailable
D/ActivityThread(11858): Added TimaKeyStore provider
D/ResourcesManager(11858): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: (11858): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 01:45:20 GMT+01:00 2016
I/KLMS-2.4.521: (11858): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (11858): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (11858): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (11858): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (11858): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11858): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (11858): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (11858): StateImplV2(): networkChangeListener().END
E/Zygote  (11874): MountEmulatedStorage()
I/libpersona(11874): KNOX_SDCARD checking this for 10038
E/Zygote  (11874): v2
I/libpersona(11874): KNOX_SDCARD not a persona
I/SELinux (11874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11874 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (11858): KLMSIntentService(): onDestroy()
I/ActivityManager( 3531): Killing 10975:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11874): TimaSignature is unavailable
D/ActivityThread(11874): Added TimaKeyStore provider
D/ResourcesManager(11874): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
I/SO_AGENT(11874): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11889): MountEmulatedStorage()
I/libpersona(11889): KNOX_SDCARD checking this for 1000
E/Zygote  (11889): v2
I/libpersona(11889): KNOX_SDCARD not a persona
I/SELinux (11889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11889 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3531): Killing 10995:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/10995/oom_score_adj; errno=22
D/TimaKeyStoreProvider(11889): TimaSignature is unavailable
D/ActivityThread(11889): Added TimaKeyStore provider
D/ResourcesManager(11889): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11909): MountEmulatedStorage()
E/Zygote  (11909): v2
I/libpersona(11909): KNOX_SDCARD checking this for 10039
I/libpersona(11909): KNOX_SDCARD not a persona
I/SELinux (11909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11909): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11909 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3531): Killing 10814:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(11909): TimaSignature is unavailable
D/ActivityThread(11909): Added TimaKeyStore provider
D/ResourcesManager(11909): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService(11909): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11909): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService(11909): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
D/SPPClientService(11909): PushLog.txt file is not deleted.
D/SPPClientService(11909): PushLog.txt file is not deleted.
D/SPPClientService(11909): ============PushLog. stop!
I/SA      (11087): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11087): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11087): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11087): [SLFUCHKMGR] constructor called
E/SPPClientService(11909): [[SystemStateMonitorService]] No Active Internet
I/SA      (11087): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11087): [OR] == isSIMCardReady false ==
I/SA      (11087): [SCU] == networkStateCheck == false
I/SA      (11087): [OR] onReceive END
V/DownloadManager( 3718): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 3531): Killing 11041:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/Zygote  (11929): MountEmulatedStorage()
I/libpersona(11929): KNOX_SDCARD checking this for 10067
E/Zygote  (11929): v2
I/libpersona(11929): KNOX_SDCARD not a persona
I/SELinux (11929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11929 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(11929): TimaSignature is unavailable
D/ActivityThread(11929): Added TimaKeyStore provider
D/ResourcesManager(11929): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/sCloudBackupApp(11929): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11929): Other Intent
I/ActivityManager( 3531): Killing 11064:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
D/accuweather( 5194): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5194): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5194): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5194): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11945): MountEmulatedStorage()
E/Zygote  (11945): v2
I/libpersona(11945): KNOX_SDCARD checking this for 1000
I/libpersona(11945): KNOX_SDCARD not a persona
,I/SELinux (11945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11945): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=11945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 272us total 10.283ms
,D/TimaKeyStoreProvider(11945): TimaSignature is unavailable
,D/ActivityThread(11945): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 259us total 8.807ms
,D/ResourcesManager(11945): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11945): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 274us total 8.833ms
,I/KnoxUsageLogPro(11945): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(11945): premStatus:2
,I/KnoxUsageLogPro(11945): isEulaShown : false
I/KnoxUsageLogPro(11945): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11960): MountEmulatedStorage()
E/Zygote  (11960): v2
I/libpersona(11960): KNOX_SDCARD checking this for 10090
I/libpersona(11960): KNOX_SDCARD not a persona
,I/SELinux (11960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11960): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=11960 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 11026:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11960): TimaSignature is unavailable
,D/ActivityThread(11960): Added TimaKeyStore provider
,D/ResourcesManager(11960): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11976): MountEmulatedStorage()
I/libpersona(11976): KNOX_SDCARD checking this for 10127
E/Zygote  (11976): v2
I/libpersona(11976): KNOX_SDCARD not a persona
,I/SELinux (11976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11976 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3531): Killing 11153:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11976): TimaSignature is unavailable
,D/ActivityThread(11976): Added TimaKeyStore provider
,D/ResourcesManager(11976): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(11976): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11976): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11976): stopCheckCategoryVersion
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11993): MountEmulatedStorage()
I/libpersona(11993): KNOX_SDCARD checking this for 10136
E/Zygote  (11993): v2
I/libpersona(11993): KNOX_SDCARD not a persona
I/SELinux (11993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11993): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=11993 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 11138:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11993): TimaSignature is unavailable
,D/ActivityThread(11993): Added TimaKeyStore provider
,D/ResourcesManager(11993): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(11993): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11993): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11993): Loading: webviewchromium
,I/LibraryLoader(11993): Time to load native libraries: 3 ms (timestamps 9915-9918)
I/LibraryLoader(11993): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11993): Binding Chromium to main looper Looper (main, tid 1) {2a9f34f3}
,I/LibraryLoader(11993): Expected native library version number "",actual native library version number ""
I/chromium(11993): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11993): Initializing chromium process, renderers=0
W/art     (11993): Attempt to remove local handle scope entry from IRT, ignoring
W/AudioManagerAndroid(11993): Requires BLUETOOTH permission
W/chromium(11993): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11993): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(11993): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(11993): Starting up...
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12061): MountEmulatedStorage()
I/libpersona(12061): KNOX_SDCARD checking this for 10150
E/Zygote  (12061): v2
I/libpersona(12061): KNOX_SDCARD not a persona
,I/SELinux (12061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12061): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12061 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 11173:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12061): TimaSignature is unavailable
,D/ActivityThread(12061): Added TimaKeyStore provider
,D/ResourcesManager(12061): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12061): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12061): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12061): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12061): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12061): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12061): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12077): MountEmulatedStorage()
I/libpersona(12077): KNOX_SDCARD checking this for 10178
E/Zygote  (12077): v2
I/libpersona(12077): KNOX_SDCARD not a persona
,I/SELinux (12077): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12077): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12077): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12077 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 11190:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12077): TimaSignature is unavailable
,D/ActivityThread(12077): Added TimaKeyStore provider
,D/ResourcesManager(12077): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12077): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12077): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12077): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12077): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12077): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12077): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3531): exchangeData() failure , invalid userId
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12100): MountEmulatedStorage()
I/libpersona(12100): KNOX_SDCARD checking this for 10082
E/Zygote  (12100): v2
I/libpersona(12100): KNOX_SDCARD not a persona
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
I/SELinux (12100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12100): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12100 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12100): TimaSignature is unavailable
,D/ActivityThread(12100): Added TimaKeyStore provider
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12100): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  (12116): MountEmulatedStorage()
E/Zygote  (12116): v2
I/libpersona(12116): KNOX_SDCARD checking this for 1000
I/libpersona(12116): KNOX_SDCARD not a persona
,I/SELinux (12116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3531): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3531): Killing 11260:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3531): Killing 11206:com.samsung.helphub/1000 (adj 13): bgCount ##32
,D/BadgeProvider(12100): onCreate
,D/BadgeProvider(12100): DatabaseHelper
,D/TimaKeyStoreProvider(12116): TimaSignature is unavailable
,D/ActivityThread(12116): Added TimaKeyStore provider
,I/art     ( 3531): Explicit concurrent mark sweep GC freed 38054(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.219ms total 76.015ms
,D/ResourcesManager(12116): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12100): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 3531): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3531): Killing 11277:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12100): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(12100): sendNotify, [notify] : null
D/BadgeProvider(12100): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12100): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12100): update, [UpdateCount] : 1
,D/Launcher.Model( 4003): reloadBadges entered.
,I/iu.Environment( 4758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4758): num queued entries: 0
I/iu.UploadsManager( 4758): num updated entries: 0
,I/iu.SyncManager( 4758): NEXT; no task
,E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3531): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12134): MountEmulatedStorage()
E/Zygote  (12134): v2
I/libpersona(12134): KNOX_SDCARD checking this for 10013
I/libpersona(12134): KNOX_SDCARD not a persona
,I/SELinux (12134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12134): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3531): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12134 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12134): TimaSignature is unavailable
,D/ActivityThread(12134): Added TimaKeyStore provider
,D/ResourcesManager(12134): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3531): Killing 11294:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/jxcore-log(11623): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11623): 
,I/jxcore-log(11623): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11623): 
,I/jxcore-log(11623): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11623): 
,I/jxcore-log(11623): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(11623): 
,I/jxcore-log(11623): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11623): 
,I/wpa_supplicant( 3835): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 3835): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3835): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3835): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3531): [1,454,460,323,407 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3531): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3c109ab2 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3531): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3531): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3531): setDetailed state send new extra info
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
,I/wpa_supplicant( 3835): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3531): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3531): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3835): Associated with C0.AA.48
E/WifiStateMachine( 3531): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
,I/wpa_supplicant( 3835): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3531): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3531): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
,I/wpa_supplicant( 3835): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3835): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3531): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3531): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3835): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3835): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3835): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3835): Blacklist: Clear (temp) 
,I/wpa_supplicant( 3835): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3531): Network connection established
D/WifiNative-HAL( 3531): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3531): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3531): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3531): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3531): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3531): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3531): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiConfigStore( 3531): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3531): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3531): updateNetworkInfo()
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4112): Starting #10
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8793): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8793): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8793): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8793): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8793): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11241): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3531): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3531): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3531): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3531): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3531): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
,E/WifiStateMachine( 3531): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3531): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3531): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3531): do suspend false
,D/SecContentProvider2( 3531): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3531): mCursor = null
D/WifiP2pService( 3531): InactiveState{ what=143375 }
D/WifiP2pService( 3531): P2pEnabledState{ what=143375 }
,E/dhcpcd  (12152): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12152): version 5.5.6 starting
,E/dhcpcd  (12152): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12152): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12152): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12152): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12152): bssid match
,I/dhcpcd  (12152): wlan0: rebinding lease of 192.168.1.124
,I/dhcpcd  (12152): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12152): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3531): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3531): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3531): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3531): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3531): do suspend true
,D/WifiP2pService( 3531): InactiveState{ what=143375 }
D/WifiP2pService( 3531): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3531): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3531): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3531): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3531): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3531): Not connected state, yet.
E/WifiStateMachine( 3531): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3531): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3531): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3531): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3531): callSECApiInt - ID [210]
,E/WifiStateMachine( 3531): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3531): updateNetworkInfo()
,D/ConnectivityService( 3531): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3531): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3531): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3531): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3531): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3531): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3531): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3531): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3531): Now, connected state.
E/WifiStateMachine( 3531): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3531): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3531): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine( 3531): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3531): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/WifiStateMachine( 3531): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService( 3531): Unexpected mtu value: 0, wlan0
V/        ( 2844): QcRouteController
,I/WifiTrafficPoller( 3531): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3531): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3531): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3531): callSECApiVoid - ID [212]
,I/WifiStateMachine( 3531): REQUEST_POWER_SAVE_ON
,V/        ( 2844): QcRouteController
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
,I/Hs20UtilService( 4112): Starting #11
,V/        ( 2844): QcRouteController
I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8793): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8793): MountReceiver.onReceive - Keep current state
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11241): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4112): Starting #12
,I/Hs20UtilService( 4112): Message received 5007
V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
D/NearbySettings( 8793): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8793): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8793): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8793): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8793): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8793): MountReceiver.mPrefHandler - 7002
,V/        ( 2844): QcRouteController
I/SignOutReceiver(11241): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #13
,I/Hs20UtilService( 4112): Message received 5007
,D/ConnectivityService( 3531): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3531): LTETest block dns file not exists
D/NearbySettings( 8793): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8793): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3531): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3531): updateNetworkInfo()
E/ConnectivityService( 3531): updateNetworkInfo()
D/ConnectivityService( 3531): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3531): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3531): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3531): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiStateMachine( 3531): callSECApi what=220
D/WifiStateMachine( 3531): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3531):    accepting network in place of null
,D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3531): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3531): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3531): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3531): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity( 3531): Not allowed due to - mEnabled false
D/ConnectivityService( 3531): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4758): CM callback handler got msg 524290
D/Tethering( 3531): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3531): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3531): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
,V/NetworkStats( 3531): updateIfacesLocked()
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
V/NetworkStats( 3531): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3531): UpdateStatsForKnox
,D/SmartBondingService( 3531): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
V/NetworkStats( 3531): performPollLocked() took 4ms
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
V/NetworkStats( 3531): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
I/SignOutReceiver(11241): NETWORK_STATE_CHANGED_ACTION
,D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
D/NtpTrustedTime( 3531): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3531): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3531
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3531): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 00:45:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454460324549], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454460324450]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3531): Validated
,D/ConnectivityService( 3531): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3531): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3531): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3531): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3531): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 4758): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3531): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3531): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3531): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3531): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3531): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
,D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
,D/SmartBondingService( 3531): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3531): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6210): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6210): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11764): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5358): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5358): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(10909): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10909): sales region : global
I/PCWCLIENTTRACE_PushUtil(10909): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10909): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11826): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11826): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3531): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3531): mCursor = null
,I/FOTA_Client(11842): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11842): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11842): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11858): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 01:45:24 GMT+01:00 2016
,I/KLMS-2.4.521: (11858): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11858): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11858): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SO_AGENT(11874): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11858): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11858): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11858): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11858): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11858): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11858): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11858): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11858): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11858): KLMSIntentService(): onDestroy()
,E/WifiStateMachine( 3531): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3531): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3531): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/SPPClientService(11909): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
D/SmartBondingService( 3531): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,V/        ( 2844): QcRouteController
D/SmartBondingService( 3531): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
D/SmartBondingService( 3531): getSBEnabled() enabled =false
,I/SA      (11087): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11087): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11087): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11087): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11087): [OR] == isSIMCardReady false ==
,I/SA      (11087): [SCU] == networkStateCheck == true
I/SA      (11087): [DM] getCountryCodeFromCSC : PL
I/SA      (11087): isChinaCountryCode : false
I/SA      (11087): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11087): [OR] == networkStateCheck true ==
I/SA      (11087): [OR] GetMyCountryZoneTask
I/SA      (11087): [OR] onReceive END
,V/        ( 2844): QcRouteController
I/SA      (11087): [SRS] prepareGetMyCountryZone
,W/NetworkManagementService( 3531): route cmd failed: 
W/NetworkManagementService( 3531): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3531): '
W/NetworkManagementService( 3531): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3531): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3531): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3531): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3531): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3531): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3531): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3531): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3531): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3531): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,D/ConnectivityService( 3531): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 4758): CM callback handler got msg 524295
V/DownloadManager( 3718): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524295
,I/SA      (11087): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11087): [SSP] query invoked
,D/ConnectivityManager.CallbackHandler( 4758): CM callback handler got msg 524295
,I/SA      (11087): [TPMU] GetMccFromDB : null
I/SA      (11087): [SCU] getMccFromPreferece mcc = 260
I/SA      (11087): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(11929): Other Intent
,D/accuweather( 5194): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5194): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5194): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5194): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5194): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(11945): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(11945): premStatus:2
,I/KnoxUsageLogPro(11945): isEulaShown : false
I/KnoxUsageLogPro(11945): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(11976): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11976): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11976): stopCheckCategoryVersion
,D/QuickConnect(12061): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12061): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12061): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
,D/RCPManagerService( 3531): exchangeData() failure , invalid userId
,I/iu.Environment( 4758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4758): num queued entries: 0
,I/iu.UploadsManager( 4758): num updated entries: 0
,I/iu.SyncManager( 4758): NEXT; no task
,D/WaitQueueForNetworkActivate(12134): notifyNetworkActivated
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12134): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3531): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12134): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12134): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12134): exit::IDLE
D/InitializeManagerStateMachine(12134): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12134): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12134): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12134): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12134): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12134): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12134): entry::SUCCESS
D/hcjo    (12134): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12134): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12134): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12134): exit::SUCCESS
D/InitializeManagerStateMachine(12134): entry::IDLE
,D/WearableService( 4617): callingUid 10014, callindPid: 4617
,D/ResourcesManager(11764): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11764): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11764): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11764): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11764): Conditions not met for autocaching.
I/MusicLeanback(11764): Stop autocaching.
,D/WearableClient(11764): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11764): WearableClientImpl.onPostInitHandler: done
,I/SA      (11087): [RC New] Execute method=[GET] start
,D/WearableClient(11764): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11764): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11764): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11764): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11764): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@e4d759c that was originally bound here
E/ActivityThread(11764): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@e4d759c that was originally bound here
E/ActivityThread(11764): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11764): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11764): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11764): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11764): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11764): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11764): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11764): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11764): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11764): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11764): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11764): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11764): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11764): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11764): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11764): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11764): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11764): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11764): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11764): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11764): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(11623): Test app app.js loaded
I/jxcore-log(11623): 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11623): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ea4d5ab added. We now have 1 listener(s)
I/SA      (11087): [RC New] Security=[true]
I/jxcore-log(11623): BLE advertisement is supported
I/jxcore-log(11623): 
I/System.out(11087): Thread-1525(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11087): Thread-1525(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11087): Thread-1525(ApacheHTTPLog):isShipBuild true
I/System.out(11087): Thread-1525(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
I/chromium(11623): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService( 3531): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/SSRM:n  ( 3531): SIOP:: AP = 280, PST = 248, CUR = 35
,I/GAV4    (11993): Thread[GAThread,5,main]: No campaign data found.
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:-234, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3531): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      (11087): [RC New] [v2liruge] api execute + 1354
,I/SA      (11087): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11087): AsyncTask #1 calls detatch()
,I/SA      (11087): [TPMU] getNetworkMcc : 
,I/SA      (11087): [SCU] saveMccToPreferece Start
,I/SA      (11087): [SCU] RegionMCC : 260
I/SA      (11087): [SSP] query invoked
,I/SA      (11087): [TPMU] GetMccFromDB : null
I/SA      (11087): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11087): [SCU] saveMccToPreferece End
,I/SA      (11087): [RC New] executeRequest [v2liruge] end. 1462
I/SA      (11087): [RC New] Execute end
I/SA      (11087): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11087): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine( 3531): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3531): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3531): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3531) eventTime = 246889
,D/PowerManagerService( 3531): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3531 (0x0)
,D/PowerManagerService( 3531): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3531, ws=WorkSource{10060}) (elapsedTime=3512),
,I/dhcpcd  (12152): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver(10909): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil(10909): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(10909): ================================================
I/CSTORAGE(10909):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(10909): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(10909): [GetString-S]
,E/art     (10909): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(10909): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(10909): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(10909): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10909): sales region : global
I/PCWCLIENTTRACE_PushUtil(10909): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(10909): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12152): wlan0: sending IPv6 Router Solicitation
,E/Watchdog( 3531): !@Sync 8
,D/PreloadUpdateManagerStateMachine(12134): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12134): exit::IDLE
D/PreloadUpdateManagerStateMachine(12134): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12134): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12134): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12134): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12134): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12134): entry::IDLE
,D/SSRM:n  ( 3531): SIOP:: AP = 270, PST = 249, CUR = -234
,I/dhcpcd  (12152): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12152): wlan0: no IPv6 Routers available
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:-54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 260, PST = 250, CUR = -54
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3531): [PWL] Off : 180s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 9
,D/SSRM:n  ( 3531): SIOP:: AP = 250, PST = 251, CUR = 31
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3531): SIOP:: AP = 250, PST = 251, CUR = 40
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 250, PST = 252, CUR = 39
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3531): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3531): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3531): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3531): initializing...
,I/TLC_TIMA_PKM_initialize( 3531): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 3531): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3531): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3531): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3531): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3531): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3531): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3531): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3531): device_id = 0x0,
I/TZ: mc_tlc_communication( 3531): tlc_open() was called
I/TZ: mc_tlc_communication( 3531): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 3531): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3531): Opening the session
,I/TZ: mc_tlc_communication( 3531): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3531): Trustlet response is completed
,E/Watchdog( 3531): !@Sync 10
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 252, CUR = 38,
,I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 225s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 252, CUR = 36
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 250, CUR = 33
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 11
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 247, CUR = 32
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 245, CUR = 31
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 244, CUR = 29
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3531): [PWL] Off : 275s ago
,E/Watchdog( 3531): !@Sync 12
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 243, CUR = 30
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 242, CUR = 30
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 241, CUR = 29
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3531): waitForAlarm result :8
,E/Watchdog( 3531): !@Sync 13
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 241, CUR = 28,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 330s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3531): !@Sync 14
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 25
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 25
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 15
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 390s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 22
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 16
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 23
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 23,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 17
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3531): stay LED for fully charged
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 455s ago
,E/Watchdog( 3531): !@Sync 18
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 21
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 19
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3531): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3531): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3531): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3531): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 525s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3531): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3531): Killing 11329:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 21
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 22
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 19
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 600s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 23
,D/SSRM:n  ( 3531): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 239, CUR = 17
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 239, CUR = 18
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 24
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 239, CUR = 17
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 238, CUR = 17,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 238, CUR = 19
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 25
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 238, CUR = 17
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 680s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 237, CUR = 16
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 237, CUR = 14
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3531): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/LightsService( 3531): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3531): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3531): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/EventLogService( 4758): Aggregate from 1454459000797 (log), 1454459000797 (data)
,E/Watchdog( 3531): !@Sync 26
,I/Sensors ( 3531): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3531): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3531): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3531): unregisterListener ::   
D/LightsService( 3531): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 237, CUR = 15
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 236, CUR = 13
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 236, CUR = 13
,V/AlarmManager( 3531): waitForAlarm result :8
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 27
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 236, CUR = 16
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 235, CUR = 15
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 235, CUR = 15
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3531): !@Sync 28
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 235, CUR = 15
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3531): [PWL] Off : 765s ago
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 234, CUR = 15
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 234, CUR = 14
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 29
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 234, CUR = 13
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 233, CUR = 13
,V/AlarmManager( 3531): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 233, CUR = 13
,D/TimaService( 3531): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3531): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3531): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 233, CUR = 13
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 232, CUR = 12
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 232, CUR = 12
,V/AlarmManager( 3531): waitForAlarm result :8
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 31
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 232, CUR = 15
,I/PowerManagerService( 3531): [PWL] Off : 855s ago
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 231, CUR = 14
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 231, CUR = 14
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 32
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 231, CUR = 13
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 14,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 33
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 12,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3531): !@Sync 34
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 950s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3531): !@Sync 35
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 12,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 12,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3531): !@Sync 36
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 12
,E/Watchdog( 3531): !@Sync 37
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3531): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3531): !@Sync 38
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3531): stay LED for fully charged
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3531): !@Sync 39
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/TimaService( 3531): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3531): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3531): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3531): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3531): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3531): Updating Usage Statistics in DB @ 1454461292420
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
,W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrC,reateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3531): ::getAppControlDB: Exception to create DB
W/System.err( 3531): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3531): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3531): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3531): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3531): Done Updating Usage Statistics in DB @ 1454461292541
,E/Watchdog( 3531): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3531): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3531): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3531): !@Sync 41
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3531): [PWL] Off : 1155s ago
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3531): !@Sync 42
,I/art     ( 3531): Background sticky concurrent mark sweep GC freed 116395(10MB) AllocSpace objects, 318(4MB) LOS objects, 13% free, 49MB/57MB, paused 3.123ms total 115.273ms
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,D/BatteryService( 3531): stay LED for fully charged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3531): !@Sync 43
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3531): !@Sync 44
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8
,I/PowerManagerService( 3531): [PWL] Off : 1265s ago
,E/Watchdog( 3531): !@Sync 45
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3531): !@Sync 46
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3531): !@Sync 47
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3531): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-25
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3531): stay LED for fully charged
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3531): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3531): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3531): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3531): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3531): Plugged
,I/MotionRecognitionService( 3531): setPowerConnected  = true
,D/BatteryService( 3531): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3531): SIOP:: AP = 230, PST = 230, CUR = 8
,TIME-OUT KILL (timeout was 1200000ms)
```
