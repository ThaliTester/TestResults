#### Test 54970261fc259e9_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AndroidRuntime(11762): 
D/AndroidRuntime(11762): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11762): CheckJNI is OFF
D/AndroidRuntime(11762): readGMSProperty: start
D/AndroidRuntime(11762): readGMSProperty: already setted!!
D/AndroidRuntime(11762): readGMSProperty: end
D/AndroidRuntime(11762): addProductProperty: start
E/AffinityControl(11762): AffinityControl: registerfunction enter
D/AndroidRuntime(11762): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3500): inState():  stateMachine is null !!
I/PersonaManagerService( 3500): PersonaId don't exist
I/ActivityManager( 3500): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3500): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager( 3500): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3500): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3500): mDVFSHelper.acquire()
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (11780): MountEmulatedStorage()
I/libpersona(11780): KNOX_SDCARD checking this for 10535
E/Zygote  (11780): v2
I/libpersona(11780): KNOX_SDCARD not a persona
I/SELinux (11780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3500): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11780 uid=10535 gids={50535, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11780): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11762): Shutting down VM
D/PointerIcon( 3500): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3500): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3500): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3500): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11780): TimaSignature is unavailable
D/ActivityThread(11780): Added TimaKeyStore provider
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11780): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6290): updateVisibility : ActivityRecord{29ef25ed token=android.os.BinderProxy@7c81716 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11780): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11780): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11780): Loading: webviewchromium
I/LibraryLoader(11780): Time to load native libraries: 4 ms (timestamps 6799-6803)
I/LibraryLoader(11780): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11780): Binding Chromium to main looper Looper (main, tid 1) {29d04394}
I/LibraryLoader(11780): Expected native library version number "",actual native library version number ""
I/chromium(11780): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11780): Initializing chromium process, renderers=0
,W/art     (11780): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11780): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11780): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11780): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11780): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11780): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11780): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11780): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11780): CordovaWebView is running on device made by: samsung
,W/art     (11780): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11780): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11780): performCreate Call secproduct feature valuefalse
D/Activity(11780): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11780): Render dirty regions requested: true
,D/ActivityManager( 3500): post active user change for 0
D/KnoxTimeoutHandler( 3500): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3500): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3500): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3500): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3500): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3500): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3500): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3500): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11780): Initialized EGL, version 1.4
,I/OpenGLRenderer(11780): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279688432 
,D/OpenGLRenderer(11780): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11780): Enabling debug mode 0
D/mali_winsys(11780): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11780): updateVisibility : ActivityRecord{1055b9c4 token=android.os.BinderProxy@391cfa0b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3500): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3500): Timeline: Activity_windows_visible id: ActivityRecord{a941212 u0 com.test.thalitest/.MainActivity t26} time:137171
W/ActivityManager( 3500): mDVFSHelper.release()
,W/IInputConnectionWrapper(11780): showStatusIcon on inactive InputConnection
,I/Timeline(11780): Timeline: Activity_idle id: android.os.BinderProxy@391cfa0b time:137182
,D/JsMessageQueue(11780): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11780): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11780): 
,D/jxcore_app_log(11780): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358526720
D/JX-Cordova(11780): jxcore cordova android initializing
,W/jxcore-log(11780): Initializing JXcore engine
W/jxcore-log(11780): JXcore engine is ready
,W/jxcore-log(11780): Starting JXcore engine
,E/auditd  ( 4601): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3500): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3500): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11780): Platform android
W/jxcore-log(11780): 
W/jxcore-log(11780): Process ARCH arm
W/jxcore-log(11780): 
,I/jxcore-log(11780): JXcore Cordova bridge is ready!
I/jxcore-log(11780): 
W/jxcore-log(11780): JXcore engine is started
,I/jxcore-log(11780): Toggling radios to true
I/jxcore-log(11780): 
,D/BluetoothAdapter(11780): enable()
D/BluetoothAdapter(11780): enable(): BT is already enabled..!
D/WifiService( 3500): New client listening to asynchronous messages
I/WifiManager(11780): packageName : com.test.thalitest
D/SecContentProvider( 3500): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3500): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3500): mCursor = null
D/WifiService( 3500): setWifiEnabled: true pid=11780, uid=10535
E/WifiService( 3500): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3500): Permission Denial: getCurrentUser() from pid=11780, uid=10535 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3500): Failed getting userId using ActivityManagerNative
W/WifiService( 3500): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11780, uid=10535 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3500): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3500): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3500): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3500): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3500): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3500): name = wifi_on
I/WifiService( 3500): disconnect: pid=11780, uid=10535
I/wpa_supplicant( 3811): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/wpa_supplicant( 3811): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3811): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3811): wlan0: State: DISCONNECTED -> DISCONNECTED
I/jxcore-log(11780): Radios toggled
I/jxcore-log(11780): 
E/WifiStateMachine( 3500): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3811): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3811): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3811): Disconnected - do not scan
I/wpa_supplicant( 3811): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3500): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3500): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3500): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3500): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3500): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3500): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3500): do suspend true
,D/WifiP2pService( 3500): InactiveState{ what=143375 }
,D/WifiP2pService( 3500): P2pEnabledState{ what=143375 }
D/CommandListener( 2846): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
E/WifiStateMachine( 3500): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3500): updateNetworkInfo()
,D/ConnectivityService( 3500): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3500): updateNetworkInfo()
D/ConnectivityService( 3500): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3500): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3500): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,I/Hs20UtilService( 4111): Starting #8
I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8857): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8857): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8857): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8857): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8857): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3500): New client listening to asynchronous messages
,I/NearbySettings( 8857): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8857): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8857): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11447): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3500): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3500): Not allowed due to - mEnabled false
D/ConnectivityService( 3500): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3696): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3500): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3500): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3500): Start Disconnecting Watchdog 1
D/ConnectivityService( 3500): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3983): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3500): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3500): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3500): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3500): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3500): do suspend true
,D/ConnectivityManager.CallbackHandler( 6864): CM callback handler got msg 524292
,D/ConnectivityService( 3500): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/EntConnectivity( 3500): Not allowed due to - mEnabled false
,D/Tethering( 3500): MasterInitialState.processMessage what=3
D/SmartBondingService( 3500): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3500): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/WifiP2pService( 3500): InactiveState{ what=143375 }
D/WifiP2pService( 3500): P2pEnabledState{ what=143375 }
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3696): getUpdateDataNetType(): 0
V/NetworkStats( 3500): updateIfacesLocked()
D/StatusBar.NetworkController( 3696): getUpdateDataNetType(): mDataTypeBrand = LTE
V/NetworkStats( 3500): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 3696): updateDataNetType()
D/StatusBar.NetworkController( 3696): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3696): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
V/NetworkStats( 3500): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3500): UpdateStatsForKnox
,D/SmartBondingService( 3500): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3500): performPollLocked() took 7ms
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3696): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3696): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3696): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3500): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/WifiStateMachine( 3500): updateConfiguredNetworkExpiration - currTime: 1452011249476
D/WifiStateMachine( 3500): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
,I/wpa_supplicant( 3811): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3811): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3811): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3811): First Scan Start
,I/WifiTrafficPoller( 3500): evaluateTrafficStatsPolling
E/WifiStateMachine( 3500): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3500): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/wpa_supplicant( 3811): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3500): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3500): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3500): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3500): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3500): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3500): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3500): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3500): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
I/Hs20UtilService( 4111): Starting #9
,I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8857): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8857): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8857): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8857): MountReceiver.mPrefHandler - 7002
,D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
,I/SignOutReceiver(11447): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3983): FileWriteThread : threadType = 3
,D/ConnectivityService( 3500): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3500): updateDataUsageMap
I/ApplicationPolicy( 3500): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3500): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3500): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3500): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3500): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3500): No Active Data Connection
,I/DBG_DM  ( 6290): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6290): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11870): MountEmulatedStorage()
I/libpersona(11870): KNOX_SDCARD checking this for 10110
E/Zygote  (11870): v2
I/libpersona(11870): KNOX_SDCARD not a persona
,I/SELinux (11870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3500): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11870 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11870): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11870): TimaSignature is unavailable
,D/ActivityThread(11870): Added TimaKeyStore provider
,D/ResourcesManager(11870): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11870): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11870): not using cross-dex optimization: ART in use
,I/art     (11870): Thread[1,tid=11870,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11870): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11870): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11870): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11870): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
,D/DexLibLoader(11870): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11870): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11870): loading pre-built fallback odex files
,V/MultiDexClassLoader(11870): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11870): released odex store lock
D/DexLibLoader(11870): DexLibLoader.loadAll took 18 ms
,W/ca      (11870): Verify
,W/LightSharedPreferencesImpl(11870): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11870): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11870): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11870): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11870): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11870): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11870): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11870): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11870): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11870): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11870): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11870): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11870): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11870): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11870): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11870): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11870): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11870): 	... 10 more
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (11895): MountEmulatedStorage()
I/libpersona(11895): KNOX_SDCARD checking this for 1000
E/Zygote  (11895): v2
I/libpersona(11895): KNOX_SDCARD not a persona
I/SELinux (11895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11895): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11895 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3500): Killing 10960:com.android.mms/u0a52 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11870): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 384us total 10.209ms
D/TimaKeyStoreProvider(11895): TimaSignature is unavailable
D/ActivityThread(11895): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 269us total 8.259ms
W/appmanager(:<default>):b(11870): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 271us total 8.671ms
D/ResourcesManager(11895): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG(11895): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11895): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11895): new DMDBOpenHelper instance
D/CountryDetector( 3500): No listener is left
I/PCWCLIENTTRACE_PushUtil(11895): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11895): sales region : global
I/PCWCLIENTTRACE_PushUtil(11895): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11895): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11895): noConnectivity : true
W/appmanager(:<default>):QuickExperimentControllerImpl(11870): Exposure of experiment com.facebook.common.network.l@38b16e95 occurred when no user was logged in
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (11918): MountEmulatedStorage()
E/Zygote  (11918): v2
I/libpersona(11918): KNOX_SDCARD checking this for 10135
I/libpersona(11918): KNOX_SDCARD not a persona
I/SELinux (11918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3500): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11918 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11918): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Killing 11068:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
W/BroadcastQueue( 3500): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{b527304 u0 ReceiverList{3977b317 11870 com.facebook.appmanager/10110/u0 remote:17b66b96}}
W/BroadcastQueue( 3500): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{b527304 u0 ReceiverList{3977b317 11870 com.facebook.appmanager/10110/u0 remote:17b66b96}}
D/TimaKeyStoreProvider(11918): TimaSignature is unavailable
D/ActivityThread(11918): Added TimaKeyStore provider
D/ResourcesManager(11918): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/BroadcastQueue( 3500): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{252fc0a5 u0 ReceiverList{1b631e9c 11870 com.facebook.appmanager/10110/u0 remote:2e67ee0f}}
I/MusicStore(11918): Database version: 104
D/ResourcesManager(11918): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager(11918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp (11918): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread(11918): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11918): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@269cd5a8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11918): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11918): GMSCore installation verified
I/ConfigStore(11918): Config Database version: 1
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11918): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11918): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11918): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11870): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11870): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
D/WifiDisplayAdapter( 3500): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 3500): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService( 3500): getStreamVolume 3 index 0
I/MediaRouter(11918): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
W/appmanager(:<default>):QuickExperimentControllerImpl(11870): Exposure of experiment com.facebook.imagepipeline.a.g@3a18531b occurred when no user was logged in
W/appmanager(:<default>):QuickExperimentControllerImpl(11870): Exposure of experiment com.facebook.imagepipeline.a.d@9d0fc64 occurred when no user was logged in
E/Zygote  (11952): MountEmulatedStorage()
E/Zygote  (11952): v2
I/libpersona(11952): KNOX_SDCARD checking this for 10002
I/libpersona(11952): KNOX_SDCARD not a persona
I/SELinux (11952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11952 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WifiDisplayAdapter( 3500): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/art     (11870): Explicit concurrent mark sweep GC freed 49830(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 882us total 25.600ms
W/appmanager(:<default>):m(11870): No feature status reporters found; is this dead code?
D/TimaKeyStoreProvider(11952): TimaSignature is unavailable
D/ActivityThread(11952): Added TimaKeyStore provider
I/NetworkMonitor(11918): type=WIFI subType= reason=null isConnected=false
I/ActivityManager( 3500): Killing 11084:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
D/ResourcesManager(11952): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
I/wpa_supplicant( 3811): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3811): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3811): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3811): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3500): [1,452,011,250,559 ms] noteScanEnd no scan source
E/WifiStateMachine( 3500): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@22600e89 sup_state=SCANNING debouncing=false
E/WifiStateMachine( 3500): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3500): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3500): setDetailed state send new extra info
D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
I/ActivityManager( 3500): Killing 11099:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (11974): MountEmulatedStorage()
E/Zygote  (11974): v2
I/libpersona(11974): KNOX_SDCARD checking this for 1000
I/libpersona(11974): KNOX_SDCARD not a persona
I/SELinux (11974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider(11974): TimaSignature is unavailable
D/ActivityThread(11974): Added TimaKeyStore provider
D/ResourcesManager(11974): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/DIAGMON_AGENT(11974): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/wpa_supplicant( 3811): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3500): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3500): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3811): Associated with C0.AA.48
E/WifiStateMachine( 3500): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
I/wpa_supplicant( 3811): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3500): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3500): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
I/wpa_supplicant( 3811): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3811): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3500): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3500): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3811): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3811): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3811): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3811): Blacklist: Clear (temp) 
I/wpa_supplicant( 3811): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3500): Network connection established
D/WifiNative-HAL( 3500): callSECApiVoid - ID [50]
E/WifiStateMachine( 3500): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine( 3500): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
E/WifiStateMachine( 3500): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3500): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3500): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3500): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3500): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3500): updateNetworkInfo()
D/ConnectivityService( 3500): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3500): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3500): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3500): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3500): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/DIAGMON_AGENT(11974): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
D/CommandListener( 2846): Setting iface cfg
E/WifiStateMachine( 3500): Start Dhcp Watchdog 2
D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
I/DIAGMON_AGENT(11974): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
E/WifiStateMachine( 3500): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3500): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (11991): MountEmulatedStorage()
I/libpersona(11991): KNOX_SDCARD checking this for 10012
E/Zygote  (11991): v2
I/libpersona(11991): KNOX_SDCARD not a persona
I/SELinux (11991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11991): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11991 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider(11991): TimaSignature is unavailable
D/ActivityThread(11991): Added TimaKeyStore provider
D/ResourcesManager(11991): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
E/WifiStateMachine( 3500): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3500): do suspend false
D/SecContentProvider2( 3500): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3500): mCursor = null
D/WifiP2pService( 3500): InactiveState{ what=143375 }
D/WifiP2pService( 3500): P2pEnabledState{ what=143375 }
I/ActivityManager( 3500): Killing 10929:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
E/lowmemorykiller( 2829): Error writing /proc/10929/oom_score_adj; errno=22
I/FOTA_Client(11991): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(11991): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(11991): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (12007): MountEmulatedStorage()
I/libpersona(12007): KNOX_SDCARD checking this for 10021
E/Zygote  (12007): v2
I/libpersona(12007): KNOX_SDCARD not a persona
I/SELinux (12007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12007 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3500): Killing 11160:com.wsomacp/u0a28 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12007): TimaSignature is unavailable
D/ActivityThread(12007): Added TimaKeyStore provider
D/ResourcesManager(12007): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/KLMS-2.4.521: (12007): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 17:27:30 GMT+01:00 2016
I/KLMS-2.4.521: (12007): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12007): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12007): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12007): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12007): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12007): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12007): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (12007): StateImplV2(): networkChangeListener().END
E/Zygote  (12023): MountEmulatedStorage()
I/libpersona(12023): KNOX_SDCARD checking this for 10038
E/Zygote  (12023): v2
I/libpersona(12023): KNOX_SDCARD not a persona
I/SELinux (12023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12023 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (12007): KLMSIntentService(): onDestroy()
I/ActivityManager( 3500): Killing 11176:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
E/lowmemorykiller( 2829): Error writing /proc/11176/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12023): TimaSignature is unavailable
D/ActivityThread(12023): Added TimaKeyStore provider
D/ResourcesManager(12023): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
I/SO_AGENT(12023): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (12038): MountEmulatedStorage()
E/Zygote  (12038): v2
I/libpersona(12038): KNOX_SDCARD checking this for 1000
I/libpersona(12038): KNOX_SDCARD not a persona
I/SELinux (12038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12038 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3500): Killing 11143:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12038): TimaSignature is unavailable
D/ActivityThread(12038): Added TimaKeyStore provider
D/ResourcesManager(12038): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/dhcpcd  (12057): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12057): version 5.5.6 starting
,E/dhcpcd  (12057): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12063): MountEmulatedStorage()
E/Zygote  (12063): v2
I/libpersona(12063): KNOX_SDCARD checking this for 10039
I/libpersona(12063): KNOX_SDCARD not a persona
,I/SELinux (12063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3500): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12063 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12063): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Killing 11219:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12063): TimaSignature is unavailable
I/dhcpcd  (12057): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12057): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12057): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12057): bssid match
I/dhcpcd  (12057): wlan0: rebinding lease of 192.168.1.124
D/ActivityThread(12063): Added TimaKeyStore provider
,D/ResourcesManager(12063): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12063): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12063): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12063): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12063): PushLog.txt file is not deleted.
D/SPPClientService(12063): PushLog.txt file is not deleted.
D/SPPClientService(12063): ============PushLog. stop!
,I/SA      (11254): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11254): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11254): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11254): [SLFUCHKMGR] constructor called
,E/SPPClientService(12063): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11254): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11254): [OR] == isSIMCardReady false ==
,I/SA      (11254): [SCU] == networkStateCheck == false
I/SA      (11254): [OR] onReceive END
,V/DownloadManager( 5486): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3500): Killing 11198:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11198/oom_score_adj; errno=22
,E/lowmemorykiller( 2829): Error writing /proc/11198/oom_score_adj; errno=22
,E/lowmemorykiller( 2829): Error writing /proc/11198/oom_score_adj; errno=22
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12085): MountEmulatedStorage()
E/Zygote  (12085): v2
I/libpersona(12085): KNOX_SDCARD checking this for 10067
I/libpersona(12085): KNOX_SDCARD not a persona
,I/SELinux (12085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12085): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3500): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12085 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12085): TimaSignature is unavailable
,D/ActivityThread(12085): Added TimaKeyStore provider
,D/ResourcesManager(12085): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12085): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12085): Other Intent
,I/ActivityManager( 3500): Killing 11126:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11126/oom_score_adj; errno=22
,D/accuweather( 5222): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5222): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5222): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5222): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5222): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5222): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5222): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12101): MountEmulatedStorage()
E/Zygote  (12101): v2
I/libpersona(12101): KNOX_SDCARD checking this for 1000
I/libpersona(12101): KNOX_SDCARD not a persona
,I/SELinux (12101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3500): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12101 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12101): TimaSignature is unavailable
,D/ActivityThread(12101): Added TimaKeyStore provider
,D/ResourcesManager(12101): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12101): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12101): premStatus:2
,I/KnoxUsageLogPro(12101): isEulaShown : false
I/KnoxUsageLogPro(12101): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12116): MountEmulatedStorage()
E/Zygote  (12116): v2
I/libpersona(12116): KNOX_SDCARD checking this for 10090
I/libpersona(12116): KNOX_SDCARD not a persona
,I/SELinux (12116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12116): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3500): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12116 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3500): Killing 11310:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8747(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 733us total 11.588ms
,D/TimaKeyStoreProvider(12116): TimaSignature is unavailable
,D/ActivityThread(12116): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 258us total 8.636ms
,D/ResourcesManager(12116): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 266us total 8.345ms
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12132): MountEmulatedStorage()
E/Zygote  (12132): v2
I/libpersona(12132): KNOX_SDCARD checking this for 10127
I/libpersona(12132): KNOX_SDCARD not a persona
,I/SELinux (12132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12132): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12132 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3500): Killing 11329:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12132): TimaSignature is unavailable
,D/ActivityThread(12132): Added TimaKeyStore provider
,D/ResourcesManager(12132): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12132): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12132): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12132): stopCheckCategoryVersion
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12148): MountEmulatedStorage()
E/Zygote  (12148): v2
I/libpersona(12148): KNOX_SDCARD checking this for 10136
I/libpersona(12148): KNOX_SDCARD not a persona
,I/SELinux (12148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12148): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3500): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12148 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3500): Killing 11347:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12148): TimaSignature is unavailable
,D/ActivityThread(12148): Added TimaKeyStore provider
,D/ResourcesManager(12148): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12148): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,I/WebViewFactory(12148): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12148): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12148): Loading: webviewchromium
,I/LibraryLoader(12148): Time to load native libraries: 2 ms (timestamps 802-804)
I/LibraryLoader(12148): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12148): Binding Chromium to main looper Looper (main, tid 1) {26bda454}
,I/LibraryLoader(12148): Expected native library version number "",actual native library version number ""
,I/chromium(12148): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12148): Initializing chromium process, renderers=0
,W/art     (12148): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12148): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(12148): Requires BLUETOOTH permission
I/chromium(12148): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12148): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12148): Starting up...
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12217): MountEmulatedStorage()
I/libpersona(12217): KNOX_SDCARD checking this for 10150
E/Zygote  (12217): v2
I/libpersona(12217): KNOX_SDCARD not a persona
,I/SELinux (12217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12217 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3500): Killing 11362:com.samsung.helphub/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12217): TimaSignature is unavailable
,D/ActivityThread(12217): Added TimaKeyStore provider
,D/ResourcesManager(12217): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12217): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12217): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12217): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12217): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12232): MountEmulatedStorage()
I/libpersona(12232): KNOX_SDCARD checking this for 10178
E/Zygote  (12232): v2
I/libpersona(12232): KNOX_SDCARD not a persona
I/SELinux (12232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3500): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12232 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3500): Killing 11467:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12232): TimaSignature is unavailable
,D/ActivityThread(12232): Added TimaKeyStore provider
,D/ResourcesManager(12232): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12232): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12232): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,E/Zygote  (12255): MountEmulatedStorage()
I/libpersona(12255): KNOX_SDCARD checking this for 10082
E/Zygote  (12255): v2
I/libpersona(12255): KNOX_SDCARD not a persona
I/SELinux (12255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12255): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3500): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12255 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12255): TimaSignature is unavailable
,D/ActivityThread(12255): Added TimaKeyStore provider
,E/Zygote  (12271): MountEmulatedStorage()
E/Zygote  (12271): v2
I/libpersona(12271): KNOX_SDCARD checking this for 1000
I/libpersona(12271): KNOX_SDCARD not a persona
,I/SELinux (12271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12271 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3500): Killing 11484:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/ActivityManager( 3500): Killing 11502:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12271): TimaSignature is unavailable
,D/ActivityThread(12271): Added TimaKeyStore provider
,I/art     ( 3500): Explicit concurrent mark sweep GC freed 72080(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 1.210ms total 81.414ms
,D/ResourcesManager(12255): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12271): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12255): onCreate
,D/BadgeProvider(12255): DatabaseHelper
W/ActivityManager( 3500): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12255): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3500): Killing 11295:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/BadgeProvider(12255): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12255): sendNotify, [notify] : null
D/BadgeProvider(12255): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12255): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12255): update, [UpdateCount] : 1
,D/Launcher.Model( 4005): reloadBadges entered.
,I/iu.Environment( 6864): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6864): num queued entries: 0
,I/iu.UploadsManager( 6864): num updated entries: 0
I/iu.SyncManager( 6864): NEXT; no task
,E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12291): MountEmulatedStorage()
I/libpersona(12291): KNOX_SDCARD checking this for 10013
E/Zygote  (12291): v2
I/libpersona(12291): KNOX_SDCARD not a persona
I/SELinux (12291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12291): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12291 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12291): TimaSignature is unavailable
,D/ActivityThread(12291): Added TimaKeyStore provider
,D/ResourcesManager(12291): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3500): Killing 11539:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4111): Starting #10
,I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8857): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8857): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8857): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8857): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11447): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12057): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12057): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3500): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3500): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3500): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3500): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3500): do suspend true
,D/WifiP2pService( 3500): InactiveState{ what=143375 }
D/WifiP2pService( 3500): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3500): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3500): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3500): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3500): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3500): Not connected state, yet.
E/WifiStateMachine( 3500): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3500): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3500): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3500): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3500): callSECApiInt - ID [210]
,E/WifiStateMachine( 3500): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3500): updateNetworkInfo()
,D/ConnectivityService( 3500): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3500): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3500): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3500): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3500): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3500): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3500): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/Hs20UtilService( 4111): Starting #11
,D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8857): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8857): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3500): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3500): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 3500): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3500): Unexpected mtu value: 0, wlan0
,V/        ( 2846): QcRouteController
,I/SignOutReceiver(11447): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3500): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3500): Now, connected state.
E/WifiStateMachine( 3500): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3500): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3500): evaluateTrafficStatsPolling
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3696): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:null
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3500): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3500): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3500): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3500): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3500): REQUEST_POWER_SAVE_ON
,I/Hs20UtilService( 4111): Starting #12
D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
V/        ( 2846): QcRouteController
I/Hs20UtilService( 4111): Message received 5007
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,D/NearbySettings( 8857): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8857): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8857): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8857): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8857): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8857): MountReceiver.mPrefHandler - 7002
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/SignOutReceiver(11447): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4111): Starting #13
,D/ConnectivityService( 3500): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3500): LTETest block dns file not exists
,D/NearbySettings( 8857): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8857): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 4111): Message received 5007
,D/ConnectivityService( 3500): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3500): updateNetworkInfo()
E/ConnectivityService( 3500): updateNetworkInfo()
D/ConnectivityService( 3500): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3500): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3500): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3500):    accepting network in place of null
,E/CSLegacyTypeTracker( 3500): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3500): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3500): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3500): (HTTPLog)-Static: isSBSettingEnabled false
,D/TelephonyNetworkFactory( 3983): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3500): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3500): MasterInitialState.processMessage what=3
D/SmartBondingService( 3500): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 3500): Not allowed due to - mEnabled false
D/SmartBondingService( 3500): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/ConnectivityService( 3500): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3696): CM callback handler got msg 524290
D/SmartBondingService( 3500): getSBEnabled() enabled =false
V/NetworkStats( 3500): updateIfacesLocked()
V/NetworkStats( 3500): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 6864): CM callback handler got msg 524290
I/WifiStateMachine( 3500): callSECApi what=220
D/WifiStateMachine( 3500): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/NetworkStatsFactory( 3500): UpdateStatsForKnox
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/SmartBondingService( 3500): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
V/NetworkStats( 3500): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NetworkStats( 3500): performPollLocked() took 4ms
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3696): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3696): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3696): updateDataNetType()
D/StatusBar.NetworkController( 3696): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3696): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
D/NtpTrustedTime( 3500): currentTimeMillis() cache hit
I/SignOutReceiver(11447): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3696): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3696): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3696): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
D/StatusBar.NetworkController( 3696): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3696): applyOpen
,I/SurfaceFlinger( 2850): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3500): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3500
,D/mali_winsys( 3696): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3500): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 16:27:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452011252837], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452011252816]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3500): Validated
,D/ConnectivityService( 3500): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3500): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3500): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3500): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3696): CM callback handler got msg 524290
D/ConnectivityService( 3500): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6864): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3696): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3696): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3696): updateDataNetType()
D/StatusBar.NetworkController( 3696): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3696): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3696): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3696): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3696): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3696): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3696): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3500): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3500): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3500): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3500): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3500): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
D/SmartBondingService( 3500): getSBEnabled() enabled =false
,D/SmartBondingService( 3500): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3500): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6290): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6290): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5353): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5353): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11918): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11895): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11895): sales region : global
I/PCWCLIENTTRACE_PushUtil(11895): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11895): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3500): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3500): mCursor = null
,I/FOTA_Client(11991): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11991): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11991): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12007): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 17:27:33 GMT+01:00 2016
,I/KLMS-2.4.521: (12007): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12007): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12007): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12007): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12007): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SO_AGENT(12023): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12007): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12007): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12007): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12007): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12007): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12007): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12007): KLMSIntentService(): onDestroy()
,E/SPPClientService(12063): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11254): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11254): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11254): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11254): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11254): [OR] == isSIMCardReady false ==
,I/SA      (11254): [SCU] == networkStateCheck == true
I/SA      (11254): [DM] getCountryCodeFromCSC : PL
I/SA      (11254): isChinaCountryCode : false
I/SA      (11254): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11254): [OR] == networkStateCheck true ==
,I/SA      (11254): [OR] GetMyCountryZoneTask
I/SA      (11254): [OR] onReceive END
,I/SA      (11254): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5486): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11254): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11254): [SSP] query invoked
,I/SCloudBackupReceiver(12085): Other Intent
,I/SA      (11254): [TPMU] GetMccFromDB : null
I/SA      (11254): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11254): [TPM] isNoProxy(default) : true
,D/accuweather( 5222): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5222): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5222): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5222): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5222): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5222): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5222): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12101): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12101): premStatus:2
,I/KnoxUsageLogPro(12101): isEulaShown : false
I/KnoxUsageLogPro(12101): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12132): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12132): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12132): stopCheckCategoryVersion
,D/QuickConnect(12217): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12217): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12217): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,D/RCPManagerService( 3500): exchangeData() failure , invalid userId
,I/iu.Environment( 6864): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6864): num queued entries: 0
,I/iu.UploadsManager( 6864): num updated entries: 0
I/iu.SyncManager( 6864): NEXT; no task
,D/WaitQueueForNetworkActivate(12291): notifyNetworkActivated
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12291): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3500): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12291): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12291): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12291): exit::IDLE
D/InitializeManagerStateMachine(12291): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12291): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12291): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12291): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12291): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12291): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12291): entry::SUCCESS
D/hcjo    (12291): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12291): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12291): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12291): exit::SUCCESS
D/InitializeManagerStateMachine(12291): entry::IDLE
,I/SA      (11254): [RC New] Execute method=[GET] start
,I/SA      (11254): [RC New] Security=[true]
,I/System.out(11254): Thread-1560(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11254): Thread-1560(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11254): Thread-1560(ApacheHTTPLog):isShipBuild true
I/System.out(11254): Thread-1560(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3500): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11254): [RC New] [v2liruge] api execute + 558
I/SA      (11254): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11254): AsyncTask #1 calls detatch()
,I/SA      (11254): [TPMU] getNetworkMcc : 
,I/SA      (11254): [SCU] saveMccToPreferece Start
I/SA      (11254): [SCU] RegionMCC : 260
I/SA      (11254): [SSP] query invoked
,I/SA      (11254): [TPMU] GetMccFromDB : null
I/SA      (11254): [SCU] getMccFromPreferece mcc = 260
I/SA      (11254): [SCU] saveMccToPreferece End
,I/SA      (11254): [RC New] executeRequest [v2liruge] end. 578
I/SA      (11254): [RC New] Execute end
I/SA      (11254): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11254): [OR] GetMyCountryZoneTask Success
,I/jxcore-log(11780): Test app app.js loaded
I/jxcore-log(11780): 
,I/Choreographer(11780): Skipped 294 frames!  The application may be doing too much work on its main thread.
,I/chromium(11780): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium(11780): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRM:n  ( 3500): SIOP:: AP = 270, PST = 255, CUR = 64
,I/PowerManagerService( 3500): [PWL] Off : 50s ago
,E/WifiStateMachine( 3500): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3500): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3500): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3500): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3500): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3500): getSBEnabled() enabled =false
,D/SmartBondingService( 3500): getSBEnabled() enabled =false
,D/SmartBondingService( 3500): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3500): route cmd failed: 
W/NetworkManagementService( 3500): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3500): '
W/NetworkManagementService( 3500): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3500): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3500): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3500): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3500): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3500): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3500): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3500): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3500): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3500): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3696): CM callback handler got msg 524295
D/ConnectivityService( 3500): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 6864): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3696): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6864): CM callback handler got msg 524295
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:-241, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:99
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  (12057): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4652): callingUid 10014, callindPid: 4652
,D/ResourcesManager(11918): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11918): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(11918): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11918): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11918): Conditions not met for autocaching.
I/MusicLeanback(11918): Stop autocaching.
,D/WearableClient(11918): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11918): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11918): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11918): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11918): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11918): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11918): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@17e3f3b2 that was originally bound here
E/ActivityThread(11918): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@17e3f3b2 that was originally bound here
E/ActivityThread(11918): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11918): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11918): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11918): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11918): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11918): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11918): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11918): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11918): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11918): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11918): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11918): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11918): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11918): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11918): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11918): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11918): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11918): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11918): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11918): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11918): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11918): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3500): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3500): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3500): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3500) eventTime = 145501
,D/PowerManagerService( 3500): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3500 (0x0)
D/PowerManagerService( 3500): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3500, ws=WorkSource{10060}) (elapsedTime=3498)
,I/GAV4    (12148): Thread[GAThread,5,main]: No campaign data found.
,D/PackageManager( 3500): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11895): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11895): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11895): ================================================
,I/CSTORAGE(11895):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11895): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11895): [GetString-S]
,E/art     (11895): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11895): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11895): [GetString-E]
I/PCWCLIENTTRACE_PushUtil(11895): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11895): sales region : global
I/PCWCLIENTTRACE_PushUtil(11895): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11895): [ensureRegistration] - No Samsung account
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (12057): wlan0: sending IPv6 Router Solicitation,
,W/ProcessCpuTracker( 3500): Skipping unknown process pid 12474
,I/dhcpcd  (12057): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12057): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12291): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12291): exit::IDLE
D/PreloadUpdateManagerStateMachine(12291): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12291): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12291): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12291): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12291): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12291): entry::IDLE
,D/SSRM:n  ( 3500): SIOP:: AP = 250, PST = 253, CUR = -241
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:-39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 5
,D/SSRM:n  ( 3500): SIOP:: AP = 240, PST = 250, CUR = -39
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3500): [PWL] Off : 75s ago
,V/AlarmManager( 3500): waitForAlarm result :8
,D/SSRM:n  ( 3500): SIOP:: AP = 230, PST = 249, CUR = 33
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:68
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 4652): Explicit concurrent mark sweep GC freed 78318(4MB) AllocSpace objects, 23(823KB) LOS objects, 34% free, 30MB/46MB, paused 1.884ms total 66.146ms
,I/ClearcutLoggerApiImpl( 4652): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3500): SIOP:: AP = 230, PST = 248, CUR = 56
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3500): !@Sync 6
,D/SSRM:n  ( 3500): SIOP:: AP = 230, PST = 247, CUR = 63
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3500): [PWL] Off : 105s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 230, PST = 241, CUR = 61
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 240, CUR = 58
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3500): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3696): handleTimeUpdate
,D/KeyguardEffectViewController( 3696): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3696): *** don't update sliding image ***
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 6864): Aggregate from 1452009432887 (log), 1452009432887 (data)
,E/Watchdog( 3500): !@Sync 7
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 238, CUR = 55
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3500): Skipping unknown process pid 12566
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3500): waitForAlarm result :8
,I/PowerManagerService( 3500): [PWL] Off : 140s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 237, CUR = 52
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 232, CUR = 50
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3500): !@Sync 8
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 231, CUR = 48,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 229, CUR = 46
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3500): [PWL] Off : 180s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 227, CUR = 45
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3500): !@Sync 9
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 225, CUR = 45
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 224, CUR = 43
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 223, CUR = 40
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3500): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3500): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3500): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3500): initializing...
,I/TLC_TIMA_PKM_initialize( 3500): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3500): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3500): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3500): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3500): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3500): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3500): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3500): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3500): device_id = 0x0
I/TZ: mc_tlc_communication( 3500): tlc_open() was called
,I/TZ: mc_tlc_communication( 3500): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3500): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3500): Opening the session
,I/TZ: mc_tlc_communication( 3500): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3500): Trustlet response is completed
,E/Watchdog( 3500): !@Sync 10
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 222, CUR = 40
,I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3500): [PWL] Off : 225s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 221, CUR = 40
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 221, CUR = 39
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 11
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 220, CUR = 39
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 220, PST = 220, CUR = 37
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 219, CUR = 38
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3500): [PWL] Off : 275s ago
,E/Watchdog( 3500): !@Sync 12
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 219, CUR = 37
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 218, CUR = 37
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 218, CUR = 36
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 13
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 217, CUR = 34
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3500): waitForAlarm result :8
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 216, CUR = 34,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 330s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 216, CUR = 32
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3500): !@Sync 14
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 216, CUR = 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 215, CUR = 32
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 215, CUR = 34
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 15
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 214, CUR = 32,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 214, CUR = 32
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 390s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 213, CUR = 30
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3500): !@Sync 16
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 213, CUR = 31
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 213, CUR = 32
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 212, CUR = 31
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 17
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 212, CUR = 30
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 212, CUR = 30
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 211, CUR = 29
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 455s ago
,E/Watchdog( 3500): !@Sync 18
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 211, CUR = 29
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 211, CUR = 28
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3500): stay LED for fully charged
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 28
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 19
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 28
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 28,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 27
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3500): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 3500): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 3500): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog( 3500): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 26
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 525s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 25,
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 26
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 21
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 26
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 26
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 26
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 22
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 25
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 24
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 600s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 24
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 23
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 25
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 24
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 25
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 24
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 23
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 23
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 226, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 24
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 25
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 22
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 680s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 21
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 22,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3500): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3500): stay LED for fully charged
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 26
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 21
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 22
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 22
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 27
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 22
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 20
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 210, PST = 210, CUR = 21
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 28
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 209, CUR = 19
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3500): [PWL] Off : 765s ago
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 225, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 209, CUR = 21
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 209, CUR = 20
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 29
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 208, CUR = 18,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 208, CUR = 20
,V/AlarmManager( 3500): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3696): handleTimeUpdate
,D/KeyguardEffectViewController( 3696): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3696): *** don't update sliding image ***
,D/LightsService( 3500): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3500): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3500): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3500): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3500): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3500): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3500): unregisterListener ::   
D/LightsService( 3500): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 208, CUR = 17
,D/TimaService( 3500): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3500): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3500): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 207, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 207, CUR = 20
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 207, CUR = 20
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged,
D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 31
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 206, CUR = 20
,I/PowerManagerService( 3500): [PWL] Off : 855s ago
,V/AlarmManager( 3500): waitForAlarm result :8
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 206, CUR = 20
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 206, CUR = 20,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged,
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 32
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 205, CUR = 19
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 224, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 205, CUR = 19
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 205, CUR = 18
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 33
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 204, CUR = 16
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 204, CUR = 17
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 204, CUR = 17
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 34
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 203, CUR = 16
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 950s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 203, CUR = 17,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3500): stay LED for fully charged
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 203, CUR = 17
,E/Watchdog( 3500): !@Sync 35
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 202, CUR = 17
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 202, CUR = 16
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 202, CUR = 18
,E/Watchdog( 3500): !@Sync 36
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 201, CUR = 16
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 201, CUR = 15
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 201, CUR = 16
,E/Watchdog( 3500): !@Sync 37
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged,
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 17
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 223, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3500): stay LED for fully charged
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 16
,E/Watchdog( 3500): !@Sync 38
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 17
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 16
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15
,E/Watchdog( 3500): !@Sync 39
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 16
,D/TimaService( 3500): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3500): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3500): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3500): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3500): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3500): Updating Usage Statistics in DB @ 1452012321993
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	,at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
,W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3500): ::getAppControlDB: Exception to create DB
W/System.err( 3500): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3500): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3500): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3500): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3500): Done Updating Usage Statistics in DB @ 1452012322117
,E/Watchdog( 3500): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15,
,I/art     ( 3500): Background sticky concurrent mark sweep GC freed 108250(10MB) AllocSpace objects, 332(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.611ms total 112.919ms
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 14
,E/Watchdog( 3500): !@Sync 41
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 14
,I/PowerManagerService( 3500): [PWL] Off : 1155s ago
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 17
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15
,E/Watchdog( 3500): !@Sync 42
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 14
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 13
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 14
,E/Watchdog( 3500): !@Sync 43
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 14,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 13,
,E/Watchdog( 3500): !@Sync 44
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 13
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 222, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,I/PowerManagerService( 3500): [PWL] Off : 1265s ago
,E/Watchdog( 3500): !@Sync 45
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 13
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 15,
,E/Watchdog( 3500): !@Sync 46
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 13
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,E/Watchdog( 3500): !@Sync 47
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11,
,E/Watchdog( 3500): !@Sync 48
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,I/PowerManagerService( 3500): [PWL] Off : 1380s ago
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3500): stay LED for fully charged
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,E/Watchdog( 3500): !@Sync 49
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 3500): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3500): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3500): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3500): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 51
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 52
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 53
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 54
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3500): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 55
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 12
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 221, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged,
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 56
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 11
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3500): [PWL] Off : 1625s ago
,E/Watchdog( 3500): !@Sync 57
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10,
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 58
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 59
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3500): waitForAlarm result :4
,W/ProcessCpuTracker( 3500): Skipping unknown process pid 13541
,D/NetworkStatsFactory( 3500): UpdateStatsForKnox
,V/AlarmManager( 3500): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3696): handleTimeUpdate
,D/KeyguardEffectViewController( 3696): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3696): *** don't update sliding image ***
,D/LightsService( 3500): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3500): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3500): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,V/AlarmManager( 3500): OOI=Alarm{66c3a4e type 0 when 1452014710739 com.google.android.gms}
,V/AlarmManager( 3500): waitForAlarm result :8
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3500): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3500): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3500): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3500): unregisterListener ::   
D/LightsService( 3500): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3500): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3500): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3500): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3500): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3500): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3500): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3500): stay LED for fully charged
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 61
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,I/PowerManagerService( 3500): [PWL] Off : 1755s ago
,V/AlarmManager( 3500): waitForAlarm result :8
,I/ProcessStatsService( 3500): Prepared write state in 16ms
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3696): handleTimeUpdate
,D/KeyguardEffectViewController( 3696): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3696): *** don't update sliding image ***
,I/ProcessStatsService( 3500): Pruning old procstats: /data/system/procstats/state-2016-01-04-20-53-25.bin
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3696): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,I/art     ( 3500): Background partial concurrent mark sweep GC freed 52725(5MB) AllocSpace objects, 200(3MB) LOS objects, 24% free, 49MB/65MB, paused 3.201ms total 189.982ms
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 62
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 8
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/BatteryService( 3500): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 7
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 63
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,V/AlarmManager( 3500): waitForAlarm result :8
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 10
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3500): stay LED for fully charged
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3500): !@Sync 64
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 9
,D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3500): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3500): Plugged
,I/MotionRecognitionService( 3500): setPowerConnected  = true
,D/BatteryService( 3500): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5677): Disconnected process message: 10
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3500): SIOP:: AP = 200, PST = 200, CUR = 7
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService( 3500): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3500): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 220, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3500): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3500): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3500): Plugged
I/MotionRecognitionService( 3500): setPowerConnected  = true
D/BatteryService( 3500): stay LED for fully charged
D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5677): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5677): Disconnected process message: 10
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(13684): 
D/AndroidRuntime(13684): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13684): CheckJNI is OFF
D/AndroidRuntime(13684): readGMSProperty: start
D/AndroidRuntime(13684): readGMSProperty: already setted!!
D/AndroidRuntime(13684): readGMSProperty: end
D/AndroidRuntime(13684): addProductProperty: start
E/AffinityControl(13684): AffinityControl: registerfunction enter
D/AndroidRuntime(13684): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 3500): START PACKAGE DELETE: observer{611363077}
D/PackageManager( 3500): pkg{<packageName>}
D/PackageManager( 3500): user{0}
D/PackageManager( 3500): caller{2000}
D/PackageManager( 3500): flags{3}
D/PersonaManagerService( 3500): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3500): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3500): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3500): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3500): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3500): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3500): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3500): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3500): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3500): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3500): !@killApplicatoin: 10535, uninstall pkg
I/ActivityManager( 3500): Force stopping com.test.thalitest appid=10535 user=-1: uninstall pkg
I/ActivityManager( 3500): Killing 11780:com.test.thalitest/u0a535 (adj 0): stop com.test.thalitest
I/ActivityManager( 3500): Killing 11254:com.osp.app.signin/u0a45 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 12038:com.policydm/1000 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 12023:com.sec.android.soagent/u0a38 (adj 13): empty for 1810s
E/lowmemorykiller( 2829): Error writing /proc/12038/oom_score_adj; errno=22
I/ActivityManager( 3500): Killing 12007:com.samsung.klmsagent/u0a21 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 11991:com.sec.android.fotaclient/u0a12 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 11974:com.sec.android.diagmonagent/1000 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 11952:com.sec.android.cloudagent/u0a2 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 11895:com.sec.pcw.device/1000 (adj 13): empty for 1810s
I/ActivityManager( 3500): Killing 11447:com.samsung.android.snote/u0a160 (adj 15): empty for 1811s
I/ActivityManager( 3500): Killing 8857:com.android.settings/1000 (adj 15): empty for 1811s
I/ActivityManager( 3500): Killing 12255:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1811s
I/ActivityManager( 3500): Killing 11679:com.android.vending/u0a31 (adj 15): empty for 1839s
I/ActivityManager( 3500): Killing 10858:com.android.defcontainer/u0a5 (adj 15): empty for 1844s
I/ActivityManager( 3500): Killing 11522:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): empty for 1852s
I/ActivityManager( 3500): Killing 11555:com.android.calendar/u0a164 (adj 15): empty for 1852s
I/ActivityManager( 3500):   Force finishing activity ActivityRecord{a941212 u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3500): mDVFSHelper.acquire()
W/PackageSettings( 3500): Skipping PackageSetting{35c56f3d com.example.hello/10529} due to missing metadata
D/WifiService( 3500): Client connection lost with reason: 4
D/WifiService( 3500): Client connection lost with reason: 4
I/WindowState( 3500): WIN DEATH: Window{17cfd628 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 2850): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 3500): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3500): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3500): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3500): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 3500): Force stopping com.test.thalitest appid=10535 user=0: pkg removed
I/ActivityManager( 3500):   Force finishing activity ActivityRecord{a941212 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3500): Duplicate finish request for ActivityRecord{a941212 u0 com.test.thalitest/.MainActivity t26 f}
W/libprocessgroup( 3500): failed to open /acct/uid_1000/pid_12038/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10021/pid_12007/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10164/pid_11555/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10005/pid_10858/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10160/pid_11447/cgroup.procs: No such file or directory
I/art     ( 9041): Explicit concurrent mark sweep GC freed 31670(1744KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.157ms total 38.808ms
W/libprocessgroup( 3500): failed to open /acct/uid_10031/pid_11679/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10022/pid_11522/cgroup.procs: No such file or directory
I/art     ( 4062): Explicit concurrent mark sweep GC freed 33159(2033KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 939us total 43.241ms
W/libprocessgroup( 3500): failed to open /acct/uid_10082/pid_12255/cgroup.procs: No such file or directory
I/art     ( 6864): Explicit concurrent mark sweep GC freed 29993(1732KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 1.989ms total 66.360ms
W/libprocessgroup( 3500): failed to open /acct/uid_1000/pid_11974/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10045/pid_11254/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10002/pid_11952/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10038/pid_12023/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_1000/pid_8857/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_1000/pid_11895/cgroup.procs: No such file or directory
W/libprocessgroup( 3500): failed to open /acct/uid_10012/pid_11991/cgroup.procs: No such file or directory
I/DBG_DM  ( 6290): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/InputReader( 3500): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6290): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
E/SamsungIME( 4519): mOCRHelper is null
W/GeofencerStateMachine( 4652): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
W/BroadcastQueue( 3500): Skipping deliver [background] BroadcastRecord{ae86b8b u0 android.intent.action.PACKAGE_REMOVED} to ReceiverList{a8bf850 11522 com.sec.android.widgetapp.locationwidget/10022/u0 remote:34720e13}: filter unregistered
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
I/art     ( 3500): Explicit concurrent mark sweep GC freed 19875(1898KB) AllocSpace objects, 28(448KB) LOS objects, 24% free, 48MB/64MB, paused 2.014ms total 144.582ms
D/ResourcesManager( 3500): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3500): WaitForGcToComplete blocked for 58.366ms for cause Explicit
I/DBG_DM  ( 6290): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
E/Zygote  (13703): MountEmulatedStorage()
E/Zygote  (13703): v2
I/libpersona(13703): KNOX_SDCARD checking this for 10063
I/libpersona(13703): KNOX_SDCARD not a persona
I/SELinux (13703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SELinux (13703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13703 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/ResourceType( 5353): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5353): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
D/SecContentProvider2( 3500): uri = 14 selection = getSealedState
D/SecContentProvider2( 3500): mCursor = null
D/TimaKeyStoreProvider(13703): TimaSignature is unavailable
D/ApplicationPolicy( 3500): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3500): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ActivityThread(13703): Added TimaKeyStore provider
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ResourcesManager(13703): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
I/DBG_DM  ( 6290): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/DBG_DM  ( 6290): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
D/RegisteredServicesCache( 3970): empty dynamic service
I/DBG_DM  ( 6290): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/DBG_DM  ( 6290): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6290): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ActivityManager( 3500): post active user change for 0
D/KnoxTimeoutHandler( 3500): postActiveUserChange for user 0
I/DBG_DM  ( 6290): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/SecContentProvider2( 3500): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3500): mCursor = null
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Books/Books.apk
D/VRSetupWizardStub/PackageIntentReceiver(13703): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13703): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13703): packagename:com.test.thalitest
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SurfaceFlinger( 2850): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/StatusBarManagerService( 3500): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/StatusBarManagerService( 3500): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/PointerIcon( 3500): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3500): setMouseCustomIcon IconType is same.101
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/PointerIcon( 3500): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3500): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6290): updateVisibility : ActivityRecord{29ef25ed token=android.os.BinderProxy@7c81716 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 3500): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/Zygote  (13720): MountEmulatedStorage()
E/Zygote  (13720): v2
I/libpersona(13720): KNOX_SDCARD checking this for 10021
I/libpersona(13720): KNOX_SDCARD not a persona
I/SELinux (13720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/InputMethodManagerService( 3500): Got RemoteException sending setActive(false) notification to pid 11780 uid 10535
W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/SELinux (13720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3500): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=13720 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/SELinux (13720): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Killing 12085:com.samsung.android.scloud.backup/u0a67 (adj 15): empty for 1811s
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/art     ( 3500): Explicit concurrent mark sweep GC freed 6907(366KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 9.413ms total 204.086ms
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/TimaKeyStoreProvider(13720): TimaSignature is unavailable
D/ResourcesManager( 3500): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ActivityThread(13720): Added TimaKeyStore provider
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(13720): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/PackageManager( 3500): delete codoeFile: 
D/RCPManagerService( 3500): PackageReceiver onReceive()
I/HarmonyEASService( 3500): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/KnoxMUMContainerPolicy( 3500): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/AASAUninstall( 3500):  com.test.thalitest not target!
D/BackupManagerService( 3500): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3500): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3500): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/PackageManager( 3500): result of delete: 1{611363077}
V/EnterpriseBillingPolicy( 3500): uID is 10535
V/EnterpriseBillingPolicy( 3500): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3500): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3500): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3500): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3500): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3500): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3500): getBillingProfileForVpnEngine - end - null
D/EnterpriseDeviceManagerService( 3500): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3500): Admin package name: com.google.android.gms
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/Timeline( 6290): Timeline: Activity_idle id: android.os.BinderProxy@7c81716 time:1953692
W/libprocessgroup( 3500): failed to open /acct/uid_10067/pid_12085/cgroup.procs: No such file or directory
D/AndroidRuntime(13684): Shutting down VM
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/KnoxTimeoutHandler( 3500): handleActiveUserChange for user 0
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.521: (13720): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 17:57:44 GMT+01:00 2016
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.521: (13720): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3500): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/splitIntent( 3500): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/KLMS-2.4.521: (13720): KLMSIntentService(): onCreate()
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/KLMS-2.4.521: (13720): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (13720): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
I/KLMS-2.4.521: (13720): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (13720): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (13720): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.4.521: (13720): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManager(12101):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3500):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3500): queryAllProviders():  providerCallBack is not register for 0
D/StatusBar( 3696): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 3696): isKioskContainerExistOnDevice
D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
I/StatusBar( 3696): Icon Only
D/PanelView( 3696): There is/are notification(s) 
D/PanelView( 3696): There is/are notification(s) 
D/PersonaManager( 3696): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3696): Icon Only
I/StatusBar( 3696): Icon Only
D/PanelView( 3696): There is/are notification(s) 
E/Zygote  (13738): MountEmulatedStorage()
E/Zygote  (13738): v2
I/libpersona(13738): KNOX_SDCARD checking this for 10160
I/libpersona(13738): KNOX_SDCARD not a persona
I/SELinux (13738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3500): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13738 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/Zygote  (13750): MountEmulatedStorage()
E/Zygote  (13750): v2
I/libpersona(13750): KNOX_SDCARD checking this for 10106
I/libpersona(13750): KNOX_SDCARD not a persona
I/SELinux (13750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3500): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13750 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (13750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TaskPersister( 3500): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3500): removeObsoleteFile: deleting file=24_task.xml
W/ActivityManager( 3500): mDVFSHelper.release()
I/Timeline( 3500): Timeline: Activity_windows_visible id: ActivityRecord{889213 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1953779
W/ResourceType( 3500): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13738): TimaSignature is unavailable
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ActivityThread(13738): Added TimaKeyStore provider
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3500): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8746(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 908us total 23.253ms
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 3500): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3500): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3500): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3500): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/PanelView( 3696): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/TimaKeyStoreProvider(13750): TimaSignature is unavailable
D/ActivityThread(13750): Added TimaKeyStore provider
D/ResourcesManager( 3500): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 825us total 18.853ms
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3500): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources( 3500): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.4.521: (13720): KLMSIntentService(): listeningToPackageRemoved().END
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 839us total 18.432ms
E/Zygote  (13768): MountEmulatedStorage()
E/Zygote  (13768): v2
I/libpersona(13768): KNOX_SDCARD checking this for 10050
I/libpersona(13768): KNOX_SDCARD not a persona
I/SELinux (13768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3500): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13768 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (13768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbSettingsManager( 3500): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3500): onPackageRemoved : com.test.thalitest
I/KLMS-2.4.521: (13720): KLMSIntentService(): onDestroy()

```
