#### Test 58751238ee11130_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime(11720): 
D/AndroidRuntime(11720): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11720): CheckJNI is OFF
D/AndroidRuntime(11720): readGMSProperty: start
D/AndroidRuntime(11720): readGMSProperty: already setted!!
D/AndroidRuntime(11720): readGMSProperty: end
D/AndroidRuntime(11720): addProductProperty: start
E/AffinityControl(11720): AffinityControl: registerfunction enter
D/AndroidRuntime(11720): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3523): inState():  stateMachine is null !!
I/PersonaManagerService( 3523): PersonaId don't exist
I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3523): mDVFSHelper.acquire()
D/FocusedStackFrame( 3523): Set to : 0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (11738): MountEmulatedStorage()
E/Zygote  (11738): v2
I/libpersona(11738): KNOX_SDCARD checking this for 10646
I/libpersona(11738): KNOX_SDCARD not a persona
I/SELinux (11738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11738 uid=10646 gids={50646, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11738): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11720): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11738): TimaSignature is unavailable
D/ActivityThread(11738): Added TimaKeyStore provider
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager( 3523): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(11738): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2850): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4001): updateVisibility : ActivityRecord{1a5c98de token=android.os.BinderProxy@3a0b87f9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4001): onTrimMemory. Level: 20
I/WebViewFactory(11738): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11738): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11738): Loading: webviewchromium
I/LibraryLoader(11738): Time to load native libraries: 4 ms (timestamps 8410-8414)
I/LibraryLoader(11738): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11738): Binding Chromium to main looper Looper (main, tid 1) {2f40e5a4}
,I/LibraryLoader(11738): Expected native library version number "",actual native library version number ""
I/chromium(11738): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11738): Initializing chromium process, renderers=0
,W/art     (11738): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11738): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11738): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11738): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11738): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11738): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11738): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11738): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11738): CordovaWebView is running on device made by: samsung
,W/art     (11738): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11738): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11738): performCreate Call secproduct feature valuefalse
,D/Activity(11738): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11738): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,W/ActivityManager( 3523): Activity pause timeout for ActivityRecord{d1a809a u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2850): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11738): Initialized EGL, version 1.4
,I/OpenGLRenderer(11738): HWUI protection enabled for context ,  &this =0xaf6ad1a0 ,&mEglDisplay = 1 , &mEglConfig = -1280868080 
,D/OpenGLRenderer(11738): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
,D/OpenGLRenderer(11738): Enabling debug mode 0
,D/mali_winsys(11738): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11738): updateVisibility : ActivityRecord{37affd4 token=android.os.BinderProxy@2051355b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
,I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{d1a809a u0 com.test.thalitest/.MainActivity t25} time:228970
,W/IInputConnectionWrapper(11738): showStatusIcon on inactive InputConnection
I/Timeline(11738): Timeline: Activity_idle id: android.os.BinderProxy@2051355b time:228977
,I/chromium(11738): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11738): 
,D/JsMessageQueue(11738): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11738): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358526720
,I/chromium(11738): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11738): Initializing JXcore engine
W/jxcore-log(11738): JXcore engine is ready
,E/auditd  ( 4606): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11738): Starting JXcore engine
,W/jxcore-log(11738): Platform android
W/jxcore-log(11738): 
W/jxcore-log(11738): Process ARCH arm
W/jxcore-log(11738): 
,I/jxcore-log(11738): JXcore Cordova bridge is ready!
I/jxcore-log(11738): 
,W/jxcore-log(11738): JXcore engine is started
,I/jxcore-log(11738): Toggling radios to true
I/jxcore-log(11738): 
,D/BluetoothAdapter(11738): enable()
,D/BluetoothAdapter(11738): enable(): BT is already enabled..!
,D/WifiService( 3523): New client listening to asynchronous messages
,I/WifiManager(11738): packageName : com.test.thalitest
D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: true pid=11738, uid=10646
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=11738, uid=10646 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): Failed getting userId using ActivityManagerNative
W/WifiService( 3523): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11738, uid=10646 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3523): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3523): name = wifi_on
I/WifiService( 3523): disconnect: pid=11738, uid=10646
,I/wpa_supplicant( 3810): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11738): Radios toggled
I/jxcore-log(11738): 
,I/jxcore-log(11738): My device name is: samsung-SM-N910C
I/jxcore-log(11738): 
,I/wpa_supplicant( 3810): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3810): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3810): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3810): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3810): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3810): Disconnected - do not scan
I/wpa_supplicant( 3810): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3523): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
,I/wpa_supplicant( 3810): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3810): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3810): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3810): First Scan Start
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,I/wpa_supplicant( 3810): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3523): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 4113): Starting #8
I/Hs20UtilService( 4113): Message received 5007
D/NearbySettings( 8687): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8687): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8687): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8687): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8687): DMSUtil.isNetworkConnected - flag-null, state-null
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8687): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8687): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8687): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524292
D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 6810): CM callback handler got msg 524292
I/SignOutReceiver( 9381): NETWORK_STATE_CHANGED_ACTION
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/NetworkStats( 3523): updateIfacesLocked()
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - currTime: 1455027869182
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,V/NetworkStats( 3523): performPollLocked() took 19ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
I/Hs20UtilService( 4113): Starting #9
D/SecContentProvider2( 3523): mCursor = null
,I/Hs20UtilService( 4113): Message received 5007
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NearbySettings( 8687): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8687): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8687): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8687): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8687): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver( 9381): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3523): updateDataUsageMap
,I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3523): No Active Data Connection
,I/DBG_DM  ( 6308): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6308): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11843): MountEmulatedStorage()
E/Zygote  (11843): v2
I/libpersona(11843): KNOX_SDCARD checking this for 1000
I/libpersona(11843): KNOX_SDCARD not a persona
,I/SELinux (11843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11843 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11843): TimaSignature is unavailable
,D/ActivityThread(11843): Added TimaKeyStore provider
,D/ResourcesManager(11843): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11843): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11843): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11843): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11843): noConnectivity : true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11859): MountEmulatedStorage()
E/Zygote  (11859): v2
I/libpersona(11859): KNOX_SDCARD checking this for 10135
I/libpersona(11859): KNOX_SDCARD not a persona
,I/SELinux (11859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11859): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11859 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10993:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11859): TimaSignature is unavailable
,D/ActivityThread(11859): Added TimaKeyStore provider
,D/ResourcesManager(11859): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11859): Database version: 104
,D/ResourcesManager(11859): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11859): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11859): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11859): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11859): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11859): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1adc06b8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11859): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11859): GMSCore installation verified
,I/ConfigStore(11859): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11859): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11859): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11859): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3523): getStreamVolume 3 index 0
,I/MediaRouter(11859): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11884): MountEmulatedStorage()
I/libpersona(11884): KNOX_SDCARD checking this for 10002
E/Zygote  (11884): v2
I/libpersona(11884): KNOX_SDCARD not a persona
,I/SELinux (11884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11884 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11859): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11884): TimaSignature is unavailable
,D/ActivityThread(11884): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11018:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ResourcesManager(11884): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3523): Killing 10297:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11904): MountEmulatedStorage()
E/Zygote  (11904): v2
I/libpersona(11904): KNOX_SDCARD checking this for 1000
I/libpersona(11904): KNOX_SDCARD not a persona
,I/SELinux (11904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11904): TimaSignature is unavailable
,D/ActivityThread(11904): Added TimaKeyStore provider
,D/ResourcesManager(11904): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11904): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11904): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11904): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/wpa_supplicant( 3810): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 3810): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3810): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3810): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3523): [1,455,027,870,208 ms] noteScanEnd no scan source
E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3e392cff sup_state=SCANNING debouncing=false
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11920): MountEmulatedStorage()
E/Zygote  (11920): v2
I/libpersona(11920): KNOX_SDCARD checking this for 10012
I/libpersona(11920): KNOX_SDCARD not a persona
,I/SELinux (11920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11920): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11920 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11920): TimaSignature is unavailable
,D/ActivityThread(11920): Added TimaKeyStore provider
,D/ResourcesManager(11920): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 3810): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,I/wpa_supplicant( 3810): Associated with C0.AA.48
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/ActivityManager( 3523): Killing 9484:com.android.mms/u0a52 (adj 13): bgCount ##31
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11920): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/wpa_supplicant( 3810): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3810): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3810): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3810): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3810): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3810): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3810): Blacklist: Clear (temp) 
I/wpa_supplicant( 3810): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  (11936): MountEmulatedStorage()
E/Zygote  (11936): v2
I/libpersona(11936): KNOX_SDCARD checking this for 10021
I/libpersona(11936): KNOX_SDCARD not a persona
,I/SELinux (11936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11936 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11057:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3523): Network connection established
,D/WifiNative-HAL( 3523): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3523): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3523): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3523): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3523): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3523): updateNetworkInfo()
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/CountryDetector( 3523): No listener is left
,D/TimaKeyStoreProvider(11936): TimaSignature is unavailable
,D/ActivityThread(11936): Added TimaKeyStore provider
,E/WifiStateMachine( 3523): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3523): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(11936): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/CommandListener( 2846): Setting iface cfg
E/WifiStateMachine( 3523): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:24:30 GMT+01:00 2016
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11936): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11936): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11936): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11936): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11936): StateImplV2(): networkChangeListener().END
,E/Zygote  (11953): MountEmulatedStorage()
I/libpersona(11953): KNOX_SDCARD checking this for 10038
E/Zygote  (11953): v2
I/libpersona(11953): KNOX_SDCARD not a persona
,I/SELinux (11953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11953 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3523): Killing 11073:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11953): TimaSignature is unavailable
,D/ActivityThread(11953): Added TimaKeyStore provider
,D/ResourcesManager(11953): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11953): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11968): MountEmulatedStorage()
E/Zygote  (11968): v2
I/libpersona(11968): KNOX_SDCARD checking this for 1000
I/libpersona(11968): KNOX_SDCARD not a persona
,I/SELinux (11968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11091:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend false
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 8749(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 289us total 10.436ms
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 440us total 9.498ms
,D/TimaKeyStoreProvider(11968): TimaSignature is unavailable
,D/ActivityThread(11968): Added TimaKeyStore provider
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 391us total 7.706ms
,D/ResourcesManager(11968): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11988): MountEmulatedStorage()
I/libpersona(11988): KNOX_SDCARD checking this for 10039
E/Zygote  (11988): v2
I/libpersona(11988): KNOX_SDCARD not a persona
,I/SELinux (11988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11988 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11988): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11108:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11988): TimaSignature is unavailable
D/ActivityThread(11988): Added TimaKeyStore provider
D/ResourcesManager(11988): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/SPPClientService(11988): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11988): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService(11988): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
D/SPPClientService(11988): PushLog.txt file is not deleted.
D/SPPClientService(11988): PushLog.txt file is not deleted.
D/SPPClientService(11988): ============PushLog. stop!
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12005): MountEmulatedStorage()
E/Zygote  (12005): v2
I/libpersona(12005): KNOX_SDCARD checking this for 10045
I/libpersona(12005): KNOX_SDCARD not a persona
I/SELinux (12005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12005): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12005 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11153:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
E/SPPClientService(11988): [[SystemStateMonitorService]] No Active Internet
D/TimaKeyStoreProvider(12005): TimaSignature is unavailable
D/ActivityThread(12005): Added TimaKeyStore provider
D/ResourcesManager(12005): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
I/SA      (12005): [SSP] onCreated
I/SA      (12005): [TPM] There is no property file
I/SA      (12005): [SCU] isHaveSA() - false
I/SA      (12005): [TPM] getModelProperty : null
I/SA      (12005): [TPM] getCSCProperty : null
I/SA      (12005): [DM] init START
I/SA      (12005): [DM] This device is not a Vodafone
I/SA      (12005): checkReactivationActive for LOLLIPOP
I/SA      (12005): checkReactivationActive for reactiveActive
I/SA      (12005): setSupportRL : true
I/SA      (12005): [SCU] isHaveSA() - false
I/SA      (12005): support phone number id : false
I/SA      (12005): [DM] init END
I/SA      (12005): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
E/dhcpcd  (12024): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/SA      (12005): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12005): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (12005): [SLFUCHKMGR] constructor called
I/dhcpcd  (12024): version 5.5.6 starting
I/SA      (12005): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12005): [OR] == isSIMCardReady false ==
E/dhcpcd  (12024): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/SA      (12005): [SCU] == networkStateCheck == false
I/SA      (12005): [OR] onReceive END
I/ActivityManager( 3523): Killing 11135:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
V/DownloadManager( 5480): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12032): MountEmulatedStorage()
E/Zygote  (12032): v2
I/libpersona(12032): KNOX_SDCARD checking this for 10067
I/libpersona(12032): KNOX_SDCARD not a persona
I/SELinux (12032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12032 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/dhcpcd  (12024): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12024): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12024): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12024): bssid match
I/dhcpcd  (12024): wlan0: rebinding lease of 192.168.1.124
D/TimaKeyStoreProvider(12032): TimaSignature is unavailable
D/ActivityThread(12032): Added TimaKeyStore provider
D/ResourcesManager(12032): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
I/sCloudBackupApp(12032): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12032): Other Intent
I/ActivityManager( 3523): Killing 11200:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
D/accuweather( 5218): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
D/accuweather( 5218): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5218): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5218): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5218): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5218): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5218): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12049): MountEmulatedStorage()
I/libpersona(12049): KNOX_SDCARD checking this for 1000
E/Zygote  (12049): v2
I/libpersona(12049): KNOX_SDCARD not a persona
I/SELinux (12049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider(12049): TimaSignature is unavailable
D/ActivityThread(12049): Added TimaKeyStore provider
D/ResourcesManager(12049): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(12049): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12049): premStatus:2
I/KnoxUsageLogPro(12049): isEulaShown : false
I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12064): MountEmulatedStorage()
I/libpersona(12064): KNOX_SDCARD checking this for 10090
E/Zygote  (12064): v2
I/libpersona(12064): KNOX_SDCARD not a persona
I/SELinux (12064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12064): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12064 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11185:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12064): TimaSignature is unavailable
D/ActivityThread(12064): Added TimaKeyStore provider
D/ResourcesManager(12064): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12080): MountEmulatedStorage()
I/libpersona(12080): KNOX_SDCARD checking this for 10127
E/Zygote  (12080): v2
I/libpersona(12080): KNOX_SDCARD not a persona
I/SELinux (12080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12080 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11218:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12080): TimaSignature is unavailable
D/ActivityThread(12080): Added TimaKeyStore provider
D/ResourcesManager(12080): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
D/KeyguardWallpaperUpdator(12080): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12080): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12080): stopCheckCategoryVersion
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12097): MountEmulatedStorage()
E/Zygote  (12097): v2
I/libpersona(12097): KNOX_SDCARD checking this for 10136
I/libpersona(12097): KNOX_SDCARD not a persona
I/SELinux (12097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12097): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12097 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11235:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12097): TimaSignature is unavailable
D/ActivityThread(12097): Added TimaKeyStore provider
D/ResourcesManager(12097): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/dhcpcd  (12024): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12097): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
I/dhcpcd  (12024): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
I/WebViewFactory(12097): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12097): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12097): Loading: webviewchromium
I/LibraryLoader(12097): Time to load native libraries: 3 ms (timestamps 2355-2358)
I/LibraryLoader(12097): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(12097): Binding Chromium to main looper Looper (main, tid 1) {3ea6d664}
I/LibraryLoader(12097): Expected native library version number "",actual native library version number ""
I/chromium(12097): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(12097): Initializing chromium process, renderers=0
W/art     (12097): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(12097): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(12097): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12097): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12097): Requires BLUETOOTH permission
I/NSApplication(12097): Starting up...
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (12186): MountEmulatedStorage()
I/libpersona(12186): KNOX_SDCARD checking this for 10150
E/Zygote  (12186): v2
I/libpersona(12186): KNOX_SDCARD not a persona
I/SELinux (12186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12186): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12186 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11250:com.samsung.helphub/1000 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12186): TimaSignature is unavailable
D/ActivityThread(12186): Added TimaKeyStore provider
D/ResourcesManager(12186): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
W/ResourcesManager(12186): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12186): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12186): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend true
D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3523): WifiStateMachine DHCP successful
E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3523): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3523): Not connected state, yet.
E/WifiStateMachine( 3523): VerifyingLinkState enter
D/QuickConnect(12186): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect(12186): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3523): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3523): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3523): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3523): callSECApiInt - ID [210]
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3523): Adding iface wlan0 to network 503
I/QuickConnect(12186): PeriphStartReceiver.onReceive - no need to start
D/WifiWatchdogStateMachine( 3523): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ConnectivityService( 3523): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/ConnectivityService( 3523): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine( 3523): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3523): Now, connected state.
E/WifiStateMachine( 3523): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/ConnectivityService( 3523): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3523): Unexpected mtu value: 0, wlan0
V/        ( 2846): QcRouteController
E/Zygote  (12205): MountEmulatedStorage()
I/libpersona(12205): KNOX_SDCARD checking this for 10178
E/Zygote  (12205): v2
I/libpersona(12205): KNOX_SDCARD not a persona
I/SELinux (12205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/        ( 2846): QcRouteController
I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12205 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/WifiStateMachine( 3523): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/ActivityManager( 3523): Killing 11333:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
E/WifiStateMachine( 3523): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
E/WifiStateMachine( 3523): ConnectedState Enter  mScreenOn=false scanperiod=20000
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3523): callSECApiVoid - ID [212]
,D/TimaKeyStoreProvider(12205): TimaSignature is unavailable
,D/ActivityThread(12205): Added TimaKeyStore provider
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,V/        ( 2846): QcRouteController
D/ResourcesManager(12205): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager(12205): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12205): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12205): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12205): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12205): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/        ( 2846): QcRouteController
V/        ( 2846): QcRouteController
V/        ( 2846): QcRouteController
D/ConnectivityService( 3523): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3523): LTETest block dns file not exists
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3523): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Connected
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3523):    accepting network in place of null
,D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3523): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3523): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ActivityManager( 3523): Failed to clear dns cache for: com.samsung.android.provider.shootingmodeprovider
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3523): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/ConnectivityManager.CallbackHandler( 6810): CM callback handler got msg 524290
,V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
V/NetworkStats( 3523): performPollLocked() took 2ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/Zygote  (12244): MountEmulatedStorage()
E/Zygote  (12244): v2
I/libpersona(12244): KNOX_SDCARD checking this for 10082
I/libpersona(12244): KNOX_SDCARD not a persona
,I/SELinux (12244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12244): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12244 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12244): TimaSignature is unavailable
,D/ActivityThread(12244): Added TimaKeyStore provider
,I/System.out( 3523): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Zygote  (12260): MountEmulatedStorage()
I/libpersona(12260): KNOX_SDCARD checking this for 1000
E/Zygote  (12260): v2
I/libpersona(12260): KNOX_SDCARD not a persona
I/SELinux (12260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11351:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11369:com.facebook.system/u0a10 (adj 13): bgCount ##31
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 287us total 10.418ms
,D/TimaKeyStoreProvider(12260): TimaSignature is unavailable
,D/ActivityThread(12260): Added TimaKeyStore provider
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 255us total 7.942ms
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 252us total 7.684ms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:24:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455027871504], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455027871481]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
,D/ConnectivityService( 3523): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6810): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 86269(4MB) AllocSpace objects, 41(656KB) LOS objects, 24% free, 49MB/65MB, paused 1.328ms total 85.425ms
,D/ResourcesManager(12244): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12260): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12244): onCreate
D/BadgeProvider(12244): DatabaseHelper
,I/ActivityManager( 3523): Killing 11395:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/BadgeProvider(12244): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12244): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12244): sendNotify, [notify] : null
D/BadgeProvider(12244): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 4001): reloadBadges entered.
D/BadgeProvider(12244): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12244): update, [UpdateCount] : 1
,E/JavaBinder( 3523): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3523): Exception when sending broadcast to ComponentInfo{com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.networkstatereceiver.NetworkStateReceiver}
W/BroadcastQueue( 3523): android.os.TransactionTooLargeException
W/BroadcastQueue( 3523): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3523): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3523): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3523): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3523): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3523): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3523): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3523): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12278): MountEmulatedStorage()
E/Zygote  (12278): v2
I/libpersona(12278): KNOX_SDCARD checking this for 10013
I/libpersona(12278): KNOX_SDCARD not a persona
,I/SELinux (12278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12278): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12278 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12278): TimaSignature is unavailable
,D/ActivityThread(12278): Added TimaKeyStore provider
,D/ResourcesManager(12278): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12278): notifyNetworkActivated
,W/ContextImpl(12278): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12278): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12278): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12278): exit::IDLE
D/InitializeManagerStateMachine(12278): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12278): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12278): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12278): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12278): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12278): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12278): entry::SUCCESS
D/hcjo    (12278): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12278): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12278): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12278): exit::SUCCESS
D/InitializeManagerStateMachine(12278): entry::IDLE
,I/ActivityManager( 3523): Killing 11427:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4113): Starting #10
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings( 8687): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8687): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8687): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8687): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver( 9381): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4113): Starting #11
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings( 8687): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8687): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver( 9381): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4113): Starting #12
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings( 8687): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8687): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 8687): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8687): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8687): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver( 9381): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4113): Starting #13
,D/NearbySettings( 8687): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8687): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 4113): Message received 5007
,I/WifiStateMachine( 3523): callSECApi what=220
D/WifiStateMachine( 3523): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver( 9381): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3523): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523
D/mali_winsys( 3695): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3523): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,V/        ( 2846): QcRouteController
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
W/NetworkManagementService( 3523): route cmd failed: 
W/NetworkManagementService( 3523): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3523): '
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3523): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3523): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3523): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3523): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3523): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3523): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6810): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6810): CM callback handler got msg 524295
W/ResourceType( 5346): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5346): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/DBG_DM  ( 6308): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/NetworkMonitor(11859): type=WIFI subType= reason=null isConnected=true
I/DBG_DM  ( 6308): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11920): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11920): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:24:31 GMT+01:00 2016
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11936): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11936): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SO_AGENT(11953): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11936): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
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
I/SA      (12005): [DM] getCountryCodeFromCSC : PL
I/SA      (12005): isChinaCountryCode : false
I/SA      (12005): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12005): [OR] == networkStateCheck true ==
I/SA      (12005): [OR] GetMyCountryZoneTask
I/SA      (12005): [OR] onReceive END
,I/SA      (12005): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5480): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12005): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12005): [SSP] query invoked
,I/SCloudBackupReceiver(12032): Other Intent
,I/SA      (12005): [TPMU] GetMccFromDB : null
I/SA      (12005): [SCU] getMccFromPreferece mcc = 260
I/SA      (12005): [TPM] isNoProxy(default) : true
,D/accuweather( 5218): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3773): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5218): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5218): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5218): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5218): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5218): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5218): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12049): premStatus:2
,I/KnoxUsageLogPro(12049): isEulaShown : false
I/KnoxUsageLogPro(12049): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12080): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12080): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12080): stopCheckCategoryVersion
,D/QuickConnect(12186): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12186): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12186): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/hcjo    (12278): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12278): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12278): exit::IDLE
D/InitializeManagerStateMachine(12278): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12278): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12278): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12278): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12278): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12278): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12278): entry::SUCCESS
D/hcjo    (12278): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12278): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12278): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12278): exit::SUCCESS
D/InitializeManagerStateMachine(12278): entry::IDLE
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11738): 
,I/SA      (12005): [RC New] Execute method=[GET] start
,I/SA      (12005): [RC New] Security=[true]
,I/System.out(12005): Thread-1670(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12005): Thread-1670(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12005): Thread-1670(ApacheHTTPLog):isShipBuild true
I/System.out(12005): Thread-1670(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3523): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11738): 
,I/SA      (12005): [RC New] [v2liruge] api execute + 623
I/SA      (12005): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12005): AsyncTask #1 calls detatch()
,I/SA      (12005): [TPMU] getNetworkMcc : 
,I/SA      (12005): [SCU] saveMccToPreferece Start
I/SA      (12005): [SCU] RegionMCC : 260
I/SA      (12005): [SSP] query invoked
,I/SA      (12005): [TPMU] GetMccFromDB : null
I/SA      (12005): [SCU] getMccFromPreferece mcc = 260
I/SA      (12005): [SCU] saveMccToPreferece End
,I/SA      (12005): [RC New] executeRequest [v2liruge] end. 643
I/SA      (12005): [RC New] Execute end
I/SA      (12005): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12005): [OR] GetMyCountryZoneTask Success
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 255, CUR = 37
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-216, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-210
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5624): Disconnected process message: 10
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3523): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  (12024): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4631): callingUid 10014, callindPid: 4631
,D/ResourcesManager(11859): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11859): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11859): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11859): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11859): Conditions not met for autocaching.
I/MusicLeanback(11859): Stop autocaching.
,D/WearableClient(11859): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11859): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11859): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11859): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11859): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11859): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11859): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2bcbf190 that was originally bound here
E/ActivityThread(11859): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2bcbf190 that was originally bound here
E/ActivityThread(11859): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11859): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11859): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11859): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11859): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11859): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11859): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11859): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11859): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11859): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11859): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11859): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11859): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11859): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11859): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11859): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11859): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11859): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11859): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11859): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11859): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11859): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11859): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11859): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11859): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3523): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3523) eventTime = 236565
D/PowerManagerService( 3523): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523 (0x0)
D/PowerManagerService( 3523): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3523, ws=WorkSource{10060}) (elapsedTime=3475)
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11738): 
,I/jxcore-log(11738): Test app app.js loaded
I/jxcore-log(11738): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11738): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37c3f334 added. We now have 1 listener(s)
,I/jxcore-log(11738): BLE advertisement is supported
I/jxcore-log(11738): 
,I/chromium(11738): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV4    (12097): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log(11738): --= Surplus to requirements =--
I/jxcore-log(11738): 
I/jxcore-log(11738): ****TEST TOOK:  ms ****
I/jxcore-log(11738): 
I/jxcore-log(11738): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11738): 
,D/AndroidRuntime(12333): 
D/AndroidRuntime(12333): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12333): CheckJNI is OFF
,D/AndroidRuntime(12333): readGMSProperty: start
D/AndroidRuntime(12333): readGMSProperty: already setted!!
,D/AndroidRuntime(12333): readGMSProperty: end
D/AndroidRuntime(12333): addProductProperty: start
,E/AffinityControl(12333): AffinityControl: registerfunction enter
,D/AndroidRuntime(12333): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3523): START PACKAGE DELETE: observer{510185503}
D/PackageManager( 3523): pkg{<packageName>}
D/PackageManager( 3523): user{0}
D/PackageManager( 3523): caller{2000}
D/PackageManager( 3523): flags{3}
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3523): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3523): !@killApplicatoin: 10646, uninstall pkg
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10646 user=-1: uninstall pkg
I/ActivityManager( 3523): Killing 11738:com.test.thalitest/u0a646 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{d1a809a u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2850): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2850): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3523): Skipping PackageSetting{32287dd3 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10646 user=0: pkg removed
,D/WifiService( 3523): Client connection lost with reason: 4
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 9100): Explicit concurrent mark sweep GC freed 31645(1743KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.602ms total 50.939ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 9381): Explicit concurrent mark sweep GC freed 1875(106KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 1.060ms total 70.476ms
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4502): mOCRHelper is null
,W/GeofencerStateMachine( 4631): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/LWLocationManager(11410): getDeviceLocationId :  id = -100
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): mConnectivityHandler : connected
,D/LocationWidgetApplication(11410): getLastUiLocationId() : mLastUiLocationId = -100
,E/Zygote  (12359): MountEmulatedStorage()
I/libpersona(12359): KNOX_SDCARD checking this for 10063
E/Zygote  (12359): v2
I/libpersona(12359): KNOX_SDCARD not a persona
,W/PCWCLIENTTRACE_AccountUtil(11843): [hasSamungAccount] - No Samsung Account
I/SELinux (12359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SELinux (12359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12359 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
,W/ResourceType( 5346): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5346): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/TimaKeyStoreProvider(12359): TimaSignature is unavailable
,D/ActivityThread(12359): Added TimaKeyStore provider
,D/ResourcesManager(11410): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/CSTORAGE(11843): ================================================
I/CSTORAGE(11843):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11843): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11843): [GetString-S]
,D/ResourcesManager(12359): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
E/art     (11843): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11843): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11843): [GetString-E]
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11843): [ensureRegistration] - No Samsung account
,D/VRSetupWizardStub/PackageIntentReceiver(12359): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12359): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12359): packagename:com.test.thalitest
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 36716(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 49MB/65MB, paused 2.125ms total 180.327ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(11410): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/art     ( 3523): WaitForGcToComplete blocked for 177.028ms for cause Explicit
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:24:37 GMT+01:00 2016
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (11936): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11410): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (11936): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11936): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (12379): MountEmulatedStorage()
E/Zygote  (12379): v2
I/libpersona(12379): KNOX_SDCARD checking this for 10106
I/libpersona(12379): KNOX_SDCARD not a persona
I/SELinux (12379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11410): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SELinux (12379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/SELinux (12379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12379 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.521: (11936): KLMSIntentService(): PACKAGE_REMOVED
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11936): KLMSIntentService(): listeningToPackageRemoved().START
,D/TimaKeyStoreProvider(12379): TimaSignature is unavailable
,I/KLMS-2.4.521: (11936): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11410): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ActivityThread(12379): Added TimaKeyStore provider
,E/Zygote  (12394): MountEmulatedStorage()
E/Zygote  (12394): v2
I/libpersona(12394): KNOX_SDCARD checking this for 10050
I/libpersona(12394): KNOX_SDCARD not a persona
,I/SELinux (12394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12394 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,I/SELinux (12394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManager(12049):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3523):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
,D/RegisteredServicesCache( 3963): empty dynamic service
,D/TimaKeyStoreProvider(12394): TimaSignature is unavailable
D/ResourcesManager(12379): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ActivityThread(12394): Added TimaKeyStore provider
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12379): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12379): ELMEngine.ELMEngine( context ).
D/elm:14491(12379): MDMBridge.setEnterpriseBridge()
,E/Zygote  (12409): MountEmulatedStorage()
E/Zygote  (12409): v2
I/libpersona(12409): KNOX_SDCARD checking this for 10101
I/libpersona(12409): KNOX_SDCARD not a persona
,I/SELinux (12409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12409 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12409): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/TimaKeyStoreProvider(12409): TimaSignature is unavailable
,D/ActivityThread(12409): Added TimaKeyStore provider
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/elm:14491(12379): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12379): ElmAgentService : onCreate()
,D/elm:14491(12379): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12379): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12379): MDMBridge.getInstance()
D/elm:14491(12379): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(12394): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/elm:14491(12379): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.4.521: (11936): KLMSIntentService(): listeningToPackageRemoved().END
W/ResourcesManager(12394): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12394): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/Zygote  (12427): MountEmulatedStorage()
E/Zygote  (12427): v2
I/libpersona(12427): KNOX_SDCARD checking this for 10183
I/libpersona(12427): KNOX_SDCARD not a persona
,I/SELinux (12427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12427 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (12427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/elm:14491(12379): ElmAgentService : onDestroy().
,I/KLMS-2.4.521: (11936): KLMSIntentService(): onDestroy()
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider(12427): TimaSignature is unavailable
,D/ActivityThread(12427): Added TimaKeyStore provider
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 9657(595KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 4.514ms total 176.062ms
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11410): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(12409): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,E/Zygote  (12442): MountEmulatedStorage()
E/Zygote  (12442): v2
I/libpersona(12442): KNOX_SDCARD checking this for 10019
I/libpersona(12442): KNOX_SDCARD not a persona
,I/SELinux (12442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(11410): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/SELinux (12442): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12442 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/TimaKeyStoreProvider(12442): TimaSignature is unavailable
,D/ActivityThread(12442): Added TimaKeyStore provider
,D/ResourcesManager(12427): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11410): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,I/ActivityManager( 3523): Killing 11442:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11410:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/ResourcesManager(12442): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/SQLiteLog(12427): (284) automatic index on shooting_modes(title_id)
,D/PackageManager( 3523): delete codoeFile: 
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12442): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12442): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12442): onReceive() : package name is not s health. Return !!!
,I/AASAUninstall( 3523):  com.test.thalitest not target!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/PackageManager( 3523): result of delete: 1{510185503}
,D/AndroidRuntime(12333): Shutting down VM
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Zygote  (12460): MountEmulatedStorage()
E/Zygote  (12460): v2
I/libpersona(12460): KNOX_SDCARD checking this for 10190
I/libpersona(12460): KNOX_SDCARD not a persona
,I/SELinux (12460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12460 uid=10190 gids={50190, 9997} abi=armeabi-v7a
I/SELinux (12460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/DocsApplication(12409): Installing DEX configuration.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/TimaKeyStoreProvider(12460): TimaSignature is unavailable
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ActivityThread(12460): Added TimaKeyStore provider
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/PackageManager( 3523): findPreferredActivity: No PreferredActivities set
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12475): MountEmulatedStorage()
,E/Zygote  (12475): v2
I/libpersona(12475): KNOX_SDCARD checking this for 10022
I/libpersona(12475): KNOX_SDCARD not a persona
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/SELinux (12475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12475 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/SELinux (12475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/SELinux (12475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11481:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,D/DexInstaller(12409): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/PackageInfoHelper(12409): Provided clientMode=RELEASE, packageInfo=PackageInfo{2b79ca55 com.google.android.apps.docs}
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/TAG     (12409): onCreate()
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/ActivityManager( 3523): Killing 10855:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/TimaKeyStoreProvider(12475): TimaSignature is unavailable
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ActivityThread(12475): Added TimaKeyStore provider
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/CrossAppStateProvider(12409): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3523): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3523): onPackageRemoved : com.test.thalitest
,D/ResourcesManager(12460): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/RCPManagerService( 3523): PackageReceiver onReceive()
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10646
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=25_task.xml
,D/NearbySource(12394): Nearby Source Create!
,D/NearbyContext(12394): Nearby Context Create!
,D/ResourcesManager(12475): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12460): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12460): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,W/ResourcesManager(12475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12475): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12475): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/TapandpayWidget:Utils(12460): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12460): Widget is not attached.
,I/ActivityManager( 3523): Killing 10435:com.android.vending/u0a31 (adj 13): bgCount ##31
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12394): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12394): Samsung link source created
,D/PackageBroadcastService( 6810): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6810): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6810): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6810): Module APK com.google.android.play.games already loaded
,I/LocationWidgetApplication(12475): onCreate() : start
,D/LocationWidgetApplication(12475): countryCode = POLAND
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ChimeraCfgMgr( 6810): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6810): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 6810): Removing dialog suppression flag for package com.test.thalitest
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/LocationManagerService( 3523): getProviders()=[]
D/LocationManagerService( 3523): getProviders()=[passive]
D/LocationManagerService( 3523): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(12475): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12475): getLastUiLocationId() : mLastUiLocationId = -100
,I/LocationWidgetFuctionData(12475): readDB
,D/gH_CompatibleDatabase( 6810): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6810): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6810): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6810): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/LocationWidgetFuctionData(12475): selectedAppSize: 3
I/LocationWidgetFuctionData(12475): configPlaceList aroundMeItems
,D/ContactProvider(12394): getAllContactInfoList Start
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/gH_CompatibleDatabase( 6810): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6810): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6810): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6810): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6810): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6810): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6810): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6810): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
E/Zygote  (12498): MountEmulatedStorage()
E/Zygote  (12498): v2
I/libpersona(12498): KNOX_SDCARD checking this for 10003
I/libpersona(12498): KNOX_SDCARD not a persona
,I/SELinux (12498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/gH_CompatibleDatabase( 6810): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 3523): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12498 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,I/SELinux (12498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/NetworkScheduler.SchedulerReceiver( 4631): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4631): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12515): MountEmulatedStorage()
,E/Zygote  (12515): v2
I/libpersona(12515): KNOX_SDCARD checking this for 10052
I/libpersona(12515): KNOX_SDCARD not a persona
,I/SELinux (12515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12515): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12498): TimaSignature is unavailable
,D/ActivityThread(12498): Added TimaKeyStore provider
,I/ActivityManager( 3523): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12515 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 846us total 24.126ms
,D/TimaKeyStoreProvider(12515): TimaSignature is unavailable
,D/ActivityThread(12515): Added TimaKeyStore provider
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 304us total 16.968ms
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 6810): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6810): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6810): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6810): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6810): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6810): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 306us total 9.599ms
E/PhenotypeInitializer( 6810): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6810): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6810): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6810): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6810): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 6810): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6810): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ResourcesManager(12498): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
E/GMPM-SVC( 6810): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 6810): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/Zygote  (12533): MountEmulatedStorage()
E/Zygote  (12533): v2
I/libpersona(12533): KNOX_SDCARD checking this for 10031
I/libpersona(12533): KNOX_SDCARD not a persona
,I/ActivityManager( 3523): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12533 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 3523): Killing 12244:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,I/SELinux (12533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
,D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
,I/SELinux (12533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12533): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
,E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityThread(10398): Failed to find provider info for com.facebook.appmanager.installrecord
,D/TimaKeyStoreProvider(12533): TimaSignature is unavailable
,D/ActivityThread(12533): Added TimaKeyStore provider
,D/ResourcesManager(12515): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/UserAnalysis.PlaceProvider(12498): PlaceProvider onCreate()
,E/SQLiteLog( 6810): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6810): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/MtpClient(12394): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12394): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/AndroidRuntime( 6810): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6810): Process: com.google.android.gms, PID: 6810
E/AndroidRuntime( 6810): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6810): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6810): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 6810): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6810): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6810): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 6810): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 6810): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6810): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6810): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6810): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6810): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6810): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6810): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ResourcesManager(12515): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12515): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12515): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12533): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/UserAnalysis.SecureDbManager(12498): Key for secure DB is newly created
,D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
D/UserAnalysis.SecurePlaceDbHelper(12498): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12498): Create SecureDbHelper
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/IntelligenceServiceApplication(12498): onCreate()
,E/SQLiteLog(12498): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12498): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(12498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12498): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:210)
E/SQLiteDatabase(12498): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.getPrivacyGuardedFilter(PlaceProvider.java:989)
E/SQLiteDatabase(12498): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:581)
E/SQLiteDatabase(12498): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12498): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12498): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12498): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper(12498): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(12498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12498): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12498): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:210)
E/SQLiteOpenHelper(12498): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.getPrivacyGuardedFilter(PlaceProvider.java:989)
E/SQLiteOpenHelper(12498): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:581)
E/SQLiteOpenHelper(12498): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(12498): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(12498): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(12498): 	at android.os.Binder.execTransact(Binder.java:446)
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
D/ContactProvider(12394): getAllContactInfoList End
,I/syncContacts(12394): thread: 1733, sync time = 368
W/SQLiteOpenHelper(12498): Opened privacy in read-only mode
,E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3523): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3523): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3523): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3523): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3523): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3523): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3523): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3523): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3523): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3523): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3523): 	... 5 more
,W/FileUtils( 6810): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 6810): Failed to open Apps corpus file.
,E/Icing   ( 6810): Failed to open Apps corpus file.
,E/SharedPreferencesImpl( 6810): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
,I/Icing   ( 6810): doRemovePackageData com.test.thalitest
,E/SQLiteLog(12498): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/Place.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12498): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/Place.db'.
E/SQLiteDatabase(12498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:906)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:879)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
E/SQLiteDatabase(12498): 	at android.database.sqlite.SQLiteSecureOpenHelper.getReadableDatabase(SQLiteSecureOpenHelper.java:280)
E/SQLiteDatabase(12498): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:587)
E/SQLiteDatabase(12498): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(12498): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(12498): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(12498): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(12498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(12498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:311)
W/System.err(12498): 	at android.database.sqlite.SQLiteConnection.openSecure(SQLiteConnection.java:243)
W/System.err(12498): 	at android.database.sqlite.SQLiteConnectionPool.openSecureConnectionLocked(SQLiteConnectionPool.java:519)
W/System.err(12498): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:217)
W/System.err(12498): 	at android.database.sqlite.SQLiteConnectionPool.openSecure(SQLiteConnectionPool.java:198)
W/System.err(12498): 	at android.database.sqlite.SQLiteDatabase.openInnerSecureDatabase(SQLiteDatabase.java:906)
W/System.err(12498): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:879)
W/System.err(12498): 	at android.database.sqlite.SQLiteDatabase.openSecureDatabase(SQLiteDatabase.java:746)
W/System.err(12498): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:346)
W/System.err(12498): 	at android.database.sqlite.SQLiteSecureOpenHelper.getReadableDatabase(SQLiteSecureOpenHelper.java:280)
W/System.err(12498): 	at com.samsung.android.intelligenceservice.useranalysis.PlaceProvider.query(PlaceProvider.java:587)
W/System.err(12498): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(12498): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(12498): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(12498): 	at android.os.Binder.execTransact(Binder.java:446)
D/UserAnalysis.PlaceProvider(12498): query - query() SQLiteException!!!
,E/LocationWidgetFuctionData(12475): configPlaceListItems : cursor is null!!
I/Process ( 6810): Sending signal. PID: 6810 SIG: 9
I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
D/Mms/MmsApp(12515): [start]    onCreate() consume time = 0.0
D/Mms/ArtClassLoader(12515): init before art
D/Mms/ArtClassLoader(12515): init [DONE] art
I/ActivityManager( 3523): Killing 8687:com.android.settings/1000 (adj 13): bgCount ##31
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
,I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver(11843): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/Mms/TelephonyPermission(12515): start operation mode monitor,
,D/ResourcesManager(12515): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12515): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  (12561): MountEmulatedStorage()
,E/Zygote  (12561): v2
I/libpersona(12561): KNOX_SDCARD checking this for 10035
I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
I/libpersona(12561): KNOX_SDCARD not a persona
,I/SELinux (12561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12561 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (12561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11884:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
,D/ConnectivityService( 3523): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@30b9117f)
,D/ConnectivityService( 3523): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3523): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog(12409): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,D/WifiService( 3523): Client connection lost with reason: 4
,E/SQLiteDatabase(12409): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12409): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12409): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12409): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12409): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12409): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12409): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12409): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12409): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12409): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12409): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12409): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12409): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12409): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12409): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12409): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12409): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12409): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12409): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12409): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12409): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12409): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12409): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12409): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12409): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12409): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12409): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12409): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12409): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12409): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12409): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12409): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12409): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12409): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12409): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12409): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12409): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12409): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12409): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12409): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12409): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12409): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12409): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12409): Opened ClientFlag.db in read-only mode
I/ActivityManager( 3523): Process com.google.android.gms (pid 6810)(adj 0) has died(316,1165)
D/Mms/TelephonyPermission(12515): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12515): isDefault true
I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 1000ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20997ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30996ms
D/Mms/MmsApp(12515): onCreate() com.android.mms
,D/TimaKeyStoreProvider(12561): TimaSignature is unavailable
D/ActivityThread(12561): Added TimaKeyStore provider
E/SQLiteLog(12409): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12409): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12409): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12409): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12409): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12409): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12409): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12409): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12409): Process: com.google.android.apps.docs, PID: 12409
E/AndroidRuntime(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12409): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12409): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12409): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12409): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12409): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12409): 	at aFp.run(AbstractDatabaseInstance.java:471)
I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,D/Mms/MmsApp(12515): [start]    initCountryIso consume time = 233.635917
,D/CountryDetector( 3523): The first listener is added
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,E/SQLiteLog(12409): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12409): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12409): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12409): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12409): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12409): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12409): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12409): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12409): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12409): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12409): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12409): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12409): 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12409): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12409): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12409): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12409): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12409): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12409): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12409): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12409): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12409): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12409): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12409): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12409): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12409): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12409): Opened ClientFlag.db in read-only mode
,E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3523): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3523): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3523): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3523): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3523): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3523): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3523): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3523): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3523): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3523): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3523): 	... 5 more
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp(12515): [end]    initCountryIso consume time = 42.582541
D/Mms/MmsConfig(12515): [start]    MmsConfig.init() consume time = 1.2045
,D/Mms/MmsConfig(12515): before partial update
,D/ResourcesManager(12561): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  (12587): MountEmulatedStorage()
E/Zygote  (12587): v2
I/libpersona(12587): KNOX_SDCARD checking this for 1000
I/libpersona(12587): KNOX_SDCARD not a persona
,I/SELinux (12587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Process (12409): Sending signal. PID: 12409 SIG: 9
,D/Mms/MmsConfig(12515): Load Resize quality : 80
W/BroadcastQueue( 3523): Skipping deliver [background] BroadcastRecord{3741e776 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{c8e7a38 12409 com.google.android.apps.docs/10101/u0 remote:1d57469b}: process crashing
,D/Mms/MmsConfig(12515):  enable multiwindow = true

```
