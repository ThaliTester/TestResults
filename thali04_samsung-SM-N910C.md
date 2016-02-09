#### Test 58741471ee11130_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
I/PowerManagerService( 3526): [PWL] Off : 105s ago
,--------- beginning of main
D/AndroidRuntime(11980): 
D/AndroidRuntime(11980): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11980): CheckJNI is OFF
D/AndroidRuntime(11980): readGMSProperty: start
D/AndroidRuntime(11980): readGMSProperty: already setted!!
D/AndroidRuntime(11980): readGMSProperty: end
D/AndroidRuntime(11980): addProductProperty: start
E/AffinityControl(11980): AffinityControl: registerfunction enter
D/AndroidRuntime(11980): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3526): inState():  stateMachine is null !!
I/PersonaManagerService( 3526): PersonaId don't exist
I/ActivityManager( 3526): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3526): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3526): mDVFSHelper.acquire()
D/FocusedStackFrame( 3526): Set to : 0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  (11998): MountEmulatedStorage()
I/libpersona(11998): KNOX_SDCARD checking this for 10645
E/Zygote  (11998): v2
I/libpersona(11998): KNOX_SDCARD not a persona
I/SELinux (11998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3526): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11998 uid=10645 gids={50645, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11998): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11980): Shutting down VM
D/PointerIcon( 3526): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3526): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3526): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3526): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2877): Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 862us total 23.795ms
D/TimaKeyStoreProvider(11998): TimaSignature is unavailable
D/ActivityThread(11998): Added TimaKeyStore provider
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3526): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3526): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager( 3526): Display changed displayId=0
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 917us total 18.467ms
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.105ms total 18.527ms
I/SurfaceFlinger( 2849): id=13 Removed Mauncher (5/8)
I/SurfaceFlinger( 2849): id=13 Removed Mauncher (-2/8)
D/ResourcesManager(11998): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 4000): updateVisibility : ActivityRecord{2e77ad2f token=android.os.BinderProxy@be1e570 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
I/WebViewFactory(11998): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11998): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11998): Loading: webviewchromium
,I/LibraryLoader(11998): Time to load native libraries: 6 ms (timestamps 808-814)
I/LibraryLoader(11998): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11998): Binding Chromium to main looper Looper (main, tid 1) {8a6b166}
,I/LibraryLoader(11998): Expected native library version number "",actual native library version number ""
I/chromium(11998): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11998): Initializing chromium process, renderers=0
,W/art     (11998): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11998): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11998): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11998): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11998): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11998): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11998): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11998): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11998): CordovaWebView is running on device made by: samsung
,W/art     (11998): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11998): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11998): performCreate Call secproduct feature valuefalse
D/Activity(11998): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11998): Render dirty regions requested: true
,D/ActivityManager( 3526): post active user change for 0
D/KnoxTimeoutHandler( 3526): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3526): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3526): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3526): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3526): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3526): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3526): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3526): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11998): Initialized EGL, version 1.4
,I/OpenGLRenderer(11998): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279811312 
,D/OpenGLRenderer(11998): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11998): Enabling debug mode 0
,D/mali_winsys(11998): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11998): updateVisibility : ActivityRecord{39b44016 token=android.os.BinderProxy@184a4a45 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3526): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3526): mDVFSHelper.release()
I/Timeline( 3526): Timeline: Activity_windows_visible id: ActivityRecord{12615ded u0 com.test.thalitest/.MainActivity t26} time:231247
,W/IInputConnectionWrapper(11998): showStatusIcon on inactive InputConnection
,I/Timeline(11998): Timeline: Activity_idle id: android.os.BinderProxy@184a4a45 time:231254
,I/chromium(11998): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11998): 
,D/JsMessageQueue(11998): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11998): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358473472
,I/chromium(11998): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11998): Initializing JXcore engine
W/jxcore-log(11998): JXcore engine is ready
,E/auditd  ( 4599): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3526): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3526): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3526): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11998): Starting JXcore engine
,W/jxcore-log(11998): Platform android
W/jxcore-log(11998): 
W/jxcore-log(11998): Process ARCH arm
W/jxcore-log(11998): 
,I/jxcore-log(11998): JXcore Cordova bridge is ready!
I/jxcore-log(11998): 
W/jxcore-log(11998): JXcore engine is started
I/jxcore-log(11998): Toggling radios to true
I/jxcore-log(11998): 
D/BluetoothAdapter(11998): enable()
D/BluetoothAdapter(11998): enable(): BT is already enabled..!
D/WifiService( 3526): New client listening to asynchronous messages
I/WifiManager(11998): packageName : com.test.thalitest
D/SecContentProvider( 3526): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3526): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3526): mCursor = null
D/WifiService( 3526): setWifiEnabled: true pid=11998, uid=10645
E/WifiService( 3526): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3526): Permission Denial: getCurrentUser() from pid=11998, uid=10645 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3526): Failed getting userId using ActivityManagerNative
W/WifiService( 3526): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11998, uid=10645 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3526): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3526): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3526): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3526): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3526): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3526): name = wifi_on
I/WifiService( 3526): disconnect: pid=11998, uid=10645
I/wpa_supplicant( 3836): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/wpa_supplicant( 3836): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3836): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3526): WifiStateMachine: Leaving Connected state
I/jxcore-log(11998): Radios toggled
I/jxcore-log(11998): 
I/wpa_supplicant( 3836): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3836): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3836): Disconnected - do not scan
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3526): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3526): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3526): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3526): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log(11998): My device name is: samsung-SM-N910C
I/jxcore-log(11998): 
E/WifiStateMachine( 3526): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3526): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3526): do suspend true
D/WifiP2pService( 3526): InactiveState{ what=143375 }
D/WifiP2pService( 3526): P2pEnabledState{ what=143375 }
D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
E/WifiStateMachine( 3526): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3526): updateNetworkInfo()
E/WifiConfigStore( 3526): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3526): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3526): updateNetworkInfo()
I/WifiTrafficPoller( 3526): evaluateTrafficStatsPolling
D/ConnectivityService( 3526): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
I/Hs20UtilService( 4098): Starting #8
I/Hs20UtilService( 4098): Message received 5007
E/WifiStateMachine( 3526): Start Disconnecting Watchdog 1
E/WifiStateMachine( 3526): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3526): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
D/NearbySettings( 8832): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8832): MountReceiver.onReceive - Start HandlerThread
E/WifiStateMachine( 3526): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3526): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3526): do suspend true
D/NearbySettings( 8832): MountReceiver.onReceive - Create mPrefHandler
D/WifiP2pService( 3526): InactiveState{ what=143375 }
D/WifiP2pService( 3526): P2pEnabledState{ what=143375 }
D/NearbySettings( 8832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8832): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiService( 3526): New client listening to asynchronous messages
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8832): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8832): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11469): NETWORK_STATE_CHANGED_ACTION
D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/ConnectivityService( 3526): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3526): Not allowed due to - mEnabled false
E/WifiStateMachine( 3526): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/ConnectivityService( 3526): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3526): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3526): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3526): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 6918): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 3983): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3526): updateConfiguredNetworkExpiration - currTime: 1455023369414
D/WifiStateMachine( 3526): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
I/wpa_supplicant( 3836): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3836): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3836): First Scan Start
E/WifiStateMachine( 3526): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3526): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine( 3526): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3526): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3526): NetworkAgent: NetworkAgent channel lost
I/wpa_supplicant( 3836): Scan requested (ret=0) - scan timeout 30 seconds
I/WifiTrafficPoller( 3526): evaluateTrafficStatsPolling
E/WifiStateMachine( 3526): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3526): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3526): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3526): mCursor = null
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/EntConnectivity( 3526): Not allowed due to - mEnabled false
D/ConnectivityService( 3526): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering( 3526): MasterInitialState.processMessage what=3
D/SmartBondingService( 3526): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3526): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
V/NetworkStats( 3526): updateIfacesLocked()
V/NetworkStats( 3526): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
D/SmartBondingService( 3526): getNetworkEnabled : wifi : true mobile : false
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3526): UpdateStatsForKnox
V/NetworkStats( 3526): performPollLocked() took 9ms
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
I/Hs20UtilService( 4098): Starting #9
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
V/NetworkStats( 3526): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3526): mCursor = null
I/Hs20UtilService( 4098): Message received 5007
D/NearbySettings( 8832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8832): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8832): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8832): MountReceiver.mPrefHandler - 7002
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
I/SignOutReceiver(11469): NETWORK_STATE_CHANGED_ACTION
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/ConnectivityService( 3526): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy( 3526): updateDataUsageMap
I/ApplicationPolicy( 3526): updateDataUsageMap  idList is null 
D/SmartBondingService( 3526): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3526): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3526): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/SLocation( 3526): No Active Data Connection
I/DBG_DM  ( 6191): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/DBG_DM  ( 6191): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  (12088): MountEmulatedStorage()
I/libpersona(12088): KNOX_SDCARD checking this for 10110
E/Zygote  (12088): v2
I/libpersona(12088): KNOX_SDCARD not a persona
I/SELinux (12088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12088): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12088 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(12088): TimaSignature is unavailable
D/ActivityThread(12088): Added TimaKeyStore provider
D/ResourcesManager(12088): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (12088): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12088): not using cross-dex optimization: ART in use
,I/art     (12088): Thread[1,tid=12088,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12088): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(12088): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(12088): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(12088): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12088): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12088): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(12088): loading pre-built fallback odex files
,V/MultiDexClassLoader(12088): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(12088): released odex store lock
D/DexLibLoader(12088): DexLibLoader.loadAll took 21 ms
,W/ca      (12088): Verify
,W/LightSharedPreferencesImpl(12088): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12088): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12088): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12088): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12088): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12088): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12088): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12088): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12088): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12088): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12088): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12088): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12088): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12088): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12088): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12088): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12088): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12088): 	... 10 more
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/Zygote  (12113): MountEmulatedStorage()
I/libpersona(12113): KNOX_SDCARD checking this for 1000
E/Zygote  (12113): v2
I/libpersona(12113): KNOX_SDCARD not a persona
I/SELinux (12113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12113): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12113 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3526): Killing 11147:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
W/appmanager(:<default>):b(12088): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/appmanager(:<default>):b(12088): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12113): TimaSignature is unavailable
,D/ActivityThread(12113): Added TimaKeyStore provider
,D/ResourcesManager(12113): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12113): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12113): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12113): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12113): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12113): sales region : global
I/PCWCLIENTTRACE_PushUtil(12113): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12113): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12113): noConnectivity : true
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(12088): Exposure of experiment com.facebook.common.network.l@1ea2180c occurred when no user was logged in
,E/Zygote  (12135): MountEmulatedStorage()
E/Zygote  (12135): v2
I/libpersona(12135): KNOX_SDCARD checking this for 10135
I/libpersona(12135): KNOX_SDCARD not a persona
,I/SELinux (12135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12135): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12135 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11244:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,W/BroadcastQueue( 3526): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2682d201 u0 ReceiverList{35946be8 12088 com.facebook.appmanager/10110/u0 remote:9bc310b}}
,W/BroadcastQueue( 3526): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2682d201 u0 ReceiverList{35946be8 12088 com.facebook.appmanager/10110/u0 remote:9bc310b}}
,D/TimaKeyStoreProvider(12135): TimaSignature is unavailable
,D/ActivityThread(12135): Added TimaKeyStore provider
,D/ResourcesManager(12135): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3526): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{23ef6c8a u0 ReceiverList{2e4a26f5 12088 com.facebook.appmanager/10110/u0 remote:3e88ec2c}}
,I/MusicStore(12135): Database version: 104
,D/ResourcesManager(12135): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12135): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12135): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12135): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12135): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12135): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d72ac5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12135): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12135): GMSCore installation verified
,I/ConfigStore(12135): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/ContextImpl(12088): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12088): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(12135): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/appmanager(:<default>):QuickExperimentControllerImpl(12088): Exposure of experiment com.facebook.imagepipeline.a.g@290ae8d5 occurred when no user was logged in
,I/AudioService( 3526): getStreamVolume 3 index 0
,W/appmanager(:<default>):QuickExperimentControllerImpl(12088): Exposure of experiment com.facebook.imagepipeline.a.d@1bb4f9b6 occurred when no user was logged in
I/MediaRouter(12135): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/art     (12088): Explicit concurrent mark sweep GC freed 42639(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 576us total 21.579ms
E/Zygote  (12170): MountEmulatedStorage()
I/libpersona(12170): KNOX_SDCARD checking this for 10002
E/Zygote  (12170): v2
I/libpersona(12170): KNOX_SDCARD not a persona
I/SELinux (12170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12170): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12170 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 3836): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3836): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3836): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3836): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3526): [1,455,023,370,499 ms] noteScanEnd no scan source
,V/analytics4a(12088): JNI_OnLoad called
V/analytics4a(12088): JNI_OnLoad complete
,I/NetworkMonitor(12135): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine( 3526): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3c642105 sup_state=SCANNING debouncing=false
,D/TimaKeyStoreProvider(12170): TimaSignature is unavailable
E/WifiStateMachine( 3526): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3526): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3526): setDetailed state send new extra info
D/ActivityThread(12170): Added TimaKeyStore provider
D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3526): mCursor = null
,I/ActivityManager( 3526): Killing 11260:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,W/appmanager(:<default>):m(12088): No feature status reporters found; is this dead code?
,E/lowmemorykiller( 2828): Error writing /proc/11260/oom_score_adj; errno=22
D/ResourcesManager(12170): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3526): Killing 11212:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3836): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3836): Associated with C0.AA.48
,E/WifiStateMachine( 3526): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine( 3526): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3526): setDetailed state send new extra info"NG700"
,I/ActivityManager( 3526): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12191 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  (12191): MountEmulatedStorage()
I/libpersona(12191): KNOX_SDCARD checking this for 1000
E/Zygote  (12191): v2
I/libpersona(12191): KNOX_SDCARD not a persona
I/SELinux (12191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3526): mCursor = null
,I/wpa_supplicant( 3836): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3526): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3526): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3526): mCursor = null
,D/TimaKeyStoreProvider(12191): TimaSignature is unavailable
,D/ActivityThread(12191): Added TimaKeyStore provider
,I/wpa_supplicant( 3836): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3836): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3526): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3526): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3836): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3836): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3836): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3836): Blacklist: Clear (temp) 
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3526): Network connection established
,D/WifiNative-HAL( 3526): callSECApiVoid - ID [50]
E/WifiStateMachine( 3526): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3526): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ResourcesManager(12191): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ConnectivityService( 3526): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3526): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3526): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3526): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3526): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3526): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3526): updateNetworkInfo()
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3526): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3526): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3526): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3526): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
E/WifiStateMachine( 3526): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3526): mCursor = null
,I/DIAGMON_AGENT(12191): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3526): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3526): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12191): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12191): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12191): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12191): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3526): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3526): do suspend false
,D/SecContentProvider2( 3526): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3526): InactiveState{ what=143375 }
D/WifiP2pService( 3526): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 3526): mCursor = null
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12210): MountEmulatedStorage()
E/Zygote  (12210): v2
I/libpersona(12210): KNOX_SDCARD checking this for 10012
I/libpersona(12210): KNOX_SDCARD not a persona
,I/SELinux (12210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12210): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12210 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12210): TimaSignature is unavailable
,D/ActivityThread(12210): Added TimaKeyStore provider
,D/ResourcesManager(12210): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3526): Killing 11329:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##31
,I/FOTA_Client(12210): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12210): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12210): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12226): MountEmulatedStorage()
E/Zygote  (12226): v2
I/libpersona(12226): KNOX_SDCARD checking this for 10021
I/libpersona(12226): KNOX_SDCARD not a persona
,I/SELinux (12226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12226): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12226 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3526): Killing 11314:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/11314/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12226): TimaSignature is unavailable
D/ActivityThread(12226): Added TimaKeyStore provider
,D/ResourcesManager(12226): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12226): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 14:09:30 GMT+01:00 2016
,I/KLMS-2.4.521: (12226): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12226): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12226): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12226): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12226): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12226): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12226): StateImplV2(): networkChangeListener().END
,E/Zygote  (12243): MountEmulatedStorage()
I/libpersona(12243): KNOX_SDCARD checking this for 10038
E/Zygote  (12243): v2
I/libpersona(12243): KNOX_SDCARD not a persona
,I/SELinux (12243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12243 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3526): Killing 11349:com.samsung.android.app.watchmanagerstub/u0a121 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12243): TimaSignature is unavailable
,D/ActivityThread(12243): Added TimaKeyStore provider
,D/ResourcesManager(12243): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12243): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  (12258): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12258): version 5.5.6 starting
,E/dhcpcd  (12258): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  (12259): MountEmulatedStorage()
I/libpersona(12259): KNOX_SDCARD checking this for 1000
,E/Zygote  (12259): v2
I/libpersona(12259): KNOX_SDCARD not a persona
I/SELinux (12259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12259 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12259): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 11365:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11365/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12259): TimaSignature is unavailable
,D/ActivityThread(12259): Added TimaKeyStore provider
,I/dhcpcd  (12258): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12258): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12258): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12258): bssid match
I/dhcpcd  (12258): wlan0: rebinding lease of 192.168.1.124
,D/ResourcesManager(12259): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12285): MountEmulatedStorage()
I/libpersona(12285): KNOX_SDCARD checking this for 10039
E/Zygote  (12285): v2
I/libpersona(12285): KNOX_SDCARD not a persona
I/SELinux (12285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12285): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12285 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11379:com.samsung.helphub/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12285): TimaSignature is unavailable
,D/ActivityThread(12285): Added TimaKeyStore provider
,D/ResourcesManager(12285): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12285): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12285): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12285): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12285): PushLog.txt file is not deleted.
D/SPPClientService(12285): PushLog.txt file is not deleted.
D/SPPClientService(12285): ============PushLog. stop!
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12302): MountEmulatedStorage()
E/Zygote  (12302): v2
I/libpersona(12302): KNOX_SDCARD checking this for 10045
I/libpersona(12302): KNOX_SDCARD not a persona
,I/SELinux (12302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12302): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12302 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11417:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8749(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 520us total 11.944ms
,E/SPPClientService(12285): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider(12302): TimaSignature is unavailable
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 476us total 8.819ms
D/ActivityThread(12302): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 268us total 8.361ms
,D/ResourcesManager(12302): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12302): [SSP] onCreated
,I/SA      (12302): [TPM] There is no property file
I/SA      (12302): [SCU] isHaveSA() - false
I/SA      (12302): [TPM] getModelProperty : null
I/SA      (12302): [TPM] getCSCProperty : null
I/SA      (12302): [DM] init START
I/SA      (12302): [DM] This device is not a Vodafone
I/SA      (12302): checkReactivationActive for LOLLIPOP
I/SA      (12302): checkReactivationActive for reactiveActive
I/SA      (12302): setSupportRL : true
I/SA      (12302): [SCU] isHaveSA() - false
I/SA      (12302): support phone number id : false
I/SA      (12302): [DM] init END
I/SA      (12302): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (12302): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12302): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (12302): [SLFUCHKMGR] constructor called
I/SA      (12302): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12302): [OR] == isSIMCardReady false ==
I/SA      (12302): [SCU] == networkStateCheck == false
I/SA      (12302): [OR] onReceive END
I/ActivityManager( 3526): Killing 11493:com.samsung.android.snote:provider/u0a160 (adj 15): bgCount ##31
V/DownloadManager( 5725): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12323): MountEmulatedStorage()
I/libpersona(12323): KNOX_SDCARD checking this for 10067
E/Zygote  (12323): v2
I/libpersona(12323): KNOX_SDCARD not a persona
,I/SELinux (12323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12323 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12323): TimaSignature is unavailable
,D/ActivityThread(12323): Added TimaKeyStore provider
,D/ResourcesManager(12323): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12323): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12323): Other Intent
,I/ActivityManager( 3526): Killing 11510:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): bgCount ##31
,D/accuweather( 5358): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5358): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5358): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5358): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5358): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5358): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5358): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12339): MountEmulatedStorage()
E/Zygote  (12339): v2
I/libpersona(12339): KNOX_SDCARD checking this for 1000
I/libpersona(12339): KNOX_SDCARD not a persona
,I/SELinux (12339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12339 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12339): TimaSignature is unavailable
,D/ActivityThread(12339): Added TimaKeyStore provider
,D/ResourcesManager(12339): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12339): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12339): premStatus:2
,I/KnoxUsageLogPro(12339): isEulaShown : false
I/KnoxUsageLogPro(12339): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12354): MountEmulatedStorage()
E/Zygote  (12354): v2
I/libpersona(12354): KNOX_SDCARD checking this for 10090
I/libpersona(12354): KNOX_SDCARD not a persona
,I/SELinux (12354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12354): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12354 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3526): Killing 11527:com.sec.android.widgetapp.tapandpay/u0a190 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12354): TimaSignature is unavailable
,D/ActivityThread(12354): Added TimaKeyStore provider
,D/ResourcesManager(12354): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12370): MountEmulatedStorage()
E/Zygote  (12370): v2
I/libpersona(12370): KNOX_SDCARD checking this for 10127
I/libpersona(12370): KNOX_SDCARD not a persona
,I/SELinux (12370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/dhcpcd  (12258): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/SELinux (12370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12370 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11563:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12370): TimaSignature is unavailable
,D/ActivityThread(12370): Added TimaKeyStore provider
,D/ResourcesManager(12370): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12370): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12370): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12370): stopCheckCategoryVersion
,I/dhcpcd  (12258): wlan0: leased 192.168.1.124 for 86400 seconds
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3526): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3526): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Zygote  (12388): MountEmulatedStorage()
I/libpersona(12388): KNOX_SDCARD checking this for 10136
E/Zygote  (12388): v2
I/libpersona(12388): KNOX_SDCARD not a persona
,I/SELinux (12388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12388): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12388 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11579:com.android.calendar/u0a164 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11579/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12388): TimaSignature is unavailable
,D/ActivityThread(12388): Added TimaKeyStore provider
,D/ResourcesManager(12388): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/SSRM:n  ( 3526): SIOP:: AP = 270, PST = 266, CUR = 69
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12388): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12388): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12388): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12388): Loading: webviewchromium
,I/LibraryLoader(12388): Time to load native libraries: 2 ms (timestamps 4973-4975)
I/LibraryLoader(12388): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12388): Binding Chromium to main looper Looper (main, tid 1) {49f3426}
,I/LibraryLoader(12388): Expected native library version number "",actual native library version number ""
,I/chromium(12388): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12388): Initializing chromium process, renderers=0
,W/art     (12388): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12388): Requires BLUETOOTH permission
W/chromium(12388): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12388): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12388): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12388): Starting up...
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12474): MountEmulatedStorage()
E/Zygote  (12474): v2
I/libpersona(12474): KNOX_SDCARD checking this for 10147
I/libpersona(12474): KNOX_SDCARD not a persona
,I/SELinux (12474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=12474 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (12474): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 11546:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,E/WifiStateMachine( 3526): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3526): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3526): do suspend true
,D/TimaKeyStoreProvider(12474): TimaSignature is unavailable
,D/ActivityThread(12474): Added TimaKeyStore provider
,D/WifiP2pService( 3526): InactiveState{ what=143375 }
D/WifiP2pService( 3526): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3526): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3526): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3526): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3526): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3526): Not connected state, yet.
E/WifiStateMachine( 3526): VerifyingLinkState enter
,D/WifiStateMachine( 3526): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3526): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3526): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3526): callSECApiInt - ID [210]
,E/WifiStateMachine( 3526): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
E/ConnectivityService( 3526): updateNetworkInfo()
,D/ConnectivityService( 3526): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3526): Adding iface wlan0 to network 503
,D/ResourcesManager(12474): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(12474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/WifiWatchdogStateMachine( 3526): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3526): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3526): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3526): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3526): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3526): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3526): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3526): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/WifiStateMachine( 3526): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3526): Now, connected state.
E/WifiStateMachine( 3526): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/ConnectivityService( 3526): Unexpected mtu value: 0, wlan0
E/WifiStateMachine( 3526): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,V/        ( 2845): QcRouteController
,I/WifiTrafficPoller( 3526): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3526): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3526): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3526): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3526): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
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
I/WifiStateMachine( 3526): REQUEST_POWER_SAVE_ON
V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,D/ConnectivityService( 3526): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3526): LTETest block dns file not exists
,D/ConnectivityService( 3526): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3526): updateNetworkInfo()
E/ConnectivityService( 3526): updateNetworkInfo()
D/ConnectivityService( 3526): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3526): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3526): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3526):    accepting network in place of null
,E/CSLegacyTypeTracker( 3526): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3526): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3526): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3526): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/TelephonyNetworkFactory( 3983): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 3526): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService( 3526): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering( 3526): MasterInitialState.processMessage what=3
D/SmartBondingService( 3526): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
,V/NetworkStats( 3526): updateIfacesLocked()
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
V/NetworkStats( 3526): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3526): UpdateStatsForKnox
D/EntConnectivity( 3526): Not allowed due to - mEnabled false
D/ConnectivityService( 3526): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
V/NetworkStats( 3526): performPollLocked() took 3ms
D/ConnectivityManager.CallbackHandler( 6918): CM callback handler got msg 524290
D/SmartBondingService( 3526): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
V/NetworkStats( 3526): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime( 3526): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/BatteryService( 3526): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3526): level:100, scale:100, status:5, health:2, present:true, voltage: 4292, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3526): online:4, current avg:-141, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-813
D/BatteryService( 3526): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3526): stay LED for fully charged
I/MotionRecognitionService( 3526): Plugged
I/MotionRecognitionService( 3526): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5630): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/System.out( 3526): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Zygote  (12522): MountEmulatedStorage()
I/libpersona(12522): KNOX_SDCARD checking this for 10150
E/Zygote  (12522): v2
I/libpersona(12522): KNOX_SDCARD not a persona
,I/SELinux (12522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12522 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(12522): TimaSignature is unavailable
,D/ActivityThread(12522): Added TimaKeyStore provider
,D/ResourcesManager(12522): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12522): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 13:09:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455023371983], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455023371958]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3526): Validated
,D/ConnectivityService( 3526): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3526): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3526): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3526): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3526): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 6918): CM callback handler got msg 524290
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
,D/QuickConnect(12522): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12522): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/art     ( 3526): Explicit concurrent mark sweep GC freed 96678(5MB) AllocSpace objects, 43(688KB) LOS objects, 23% free, 51MB/67MB, paused 1.211ms total 80.304ms
,I/QuickConnect(12522): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12539): MountEmulatedStorage()
I/libpersona(12539): KNOX_SDCARD checking this for 10178
E/Zygote  (12539): v2
I/libpersona(12539): KNOX_SDCARD not a persona
,I/SELinux (12539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12539 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 10852:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12539): TimaSignature is unavailable
,D/ActivityThread(12539): Added TimaKeyStore provider
,D/ResourcesManager(12539): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12539): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12539): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/BadgeProvider(11849): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(11849): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11849): sendNotify, [notify] : null
D/BadgeProvider(11849): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11849): update, [BadgeCount] : badgecount=0
D/BadgeProvider(11849): update, [UpdateCount] : 1
,D/Launcher.Model( 4000): reloadBadges entered.
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12567): MountEmulatedStorage()
I/libpersona(12567): KNOX_SDCARD checking this for 1000
E/Zygote  (12567): v2
I/libpersona(12567): KNOX_SDCARD not a persona
,I/SELinux (12567): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12567): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12567): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12567 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11680:com.android.vending/u0a31 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12567): TimaSignature is unavailable
,D/ActivityThread(12567): Added TimaKeyStore provider
,D/ResourcesManager(12567): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3526): Killing 11741:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,W/ActivityManager( 3526): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12585): MountEmulatedStorage()
I/libpersona(12585): KNOX_SDCARD checking this for 10013
E/Zygote  (12585): v2
I/libpersona(12585): KNOX_SDCARD not a persona
,I/SELinux (12585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12585): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3526): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12585 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ConnectivityService( 3526): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3526): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3526): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3526): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3526): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
,D/SmartBondingService( 3526): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6191): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6191): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5187): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5187): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/TimaKeyStoreProvider(12585): TimaSignature is unavailable
,D/ActivityThread(12585): Added TimaKeyStore provider
,I/NetworkMonitor(12135): type=WIFI subType= reason=null isConnected=true
,D/ResourcesManager(12585): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/GpsLocationProvider( 3526): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3526): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3526): mCursor = null
,D/WaitQueueForNetworkActivate(12585): notifyNetworkActivated
,W/ContextImpl(12585): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3526): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11998): 
,I/art     ( 4638): Explicit concurrent mark sweep GC freed 70794(3MB) AllocSpace objects, 38(1664KB) LOS objects, 34% free, 30MB/46MB, paused 893us total 39.988ms
,D/hcjo    (12585): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12585): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine(12585): exit::IDLE
D/InitializeManagerStateMachine(12585): entry::NETWORK_CHECK
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InitializeManagerStateMachine(12585): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12585): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12585): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12585): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12585): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12585): entry::SUCCESS
D/hcjo    (12585): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12585): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12585): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12585): exit::SUCCESS
D/InitializeManagerStateMachine(12585): entry::IDLE
,I/Hs20UtilService( 4098): Starting #10
,I/Hs20UtilService( 4098): Message received 5007
,D/NearbySettings( 8832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8832): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8832): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11469): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4098): Starting #11
,D/NearbySettings( 8832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 4098): Message received 5007
I/NearbySettings( 8832): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11469): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4098): Starting #12
,I/Hs20UtilService( 4098): Message received 5007
,I/ActivityManager( 3526): Killing 11771:com.sec.android.app.camera/u0a168 (adj 13): bgCount ##31
,D/NearbySettings( 8832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8832): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11469): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4098): Starting #13
,I/Hs20UtilService( 4098): Message received 5007
,D/NearbySettings( 8832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8832): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3526): callSECApi what=220
D/WifiStateMachine( 3526): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11469): NETWORK_STATE_CHANGED_ACTION
,W/art     (12474): Attempt to remove local handle scope entry from IRT, ignoring
,I/PCWCLIENTTRACE_PushUtil(12113): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12113): sales region : global
I/PCWCLIENTTRACE_PushUtil(12113): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12113): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2849): id=16 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3526): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3526
,I/DIAGMON_AGENT(12191): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12191): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10147
,I/FOTA_Client(12210): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12210): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12210): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12226): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 14:09:32 GMT+01:00 2016
,I/KLMS-2.4.521: (12226): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12226): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12226): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(12243): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12226): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12226): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12226): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12226): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12226): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12226): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onDestroy()
,E/SPPClientService(12285): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12302): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12302): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12302): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12302): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12302): [OR] == isSIMCardReady false ==
,I/SA      (12302): [SCU] == networkStateCheck == true
I/SA      (12302): [DM] getCountryCodeFromCSC : PL
I/SA      (12302): isChinaCountryCode : false
I/SA      (12302): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12302): [OR] == networkStateCheck true ==
I/SA      (12302): [OR] GetMyCountryZoneTask
I/SA      (12302): [OR] onReceive END
I/SA      (12302): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5725): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12302): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12302): [SSP] query invoked
,I/SCloudBackupReceiver(12323): Other Intent
,D/accuweather( 5358): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (12302): [TPMU] GetMccFromDB : null
I/SA      (12302): [SCU] getMccFromPreferece mcc = 260
I/SA      (12302): [TPM] isNoProxy(default) : true
,D/daemonapp( 3771): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,D/accuweather( 5358): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5358): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5358): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5358): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5358): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5358): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12339): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12339): premStatus:2
,I/KnoxUsageLogPro(12339): isEulaShown : false
I/KnoxUsageLogPro(12339): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12370): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12370): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12370): stopCheckCategoryVersion
,D/QuickConnect(12522): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12522): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12522): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/RCPManagerService( 3526): exchangeData() failure , invalid userId
,D/hcjo    (12585): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12585): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12585): exit::IDLE
D/InitializeManagerStateMachine(12585): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12585): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12585): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12585): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12585): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12585): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12585): entry::SUCCESS
D/hcjo    (12585): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService( 3526): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/hcjo    (12585): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12585): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12585): exit::SUCCESS
D/InitializeManagerStateMachine(12585): entry::IDLE
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11998): 
,I/SA      (12302): [RC New] Execute method=[GET] start
,I/SA      (12302): [RC New] Security=[true]
,I/System.out(12302): Thread-1715(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12302): Thread-1715(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12302): Thread-1715(ApacheHTTPLog):isShipBuild true
I/System.out(12302): Thread-1715(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11998): 
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11998): 
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11998): 
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11998): 
,E/WifiStateMachine( 3526): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3526): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3526): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/SmartBondingService( 3526): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
V/        ( 2845): QcRouteController
,D/SmartBondingService( 3526): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
D/SmartBondingService( 3526): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3526): route cmd failed: 
W/NetworkManagementService( 3526): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3526): '
W/NetworkManagementService( 3526): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3526): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3526): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3526): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3526): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3526): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3526): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3526): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3526): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3526): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3526): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityService( 3526): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6918): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6918): CM callback handler got msg 524295
,I/SA      (12302): [RC New] [v2liruge] api execute + 621
I/SA      (12302): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12302): AsyncTask #1 calls detatch()
,I/SA      (12302): [TPMU] getNetworkMcc : 
,I/SA      (12302): [SCU] saveMccToPreferece Start
I/SA      (12302): [SCU] RegionMCC : 260
I/SA      (12302): [SSP] query invoked
,I/SA      (12302): [TPMU] GetMccFromDB : null
I/SA      (12302): [SCU] getMccFromPreferece mcc = 260
I/SA      (12302): [SCU] saveMccToPreferece End
,I/SA      (12302): [RC New] executeRequest [v2liruge] end. 641
I/SA      (12302): [RC New] Execute end
I/SA      (12302): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12302): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine( 3526): REQUEST_POWER_SAVE_ON
,I/dhcpcd  (12258): wlan0: sending IPv6 Router Solicitation
,E/WifiStateMachine( 3526): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 4638): callingUid 10014, callindPid: 4638
,D/ResourcesManager(12135): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12135): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12135): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12135): Using the GMSCore's GoogleHttpClient
,D/WearableClient(12135): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12135): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(12135): Conditions not met for autocaching.
I/MusicLeanback(12135): Stop autocaching.
,D/WearableClient(12135): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12135): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12135): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12135): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12135): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@8851b72 that was originally bound here
E/ActivityThread(12135): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@8851b72 that was originally bound here
E/ActivityThread(12135): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12135): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12135): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12135): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12135): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12135): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12135): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12135): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12135): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12135): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12135): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12135): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12135): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12135): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12135): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12135): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12135): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12135): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12135): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12135): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12135): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12135): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12135): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12135): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12135): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11998): 
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11998): 
,I/jxcore-log(11998): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11998): 
,I/SurfaceFlinger( 2849): id=16 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=16 Removed Uoast (-2/9)
,D/PowerManagerService( 3526): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3526) eventTime = 239431
D/PowerManagerService( 3526): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3526 (0x0)
D/PowerManagerService( 3526): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3526, ws=WorkSource{10060}) (elapsedTime=3472)
,I/jxcore-log(11998): Test app app.js loaded
I/jxcore-log(11998): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11998): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14e60476 added. We now have 1 listener(s)
,I/jxcore-log(11998): BLE advertisement is supported
I/jxcore-log(11998): 
,I/chromium(11998): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11998): --= Surplus to requirements =--
I/jxcore-log(11998): 
I/jxcore-log(11998): ****TEST TOOK:  ms ****
I/jxcore-log(11998): 
I/jxcore-log(11998): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11998): 
,I/GAV4    (12388): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12656): 
D/AndroidRuntime(12656): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12656): CheckJNI is OFF
,D/AndroidRuntime(12656): readGMSProperty: start
D/AndroidRuntime(12656): readGMSProperty: already setted!!
,D/AndroidRuntime(12656): readGMSProperty: end
D/AndroidRuntime(12656): addProductProperty: start
,I/GAV2    (12474): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3526): Killing 11788:com.sec.android.widgetapp.digitalclock/u0a97 (adj 15): bgCount ##31
,E/AffinityControl(12656): AffinityControl: registerfunction enter
,D/AndroidRuntime(12656): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3526): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3526): START PACKAGE DELETE: observer{998910985}
D/PackageManager( 3526): pkg{<packageName>}
D/PackageManager( 3526): user{0}
D/PackageManager( 3526): caller{2000}
D/PackageManager( 3526): flags{3}
D/PersonaManagerService( 3526): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3526): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3526): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3526): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3526): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3526): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3526): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3526): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3526): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3526): !@killApplicatoin: 10645, uninstall pkg
,I/ActivityManager( 3526): Force stopping com.test.thalitest appid=10645 user=-1: uninstall pkg
,I/ActivityManager( 3526): Killing 11998:com.test.thalitest/u0a645 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3526):   Force finishing activity ActivityRecord{12615ded u0 com.test.thalitest/.MainActivity t26}
,I/SurfaceFlinger( 2849): id=15 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=15 Removed NainActivit (-2/8)
,D/PointerIcon( 3526): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3526): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3526): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3526): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3526): Skipping PackageSetting{19345cf9 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3526): Force stopping com.test.thalitest appid=10645 user=0: pkg removed
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/WifiService( 3526): Client connection lost with reason: 4
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3526): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4638): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 4442): mOCRHelper is null
,I/art     ( 8883): Explicit concurrent mark sweep GC freed 26878(1540KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 2.571ms total 69.363ms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 6918): Explicit concurrent mark sweep GC freed 25880(1490KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.060ms total 90.126ms
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 5187): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5187): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12684): MountEmulatedStorage()
E/Zygote  (12684): v2
I/libpersona(12684): KNOX_SDCARD checking this for 10063
I/libpersona(12684): KNOX_SDCARD not a persona
,I/SELinux (12684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12684 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3526): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3526): Admin package name: com.google.android.gms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 922us total 25.340ms
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 382us total 16.967ms
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 991us total 12.805ms
,D/TimaKeyStoreProvider(12684): TimaSignature is unavailable
,D/ActivityThread(12684): Added TimaKeyStore provider
,I/art     ( 3526): Explicit concurrent mark sweep GC freed 47389(3MB) AllocSpace objects, 8(128KB) LOS objects, 23% free, 51MB/67MB, paused 2.184ms total 170.604ms
,I/art     ( 3526): WaitForGcToComplete blocked for 56.809ms for cause Explicit
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(12684): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/SecContentProvider2( 3526): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3526): mCursor = null
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12684): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12684): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12684): packagename:com.test.thalitest
,I/KLMS-2.4.521: (12226): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 14:09:37 GMT+01:00 2016
,I/KLMS-2.4.521: (12226): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3526): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3526): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/RegisteredServicesCache( 3968): empty dynamic service
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12226): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12226): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12226): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12226): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12226): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,E/Zygote  (12701): MountEmulatedStorage()
E/Zygote  (12701): v2
I/libpersona(12701): KNOX_SDCARD checking this for 10106
I/libpersona(12701): KNOX_SDCARD not a persona
,I/SELinux (12701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12701 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (12701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 3526): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/RCPManager(12339):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3526):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3526): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/TimaKeyStoreProvider(12701): TimaSignature is unavailable
,E/Zygote  (12716): MountEmulatedStorage()
E/Zygote  (12716): v2
I/libpersona(12716): KNOX_SDCARD checking this for 10050
D/ActivityThread(12701): Added TimaKeyStore provider
I/libpersona(12716): KNOX_SDCARD not a persona
,I/SELinux (12716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/SELinux (12716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12716 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/art     ( 3526): Explicit concurrent mark sweep GC freed 7069(411KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 51MB/67MB, paused 2.509ms total 166.180ms
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider(12716): TimaSignature is unavailable
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
D/ActivityThread(12716): Added TimaKeyStore provider
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3526): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(12701): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/ResourcesManager( 3526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3526): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/libpersona(12731): KNOX_SDCARD checking this for 10101
E/Zygote  (12731): MountEmulatedStorage()
I/libpersona(12731): KNOX_SDCARD not a persona
E/Zygote  (12731): v2
I/ActivityManager( 3526): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12731 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux (12731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/SELinux (12731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/SELinux (12731): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/elm:14491(12701): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12701): ELMEngine.ELMEngine( context ).
,D/elm:14491(12701): MDMBridge.setEnterpriseBridge()
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3526): delete codoeFile: 
,I/AASAUninstall( 3526):  com.test.thalitest not target!
,D/PackageManager( 3526): result of delete: 1{998910985}
,D/AndroidRuntime(12656): Shutting down VM
,E/Zygote  (12746): MountEmulatedStorage()
E/Zygote  (12746): v2
I/libpersona(12746): KNOX_SDCARD checking this for 10183
I/libpersona(12746): KNOX_SDCARD not a persona
,I/SELinux (12746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3526): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12746 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/KLMS-2.4.521: (12226): KLMSIntentService(): listeningToPackageRemoved().END
D/PackageManager( 3526): [MSG] WRITE_PACKAGE_RESTRICTIONS
I/SELinux (12746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(12731): TimaSignature is unavailable
,D/ActivityThread(12731): Added TimaKeyStore provider
,D/ResourcesManager(12716): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12716): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12716): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12716): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12716): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12716): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12716): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12716): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12716): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12746): TimaSignature is unavailable
,D/ActivityThread(12746): Added TimaKeyStore provider
,I/KLMS-2.4.521: (12226): KLMSIntentService(): onDestroy()
,D/elm:14491(12701): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12701): ElmAgentService : onCreate()
,D/elm:14491(12701): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12701): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12701): MDMBridge.getInstance()
D/elm:14491(12701): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12701): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_SYSTEMReceiver(12113): mConnectivityHandler : connected
,D/ResourcesManager( 3526): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/PCWCLIENTTRACE_AccountUtil(12113): [hasSamungAccount] - No Samsung Account
,D/ResourcesManager(12731): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(12746): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/ActivityManager( 3526): Killing 11806:com.sec.android.widgetapp.dualclockdigital/u0a105 (adj 15): bgCount ##31
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog(12746): (284) automatic index on shooting_modes(title_id)
,I/CSTORAGE(12113): ================================================
I/CSTORAGE(12113):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12113): ================================================
,E/Zygote  (12766): MountEmulatedStorage()
E/Zygote  (12766): v2
I/libpersona(12766): KNOX_SDCARD checking this for 10019
I/libpersona(12766): KNOX_SDCARD not a persona
,I/SELinux (12766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/SELinux (12766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12113): [GetString-S]
E/art     (12113): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(12113): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12113): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12113): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12113): sales region : global
I/PCWCLIENTTRACE_PushUtil(12113): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12113): [ensureRegistration] - No Samsung account
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,I/ActivityManager( 3526): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12766 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/elm:14491(12701): ElmAgentService : onDestroy().
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/ActivityManager( 3526): Killing 11824:com.android.mms/u0a52 (adj 13): bgCount ##31
D/DocsApplication(12731): Installing DEX configuration.
D/PackageManager( 3526): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/TimaKeyStoreProvider(12766): TimaSignature is unavailable
,D/ActivityThread(12766): Added TimaKeyStore provider
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Books/Books.apk
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3526): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3526): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (12783): MountEmulatedStorage()
E/Zygote  (12783): v2
I/libpersona(12783): KNOX_SDCARD checking this for 10190
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/libpersona(12783): KNOX_SDCARD not a persona
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/SELinux (12783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3526): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12783 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (12783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/DexInstaller(12731): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/PackageInfoHelper(12731): Provided clientMode=RELEASE, packageInfo=PackageInfo{180b6af com.google.android.apps.docs}
,D/TAG     (12731): onCreate()
D/ResourcesManager( 3526): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/CrossAppStateProvider(12731): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/CrashAnrDetector( 3526): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3526): clearDefaults: com.test.thalitest
,I/ActivityManager( 3526): Killing 11864:com.wsomacp/u0a28 (adj 13): bgCount ##31
,D/RCPManagerService( 3526): PackageReceiver onReceive()
I/HarmonyEASService( 3526): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3526): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 3526): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3526): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3526): uID is 10645
D/JobSchedulerService( 3526): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3526): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3526): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3526): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3526): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3526): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3526): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3526): getBillingProfileForVpnEngine - end - null
,D/TaskPersister( 3526): removeObsoleteFile: deleting file=26_task.xml
,D/CountryDetector( 3526): No listener is left
,D/TimaKeyStoreProvider(12783): TimaSignature is unavailable
,D/ActivityThread(12783): Added TimaKeyStore provider
,D/ResourcesManager(12766): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(12783): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/NearbySource(12716): Nearby Source Create!
,D/NearbyContext(12716): Nearby Context Create!
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12766): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12766): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12766): onReceive() : package name is not s health. Return !!!
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12783): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12783): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:Utils(12783): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12783): Widget is not attached.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12716): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12716): Samsung link source created
,E/Zygote  (12802): MountEmulatedStorage()
E/Zygote  (12802): v2
I/libpersona(12802): KNOX_SDCARD checking this for 10022
I/libpersona(12802): KNOX_SDCARD not a persona
,I/SELinux (12802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3526): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12802 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3526): Killing 11758:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,I/SELinux (12802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Killing 11849:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/SQLiteLog(12716): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12716): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12716): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12716): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12716): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12716): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12716): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12716): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12716): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12716): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12716): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12716): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12716): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12716): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12716): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12716): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12716): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12716): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12716): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12716): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12716): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12716): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12716): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12716): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12716): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12716): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12716): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12716): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/PackageBroadcastService( 6918): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6918): Clearing selected account for com.test.thalitest
D/TimaKeyStoreProvider(12802): TimaSignature is unavailable
D/ActivityThread(12802): Added TimaKeyStore provider
D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3526): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3526): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3526): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3526): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3526): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3526): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3526): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/UsbHostManager( 3526): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3526): displayNotification : [09h,00h,00h]
D/ChimeraCfgMgr( 6918): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6918): Module APK com.google.android.play.games already loaded
D/WifiDisplayAdapter( 3526): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider(12716): getAllContactInfoList Start
D/ChimeraCfgMgr( 6918): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6918): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 6918): Removing dialog suppression flag for package com.test.thalitest
D/ResourcesManager(12802): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
D/UsbHostManager( 3526): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3526): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/SQLiteLog( 6918): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6918): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/MtpClient(12716): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12716): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,W/ResourcesManager(12802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager(12802): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/ResourcesManager(12802): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SQLiteLog( 6918): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6918): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 6918): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 6918): Process: com.google.android.gms, PID: 6918
E/AndroidRuntime( 6918): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6918): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6918): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 6918): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6918): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6918): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 6918): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/AndroidRuntime( 6918): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 6918): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 6918): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 6918): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/AndroidRuntime( 6918): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 6918): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 6918): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 6918): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 6918): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 6918): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6918): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6918): 	at java.lang.Thread.run(Thread.java:818)
,E/DriveAsyncService( 6918): disk I/O error (code 3850)
E/DriveAsyncService( 6918): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6918): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6918): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6918): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6918): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6918): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6918): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6918): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6918): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6918): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6918): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6918): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6918): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6918): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6918): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6918): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 6918): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3526): Removing device '/dev/input/event10' due to inotify event
,E/SQLiteDatabase( 6918): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6918): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6918): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6918): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6918): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6918): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6918): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 6918): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6918): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6918): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6918): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6918): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6918): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6918): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6918): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6918): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6918): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 6918): Sending signal. PID: 6918 SIG: 9
,E/SharedPreferencesImpl(12716): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/JavaBinder( 3526): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/EventHub( 3526): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog( 4638): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4638): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,I/LocationWidgetApplication(12802): onCreate() : start
D/AndroidRuntime( 4638): Shutting down VM
,D/LocationWidgetApplication(12802): countryCode = POLAND
,I/EventHub( 3526): Removing device '/dev/input/event8' due to inotify event
,E/AndroidRuntime( 4638): FATAL EXCEPTION: main
E/AndroidRuntime( 4638): Process: com.google.android.gms.persistent, PID: 4638
E/AndroidRuntime( 4638): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4638): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4638): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4638): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4638): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4638): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4638): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4638): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4638): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4638): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4638): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4638): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4638): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4638): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4638): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4638): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4638): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4638): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4638): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4638): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4638): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4638): 	... 9 more
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/DropBoxManagerService( 3526): Can't write: system_app_crash
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,D/LocationManagerService( 3526): getProviders()=[]
D/LocationManagerService( 3526): getProviders()=[passive]
,D/LocationManagerService( 3526): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(12802): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(12802): getLastUiLocationId() : mLastUiLocationId = -100
I/EventHub( 3526): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteLog(12802): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/Zygote  (12833): MountEmulatedStorage()
,E/Zygote  (12833): v2
I/libpersona(12833): KNOX_SDCARD checking this for 10052
E/SQLiteDatabase(12802): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12802): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12802): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12802): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12802): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12802): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12802): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12802): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12802): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12802): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12802): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12802): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/libpersona(12833): KNOX_SDCARD not a persona
D/AndroidRuntime(12802): Shutting down VM
,E/AndroidRuntime(12802): FATAL EXCEPTION: main
E/AndroidRuntime(12802): Process: com.sec.android.widgetapp.locationwidget, PID: 12802
E/AndroidRuntime(12802): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12802): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12802): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12802): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12802): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12802): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12802): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12802): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12802): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12802): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12802): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12802): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12802): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12802): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12802): 	... 9 more
I/SELinux (12833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3526): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12833 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (12833): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 3526): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@31424e4a)
D/ConnectivityService( 3526): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3526): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/EventHub( 3526): Removing device '/dev/input/event11' due to inotify event
,V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,I/ActivityManager( 3526): Process com.google.android.gms (pid 6918)(adj 0) has died(321,1159)
V/ApplicationPolicy( 3526): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10870ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10869ms
W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10868ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10866ms
,W/ActivityManager( 3526): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20865ms
,W/ActivityManager( 3526): Process com.google.android.gms has crashed too many times: killing!
,E/DropBoxManagerService( 3526): Can't write: system_app_crash
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,I/ActivityManager( 3526): Killing 4638:com.google.android.gms.persistent/u0a14 (adj 0): crash
,I/EventHub( 3526): Removing device '/dev/input/event12' due to inotify event
,V/BackupManagerService( 3526): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 3526): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,E/DropBoxManagerService( 3526): Can't write: system_app_crash
E/DropBoxManagerService( 3526): java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3526): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3526): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3526): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3526): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3526): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3526): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3526): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3526): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3526): 	... 5 more
,W/BroadcastQueue( 3526): Unable to launch app com.google.android.gms/10014 for broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }: process is bad
,D/TimaKeyStoreProvider(12833): TimaSignature is unavailable
D/ActivityThread(12833): Added TimaKeyStore provider
,I/ActivityManager( 3526): Killing 8832:com.android.settings/1000 (adj 15): bgCount ##31
,I/EventHub( 3526): Removing device '/dev/input/event13' due to inotify event
,I/PCWCLIENTTRACE_PushUtil(12113): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12113): sales region : global
I/PCWCLIENTTRACE_PushUtil(12113): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12113): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/EventHub( 3526): Removing device '/dev/input/event14' due to inotify event
,I/Process (12802): Sending signal. PID: 12802 SIG: 9
,D/WifiService( 3526): Client connection lost with reason: 4
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 3526): Location listener died
I/LocationManagerService( 3526): remove 1469ceea by com.google.android.gms
,D/GpsStatusListenerHelper( 3526): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@39d06884
,D/LocationManagerService( 3526): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService( 3526): Location listener died
I/LocationManagerService( 3526): remove 9154276 by com.google.android.gms
,D/WifiService( 3526): Client connection lost with reason: 4
D/LocationManagerService( 3526): provider request: passive ProviderRequest[ON interval=0]
,D/ResourcesManager(12833): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(12833): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12833): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12833): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12833): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12833): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12833): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  (12853): MountEmulatedStorage()
E/Zygote  (12853): v2
I/libpersona(12853): KNOX_SDCARD checking this for 10035
I/libpersona(12853): KNOX_SDCARD not a persona
,I/SELinux (12853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12853): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3526): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12853 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/ActivityThread(12088): Failed to find provider info for com.facebook.appmanager.installrecord
,I/ActivityManager( 3526): Process com.sec.android.widgetapp.locationwidget (pid 12802)(adj 9) has died(380,1159)
,D/TimaKeyStoreProvider(12853): TimaSignature is unavailable
,D/ActivityThread(12853): Added TimaKeyStore provider
,E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3526): checkUser: useridlist=null, currentuser=0

```
