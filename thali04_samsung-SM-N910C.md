#### Test 549702613245198_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3523): !@Sync 4
,--------- beginning of main
D/AndroidRuntime(11704): 
D/AndroidRuntime(11704): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11704): CheckJNI is OFF
D/AndroidRuntime(11704): readGMSProperty: start
D/AndroidRuntime(11704): readGMSProperty: already setted!!
D/AndroidRuntime(11704): readGMSProperty: end
D/AndroidRuntime(11704): addProductProperty: start
E/AffinityControl(11704): AffinityControl: registerfunction enter
D/AndroidRuntime(11704): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3523): inState():  stateMachine is null !!
I/PersonaManagerService( 3523): PersonaId don't exist
I/ActivityManager( 3523): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3523): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3523): mDVFSHelper.acquire()
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/Zygote  (11722): MountEmulatedStorage()
I/libpersona(11722): KNOX_SDCARD checking this for 10552
E/Zygote  (11722): v2
I/libpersona(11722): KNOX_SDCARD not a persona
I/SELinux (11722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11722 uid=10552 gids={50552, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11722): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11704): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11722): TimaSignature is unavailable
D/ActivityThread(11722): Added TimaKeyStore provider
D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 260, CUR = 39
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2850): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11722): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6263): updateVisibility : ActivityRecord{3daddfca token=android.os.BinderProxy@24e59e9f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5644): Disconnected process message: 10
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/WebViewFactory(11722): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11722): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11722): Loading: webviewchromium
,I/LibraryLoader(11722): Time to load native libraries: 6 ms (timestamps 4316-4322)
I/LibraryLoader(11722): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11722): Binding Chromium to main looper Looper (main, tid 1) {3aa84d85}
,I/LibraryLoader(11722): Expected native library version number "",actual native library version number ""
,I/chromium(11722): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11722): Initializing chromium process, renderers=0
,W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11722): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11722): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11722): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11722): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11722): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11722): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11722): CordovaWebView is running on device made by: samsung
,W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11722): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11722): performCreate Call secproduct feature valuefalse
D/Activity(11722): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11722): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2850): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11722): Initialized EGL, version 1.4
,I/OpenGLRenderer(11722): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279672048 
,D/OpenGLRenderer(11722): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11722): Enabling debug mode 0
,D/mali_winsys(11722): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11722): updateVisibility : ActivityRecord{3c70a1f5 token=android.os.BinderProxy@23ba69d0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{474414e u0 com.test.thalitest/.MainActivity t26} time:134738
,W/IInputConnectionWrapper(11722): showStatusIcon on inactive InputConnection
,I/Timeline(11722): Timeline: Activity_idle id: android.os.BinderProxy@23ba69d0 time:134748
,D/JsMessageQueue(11722): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11722): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11722): 
,D/jxcore_app_log(11722): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1361352960
D/JX-Cordova(11722): jxcore cordova android initializing
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11722): Initializing JXcore engine
W/jxcore-log(11722): JXcore engine is ready
,W/jxcore-log(11722): Starting JXcore engine
,E/auditd  ( 4600): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11722): Platform android
W/jxcore-log(11722): 
W/jxcore-log(11722): Process ARCH arm
W/jxcore-log(11722): 
,I/jxcore-log(11722): JXcore Cordova bridge is ready!
I/jxcore-log(11722): 
W/jxcore-log(11722): JXcore engine is started
,I/jxcore-log(11722): Toggling radios to true
I/jxcore-log(11722): 
,D/BluetoothAdapter(11722): enable()
,D/BluetoothAdapter(11722): enable(): BT is already enabled..!
,D/WifiService( 3523): New client listening to asynchronous messages
,I/WifiManager(11722): packageName : com.test.thalitest
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: true pid=11722, uid=10552
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=11722, uid=10552 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): Failed getting userId using ActivityManagerNative
W/WifiService( 3523): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11722, uid=10552 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3523): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3523): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3523): name = wifi_on
I/WifiService( 3523): disconnect: pid=11722, uid=10552
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): Disconnected - do not scan
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11722): Radios toggled
I/jxcore-log(11722): 
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
,I/Hs20UtilService( 4083): Starting #8
,I/Hs20UtilService( 4083): Message received 5007
,D/NearbySettings( 8781): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8781): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8781): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8781): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8781): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine( 3523): Start Disconnecting Watchdog 1
,E/WifiStateMachine( 3523): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8781): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8781): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11376): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524292
D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 3981): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - currTime: 1452283763723
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 4761): CM callback handler got msg 524292
,I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3833): First Scan Start
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): updateIfacesLocked()
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,V/NetworkStats( 3523): performPollLocked() took 8ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
I/Hs20UtilService( 4083): Starting #9
,I/Hs20UtilService( 4083): Message received 5007
,D/NearbySettings( 8781): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8781): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
I/NearbySettings( 8781): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8781): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8781): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11376): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3523): updateDataUsageMap
,I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3523): No Active Data Connection
,I/DBG_DM  ( 6263): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6263): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11823): MountEmulatedStorage()
E/Zygote  (11823): v2
I/libpersona(11823): KNOX_SDCARD checking this for 10110
I/libpersona(11823): KNOX_SDCARD not a persona
,I/SELinux (11823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11823 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11823): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11823): TimaSignature is unavailable
,D/ActivityThread(11823): Added TimaKeyStore provider
,D/ResourcesManager(11823): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11823): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11823): not using cross-dex optimization: ART in use
,I/art     (11823): Thread[1,tid=11823,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11823): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11823): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11823): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11823): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11823): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11823): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11823): loading pre-built fallback odex files
V/MultiDexClassLoader(11823): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11823): released odex store lock
D/DexLibLoader(11823): DexLibLoader.loadAll took 15 ms
,W/ca      (11823): Verify
,W/LightSharedPreferencesImpl(11823): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11823): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11823): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11823): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11823): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11823): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11823): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11823): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11823): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11823): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11823): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11823): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11823): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11823): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11823): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11823): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11823): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11823): 	... 10 more
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11848): MountEmulatedStorage()
E/Zygote  (11848): v2
I/libpersona(11848): KNOX_SDCARD checking this for 1000
I/libpersona(11848): KNOX_SDCARD not a persona
,I/SELinux (11848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11848 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 10891:com.android.mms/u0a52 (adj 15): bgCount ##31
W/appmanager(:<default>):b(11823): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/lowmemorykiller( 2829): Error writing /proc/10891/oom_score_adj; errno=22
,W/appmanager(:<default>):b(11823): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11848): TimaSignature is unavailable
,D/ActivityThread(11848): Added TimaKeyStore provider
,D/ResourcesManager(11848): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/CountryDetector( 3523): No listener is left
,W/appmanager(:<default>):QuickExperimentControllerImpl(11823): Exposure of experiment com.facebook.common.network.l@7728d23 occurred when no user was logged in
,I/PCWCLIENTTRACE_LOG(11848): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11848): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11848): new DMDBOpenHelper instance
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1c97e79d u0 ReceiverList{c782674 11823 com.facebook.appmanager/10110/u0 remote:14ff4e47}}
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1c97e79d u0 ReceiverList{c782674 11823 com.facebook.appmanager/10110/u0 remote:14ff4e47}}
,I/PCWCLIENTTRACE_PushUtil(11848): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11848): sales region : global
I/PCWCLIENTTRACE_PushUtil(11848): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11848): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11848): noConnectivity : true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11876): MountEmulatedStorage()
I/libpersona(11876): KNOX_SDCARD checking this for 10135
E/Zygote  (11876): v2
I/libpersona(11876): KNOX_SDCARD not a persona
,I/SELinux (11876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11876): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11876 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10977:com.policydm/1000 (adj 15): bgCount ##31
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2a7489d1 u0 ReceiverList{1cfde0f8 11823 com.facebook.appmanager/10110/u0 remote:1d5d105b}}
,D/TimaKeyStoreProvider(11876): TimaSignature is unavailable
,D/ActivityThread(11876): Added TimaKeyStore provider
,D/ResourcesManager(11876): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11876): Database version: 104
,D/ResourcesManager(11876): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11876): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11876): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11876): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@569bb89: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11876): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11876): GMSCore installation verified
,I/ConfigStore(11876): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11823): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11823): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11876): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11823): Exposure of experiment com.facebook.imagepipeline.a.g@3fdd4ba0 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11823): Exposure of experiment com.facebook.imagepipeline.a.d@324a9c15 occurred when no user was logged in
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11876): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11876): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/art     (11823): Explicit concurrent mark sweep GC freed 47154(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 565us total 21.994ms
,W/appmanager(:<default>):m(11823): No feature status reporters found; is this dead code?
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3523): getStreamVolume 3 index 0
,I/MediaRouter(11876): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11908): MountEmulatedStorage()
I/libpersona(11908): KNOX_SDCARD checking this for 10002
E/Zygote  (11908): v2
I/libpersona(11908): KNOX_SDCARD not a persona
I/SELinux (11908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11908 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3833): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 3833): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3833): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3833): wlan0: State: SCANNING -> ASSOCIATING
E/WifiStateMachine( 3523): [1,452,283,764,807 ms] noteScanEnd no scan source
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1861bd24 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info
,I/NetworkMonitor(11876): type=WIFI subType= reason=null isConnected=false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/TimaKeyStoreProvider(11908): TimaSignature is unavailable
,D/ActivityThread(11908): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 10993:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/10993/oom_score_adj; errno=22
,D/ResourcesManager(11908): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3523): Killing 11010:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11927): MountEmulatedStorage()
I/libpersona(11927): KNOX_SDCARD checking this for 1000
E/Zygote  (11927): v2
I/libpersona(11927): KNOX_SDCARD not a persona
,I/SELinux (11927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11927 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3833): Associated with C0.AA.48
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 566us total 12.741ms
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 264us total 8.253ms
,D/TimaKeyStoreProvider(11927): TimaSignature is unavailable
,D/ActivityThread(11927): Added TimaKeyStore provider
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3833): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3833): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3833): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3833): Blacklist: Clear (temp) 
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 277us total 9.797ms
E/WifiStateMachine( 3523): Network connection established
D/WifiNative-HAL( 3523): callSECApiVoid - ID [50]
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3523): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3523): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3523): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3523): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ResourcesManager(11927): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3523): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2846): Setting iface cfg
,E/WifiStateMachine( 3523): Start Dhcp Watchdog 2
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(11927): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11927): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11927): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11927): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11927): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11944): MountEmulatedStorage()
E/Zygote  (11944): v2
I/libpersona(11944): KNOX_SDCARD checking this for 10012
I/libpersona(11944): KNOX_SDCARD not a persona
,I/SELinux (11944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11944): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11944 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11944): TimaSignature is unavailable
,D/ActivityThread(11944): Added TimaKeyStore provider
,D/ResourcesManager(11944): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3523): Killing 11030:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(11944): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11944): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11944): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11960): MountEmulatedStorage()
I/libpersona(11960): KNOX_SDCARD checking this for 10021
E/Zygote  (11960): v2
I/libpersona(11960): KNOX_SDCARD not a persona
,I/SELinux (11960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11960): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11960 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11047:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11047/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11960): TimaSignature is unavailable
,D/ActivityThread(11960): Added TimaKeyStore provider
,D/ResourcesManager(11960): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11960): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 21:09:25 GMT+01:00 2016
,I/KLMS-2.4.521: (11960): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11960): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11960): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11960): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11960): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11960): StateImplV2(): networkChangeListener().END
,E/Zygote  (11976): MountEmulatedStorage()
I/libpersona(11976): KNOX_SDCARD checking this for 10038
E/Zygote  (11976): v2
I/libpersona(11976): KNOX_SDCARD not a persona
I/SELinux (11976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11976 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3523): Killing 10858:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11976): TimaSignature is unavailable
,D/ActivityThread(11976): Added TimaKeyStore provider
,D/ResourcesManager(11976): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11976): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  (11991): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/Zygote  (11992): MountEmulatedStorage()
I/libpersona(11992): KNOX_SDCARD checking this for 1000
E/Zygote  (11992): v2
I/libpersona(11992): KNOX_SDCARD not a persona
I/SELinux (11992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/dhcpcd  (11991): version 5.5.6 starting
,I/SELinux (11992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/dhcpcd  (11991): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/SELinux (11992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11103:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11992): TimaSignature is unavailable
,D/ActivityThread(11992): Added TimaKeyStore provider
,D/ResourcesManager(11992): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/dhcpcd  (11991): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11991): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11991): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (11991): bssid match
I/dhcpcd  (11991): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12018): MountEmulatedStorage()
E/Zygote  (12018): v2
I/libpersona(12018): KNOX_SDCARD checking this for 10039
I/libpersona(12018): KNOX_SDCARD not a persona
,I/SELinux (12018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12018): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12018 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11125:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12018): TimaSignature is unavailable
,D/ActivityThread(12018): Added TimaKeyStore provider
,D/ResourcesManager(12018): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12018): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12018): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12018): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12018): PushLog.txt file is not deleted.
,D/SPPClientService(12018): PushLog.txt file is not deleted.
D/SPPClientService(12018): ============PushLog. stop!
,I/SA      (11183): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11183): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11183): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11183): [SLFUCHKMGR] constructor called
,E/SPPClientService(12018): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11183): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11183): [OR] == isSIMCardReady false ==
,I/SA      (11183): [SCU] == networkStateCheck == false
I/SA      (11183): [OR] onReceive END
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12038): MountEmulatedStorage()
I/libpersona(12038): KNOX_SDCARD checking this for 10067
E/Zygote  (12038): v2
I/libpersona(12038): KNOX_SDCARD not a persona
I/SELinux (12038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12038): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12038 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11067:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12038): TimaSignature is unavailable
,D/ActivityThread(12038): Added TimaKeyStore provider
,D/ResourcesManager(12038): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12038): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12038): Other Intent
,I/ActivityManager( 3523): Killing 11148:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5422): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5422): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5422): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5422): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5422): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5422): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5422): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12054): MountEmulatedStorage()
I/libpersona(12054): KNOX_SDCARD checking this for 1000
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,I/dhcpcd  (11991): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,D/ResourcesManager(12054): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12054): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12054): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12054): premStatus:2
,I/KnoxUsageLogPro(12054): isEulaShown : false
I/KnoxUsageLogPro(12054): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12069): MountEmulatedStorage()
E/Zygote  (12069): v2
I/libpersona(12069): KNOX_SDCARD checking this for 10090
I/libpersona(12069): KNOX_SDCARD not a persona
,I/SELinux (12069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12069): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/dhcpcd  (11991): wlan0: leased 192.168.1.124 for 86400 seconds
,I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12069 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11086:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/TimaKeyStoreProvider(12069): TimaSignature is unavailable
,D/ActivityThread(12069): Added TimaKeyStore provider
,D/ResourcesManager(12069): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12100): MountEmulatedStorage()
I/libpersona(12100): KNOX_SDCARD checking this for 10127
E/Zygote  (12100): v2
I/libpersona(12100): KNOX_SDCARD not a persona
,I/SELinux (12100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12100): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12100 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11240:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12100): TimaSignature is unavailable
,D/ActivityThread(12100): Added TimaKeyStore provider
,D/ResourcesManager(12100): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12100): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12100): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12100): stopCheckCategoryVersion
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12122): MountEmulatedStorage()
E/Zygote  (12122): v2
I/libpersona(12122): KNOX_SDCARD checking this for 10136
I/libpersona(12122): KNOX_SDCARD not a persona
,I/SELinux (12122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12122): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12122 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11257:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12122): TimaSignature is unavailable
,D/ActivityThread(12122): Added TimaKeyStore provider
,D/ResourcesManager(12122): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12122): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3523): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3523): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3523): Not connected state, yet.
E/WifiStateMachine( 3523): VerifyingLinkState enter
,D/WifiStateMachine( 3523): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3523): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3523): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiNative-HAL( 3523): callSECApiInt - ID [210]
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3523): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3523): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/WebViewFactory(12122): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12122): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine.DnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/LibraryLoader(12122): Loading: webviewchromium
,D/ConnectivityService( 3523): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3523): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3523): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
I/LibraryLoader(12122): Time to load native libraries: 4 ms (timestamps 8655-8659)
I/LibraryLoader(12122): Expected native library version number "",actual native library version number ""
E/ConnectivityService( 3523): Unexpected mtu value: 0, wlan0
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3523): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3523): Now, connected state.
,E/WifiStateMachine( 3523): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
V/WebViewChromiumFactoryProvider(12122): Binding Chromium to main looper Looper (main, tid 1) {29a98745}
I/LibraryLoader(12122): Expected native library version number "",actual native library version number ""
,I/chromium(12122): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/WifiStateMachine( 3523): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3523): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/StatusBar.NetworkController( 3689): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3523): callSECApiVoid - ID [212]
,I/BrowserStartupController(12122): Initializing chromium process, renderers=0
,E/WifiStateMachine( 3523): ConnectedState Enter  mScreenOn=false scanperiod=20000
W/art     (12122): Attempt to remove local handle scope entry from IRT, ignoring
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
,W/AudioManagerAndroid(12122): Requires BLUETOOTH permission
,V/        ( 2846): QcRouteController
,W/chromium(12122): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12122): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12122): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,D/ConnectivityService( 3523): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3523): LTETest block dns file not exists
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3523):    accepting network in place of null
,D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3523): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3523): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3523): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3523): MasterInitialState.processMessage what=3
I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): updateIfacesLocked()
,V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 4761): CM callback handler got msg 524290
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
I/NSApplication(12122): Starting up...
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
D/StatusBar.NetworkController( 3689): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3689): applyOpen
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked() took 11ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12208): MountEmulatedStorage()
I/libpersona(12208): KNOX_SDCARD checking this for 10150
E/Zygote  (12208): v2
I/libpersona(12208): KNOX_SDCARD not a persona
,I/SELinux (12208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/System.out( 3523): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SELinux (12208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12208): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12208 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11225:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8751(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 382us total 10.216ms
,D/TimaKeyStoreProvider(12208): TimaSignature is unavailable
,D/ActivityThread(12208): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 257us total 7.953ms
,D/ResourcesManager(12208): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12208): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12208): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 580us total 8.305ms
,D/QuickConnect(12208): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12208): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12208): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:09:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283766052], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283766023]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
,D/ConnectivityService( 3523): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 4761): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524290
,E/Zygote  (12224): MountEmulatedStorage()
I/libpersona(12224): KNOX_SDCARD checking this for 10178
E/Zygote  (12224): v2
I/libpersona(12224): KNOX_SDCARD not a persona
,I/SELinux (12224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12224 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11273:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3689): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3689): updateDataNetType()
D/StatusBar.NetworkController( 3689): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3689): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3689): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3689): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3689): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3689): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/TimaKeyStoreProvider(12224): TimaSignature is unavailable
,D/ActivityThread(12224): Added TimaKeyStore provider
,D/ResourcesManager(12224): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12224): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12224): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12224): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12224): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12224): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12224): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/Zygote  (12247): MountEmulatedStorage()
E/Zygote  (12247): v2
I/libpersona(12247): KNOX_SDCARD checking this for 10082
I/libpersona(12247): KNOX_SDCARD not a persona
,I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12247 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/SELinux (12247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/SELinux (12247): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  (12260): MountEmulatedStorage()
E/Zygote  (12260): v2
I/libpersona(12260): KNOX_SDCARD checking this for 1000
I/libpersona(12260): KNOX_SDCARD not a persona
,I/SELinux (12260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12247): TimaSignature is unavailable
,I/ActivityManager( 3523): Killing 11290:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
D/ActivityThread(12247): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11400:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12260): TimaSignature is unavailable
,D/ActivityThread(12260): Added TimaKeyStore provider
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 90388(4MB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 49MB/65MB, paused 1.273ms total 83.710ms
,D/ResourcesManager(12247): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12260): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12247): onCreate
D/BadgeProvider(12247): DatabaseHelper
,W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12247): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3523): Killing 11419:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12247): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12247): sendNotify, [notify] : null
D/BadgeProvider(12247): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12247): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12247): update, [UpdateCount] : 1
,D/Launcher.Model( 4001): reloadBadges entered.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12280): MountEmulatedStorage()
E/Zygote  (12280): v2
I/libpersona(12280): KNOX_SDCARD checking this for 10013
I/libpersona(12280): KNOX_SDCARD not a persona
,I/SELinux (12280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12280): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12280 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12280): TimaSignature is unavailable
,D/ActivityThread(12280): Added TimaKeyStore provider
,D/ResourcesManager(12280): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3523): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6263): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6263): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor(11876): type=WIFI subType= reason=null isConnected=true
,D/WaitQueueForNetworkActivate(12280): notifyNetworkActivated
W/ResourceType( 5239): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5239): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/ContextImpl(12280): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,D/hcjo    (12280): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12280): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12280): exit::IDLE
D/InitializeManagerStateMachine(12280): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12280): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12280): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12280): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12280): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12280): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12280): entry::SUCCESS
D/hcjo    (12280): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12280): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12280): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12280): exit::SUCCESS
D/InitializeManagerStateMachine(12280): entry::IDLE
,I/Hs20UtilService( 4083): Starting #10
,I/Hs20UtilService( 4083): Message received 5007
,D/NearbySettings( 8781): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8781): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8781): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 3523): Killing 11436:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SignOutReceiver(11376): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4083): Starting #11
,I/Hs20UtilService( 4083): Message received 5007
,D/NearbySettings( 8781): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8781): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11376): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4083): Starting #12
,D/NearbySettings( 8781): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8781): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 4083): Message received 5007
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8781): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8781): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8781): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11376): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4083): Starting #13
,I/Hs20UtilService( 4083): Message received 5007
,D/NearbySettings( 8781): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8781): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3523): callSECApi what=220
D/WifiStateMachine( 3523): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11376): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11848): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11848): sales region : global
I/PCWCLIENTTRACE_PushUtil(11848): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11848): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11927): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11927): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger( 2850): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3523): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523
,D/mali_winsys( 3689): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(11944): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11944): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11944): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11960): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 21:09:26 GMT+01:00 2016
,I/KLMS-2.4.521: (11960): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11960): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11960): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(11976): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11960): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11960): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11960): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11960): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11960): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11960): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onDestroy()
,E/SPPClientService(12018): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11183): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11183): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11183): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11183): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11183): [OR] == isSIMCardReady false ==
,I/SA      (11183): [SCU] == networkStateCheck == true
I/SA      (11183): [DM] getCountryCodeFromCSC : PL
I/SA      (11183): isChinaCountryCode : false
I/SA      (11183): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11183): [OR] == networkStateCheck true ==
I/SA      (11183): [OR] GetMyCountryZoneTask
I/SA      (11183): [OR] onReceive END
,I/SA      (11183): [SRS] prepareGetMyCountryZone
,I/SA      (11183): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11183): [SSP] query invoked
,I/SA      (11183): [TPMU] GetMccFromDB : null
I/SA      (11183): [SCU] getMccFromPreferece mcc = 260
I/SA      (11183): [TPM] isNoProxy(default) : true
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SCloudBackupReceiver(12038): Other Intent
,D/accuweather( 5422): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5422): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5422): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5422): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5422): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5422): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5422): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12054): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12054): premStatus:2
,I/KnoxUsageLogPro(12054): isEulaShown : false
I/KnoxUsageLogPro(12054): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12100): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12100): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12100): stopCheckCategoryVersion
,D/QuickConnect(12208): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12208): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12208): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/hcjo    (12280): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12280): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12280): exit::IDLE
D/InitializeManagerStateMachine(12280): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12280): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12280): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12280): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12280): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12280): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12280): entry::SUCCESS
D/hcjo    (12280): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12280): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12280): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12280): exit::SUCCESS
D/InitializeManagerStateMachine(12280): entry::IDLE
,I/SA      (11183): [RC New] Execute method=[GET] start
,I/SA      (11183): [RC New] Security=[true]
,I/System.out(11183): Thread-1545(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11183): Thread-1545(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11183): Thread-1545(ApacheHTTPLog):isShipBuild true
I/System.out(11183): Thread-1545(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3523): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11183): [RC New] [v2liruge] api execute + 646
I/SA      (11183): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11183): AsyncTask #1 calls detatch()
,I/SA      (11183): [TPMU] getNetworkMcc : 
,I/SA      (11183): [SCU] saveMccToPreferece Start
I/SA      (11183): [SCU] RegionMCC : 260
I/SA      (11183): [SSP] query invoked
,I/SA      (11183): [TPMU] GetMccFromDB : null
I/SA      (11183): [SCU] getMccFromPreferece mcc = 260
I/SA      (11183): [SCU] saveMccToPreferece End
,I/SA      (11183): [RC New] executeRequest [v2liruge] end. 667
I/SA      (11183): [RC New] Execute end
I/SA      (11183): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11183): [OR] GetMyCountryZoneTask Success
,I/jxcore-log(11722): Test app app.js loaded
I/jxcore-log(11722): 
,I/chromium(11722): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium(11722): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3523): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3523): route cmd failed: 
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
D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3689): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4761): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4761): CM callback handler got msg 524295
,I/dhcpcd  (11991): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4615): callingUid 10014, callindPid: 4615
,D/ResourcesManager(11876): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11876): Using the GMSCore's GoogleHttpClient
,D/WearableClient(11876): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11876): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11876): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11876): WearableClientImpl.onPostInitHandler: done
I/MusicLeanback(11876): Conditions not met for autocaching.
I/MusicLeanback(11876): Stop autocaching.
,E/GmsUtils(11876): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11876): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11876): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1ac2038b that was originally bound here
E/ActivityThread(11876): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1ac2038b that was originally bound here
E/ActivityThread(11876): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11876): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11876): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11876): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11876): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11876): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11876): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11876): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11876): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11876): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11876): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11876): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11876): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11876): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11876): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11876): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11876): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11876): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11876): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11876): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11876): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2850): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3523): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3523) eventTime = 142878
,D/PowerManagerService( 3523): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523 (0x0)
D/PowerManagerService( 3523): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3523, ws=WorkSource{10060}) (elapsedTime=3475)
,I/GAV4    (12122): Thread[GAThread,5,main]: No campaign data found.
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 260, CUR = 56
,I/PowerManagerService( 3523): [PWL] Off : 50s ago
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-170, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:83
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PCWCLIENTTRACE_SYSTEMReceiver(11848): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11848): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11848): ================================================
,I/CSTORAGE(11848):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11848): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11848): [GetString-S]
,E/art     (11848): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11848): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11848): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11848): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11848): sales region : global
,I/PCWCLIENTTRACE_PushUtil(11848): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11848): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11991): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PreloadUpdateManagerStateMachine(12280): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12280): exit::IDLE
D/PreloadUpdateManagerStateMachine(12280): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12280): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12280): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine(12280): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12280): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12280): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12280): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12280): exit::IDLE
D/PreloadUpdateManagerStateMachine(12280): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12280): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12280): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12280): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12280): entry::IDLE
,I/dhcpcd  (11991): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11991): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 259, CUR = -170
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:-18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:76
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3523): Waited long enough for: ServiceRecord{9f4ba30 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3523): !@Sync 5
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 254, CUR = -18
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 75s ago
,V/AlarmManager( 3523): waitForAlarm result :8
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 253, CUR = 34
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4615): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 253, CUR = 50
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 6
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 251, CUR = 52
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3523): [PWL] Off : 105s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 245, CUR = 50
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 243, CUR = 49
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3689): handleTimeUpdate
,D/KeyguardEffectViewController( 3689): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3689): *** don't update sliding image ***
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3689): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3523): !@Sync 7
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 242, CUR = 46
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3523): waitForAlarm result :8
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 242, CUR = 42
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 238, CUR = 41
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 8
,D/SSRM:n  ( 3523): SIOP:: AP = 230, PST = 237, CUR = 39
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5644): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5644): Disconnected process message: 10
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11722): --= Surplus to requirements =--,
I/jxcore-log(11722): 
,I/jxcore-log(11722): ****TEST TOOK:  ms ****
I/jxcore-log(11722): 
,I/jxcore-log(11722): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11722): 
,D/AndroidRuntime(12565): 
D/AndroidRuntime(12565): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12565): CheckJNI is OFF
,D/AndroidRuntime(12565): readGMSProperty: start
D/AndroidRuntime(12565): readGMSProperty: already setted!!
,D/AndroidRuntime(12565): readGMSProperty: end
D/AndroidRuntime(12565): addProductProperty: start
,E/AffinityControl(12565): AffinityControl: registerfunction enter
,D/AndroidRuntime(12565): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3523): START PACKAGE DELETE: observer{375821223}
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
,D/PackageManager( 3523): !@killApplicatoin: 10552, uninstall pkg
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10552 user=-1: uninstall pkg
,I/ActivityManager( 3523): Killing 11722:com.test.thalitest/u0a552 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{474414e u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,W/PackageSettings( 3523): Skipping PackageSetting{1fcd97e8 com.example.hello/10549} due to missing metadata
,D/WifiService( 3523): Client connection lost with reason: 4
,I/WindowState( 3523): WIN DEATH: Window{2fe12444 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10552 user=0: pkg removed
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 2850): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2850): id=14 Removed NainActivit (-2/8)
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{474414e u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3523): Duplicate finish request for ActivityRecord{474414e u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/art     ( 8939): Explicit concurrent mark sweep GC freed 28458(1607KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.146ms total 43.527ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
,I/art     ( 4052): Explicit concurrent mark sweep GC freed 35767(2MB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 977us total 76.198ms
,E/Zygote  (12587): MountEmulatedStorage()
E/Zygote  (12587): v2
I/libpersona(12587): KNOX_SDCARD checking this for 10063
I/libpersona(12587): KNOX_SDCARD not a persona
,W/GeofencerStateMachine( 4615): Ignoring removeGeofence because network location is disabled.
,D/LWLocationManager(11455): getDeviceLocationId :  id = -100
I/SELinux (12587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12587 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
E/SamsungIME( 4463): mOCRHelper is null
,I/SELinux (12587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/LocationWidgetApplication(11455): getLastUiLocationId() : mLastUiLocationId = -100
,E/SELinux (12587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/TimaKeyStoreProvider(12587): TimaSignature is unavailable
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
D/ActivityThread(12587): Added TimaKeyStore provider
,D/SecContentProvider2( 3523): uri = 14 selection = getSealedState
D/SecContentProvider2( 3523): mCursor = null
,D/ApplicationPolicy( 3523): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ResourceType( 5239): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5239): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12587): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6263): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6263): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6263): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6263): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
,I/DBG_DM  ( 6263): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2850): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12587): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12587): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12587): packagename:com.test.thalitest
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6263): updateVisibility : ActivityRecord{3daddfca token=android.os.BinderProxy@24e59e9f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 51677(3MB) AllocSpace objects, 43(688KB) LOS objects, 24% free, 49MB/65MB, paused 4.453ms total 223.451ms
,I/art     ( 3523): WaitForGcToComplete blocked for 128.765ms for cause Explicit
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/KLMS-2.4.521: (11960): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 21:11:28 GMT+01:00 2016
,I/KLMS-2.4.521: (11960): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onCreate()
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11960): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11960): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,E/Zygote  (12606): MountEmulatedStorage()
E/Zygote  (12606): v2
I/libpersona(12606): KNOX_SDCARD checking this for 10106
I/libpersona(12606): KNOX_SDCARD not a persona
D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SELinux (12606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12606): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12606 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (11960): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/InputMethodManagerService( 3523): Got RemoteException sending setActive(false) notification to pid 11722 uid 10552
,I/KLMS-2.4.521: (11960): KLMSIntentService(): PACKAGE_REMOVED
,I/Timeline( 6263): Timeline: Activity_idle id: android.os.BinderProxy@24e59e9f time:261150
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.4.521: (11960): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11960): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/TimaKeyStoreProvider(12606): TimaSignature is unavailable
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ActivityThread(12606): Added TimaKeyStore provider
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/RCPManager(12054):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3523):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/RegisteredServicesCache( 3965): empty dynamic service
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ActivityManager( 3523): mDVFSHelper.release()
,I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{1e240ab5 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:261217
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12606): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12624): MountEmulatedStorage()
E/Zygote  (12624): v2
,I/libpersona(12624): KNOX_SDCARD checking this for 10050
I/libpersona(12624): KNOX_SDCARD not a persona
,I/SELinux (12624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/SELinux (12624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12624 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/SELinux (12624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/elm:14491(12606): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12606): ELMEngine.ELMEngine( context ).
,D/elm:14491(12606): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(11455): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 7121(327KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 3.463ms total 184.096ms
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/elm:14491(12606): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.4.521: (11960): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:14491(12606): ElmAgentService : onCreate()
,D/elm:14491(12606): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12606): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12606): MDMBridge.getInstance()
D/elm:14491(12606): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.4.521: (11960): KLMSIntentService(): onDestroy()
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14491(12606): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider(12624): TimaSignature is unavailable
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ActivityThread(12624): Added TimaKeyStore provider
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/PackageManager( 3523): delete codoeFile: 
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(11455): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11455): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11455): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11455): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/AASAUninstall( 3523):  com.test.thalitest not target!
D/PackageManager( 3523): result of delete: 1{375821223}
,E/Zygote  (12641): MountEmulatedStorage()
I/libpersona(12641): KNOX_SDCARD checking this for 10101
E/Zygote  (12641): v2
I/libpersona(12641): KNOX_SDCARD not a persona
,D/AndroidRuntime(12565): Shutting down VM
I/SELinux (12641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12641 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/SELinux (12641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12641): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/elm:14491(12606): ElmAgentService : onDestroy().
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider(12641): TimaSignature is unavailable
,D/ActivityThread(12641): Added TimaKeyStore provider
D/ResourcesManager(12624): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/Zygote  (12656): MountEmulatedStorage()
,E/Zygote  (12656): v2
I/libpersona(12656): KNOX_SDCARD checking this for 10183
I/libpersona(12656): KNOX_SDCARD not a persona
,I/SELinux (12656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager(12624): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12624): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SELinux (12656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourcesManager(12624): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12624): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SELinux (12656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager(12624): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12656 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,W/ResourcesManager(12624): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12624): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
W/ResourcesManager(12624): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12656): TimaSignature is unavailable
,D/ActivityThread(12656): Added TimaKeyStore provider
,E/Zygote  (12671): MountEmulatedStorage()
E/Zygote  (12671): v2
I/libpersona(12671): KNOX_SDCARD checking this for 10019
I/libpersona(12671): KNOX_SDCARD not a persona
,D/ResourcesManager(11455): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux (12671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SELinux (12671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(12641): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/SELinux (12671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12671 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(11455): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/ActivityManager( 3523): Killing 11472:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/ActivityManager( 3523): Killing 11488:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(12656): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/TimaKeyStoreProvider(12671): TimaSignature is unavailable
,D/ActivityThread(12671): Added TimaKeyStore provider
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(12671): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/SQLiteLog(12656): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/DocsApplication(12641): Installing DEX configuration.
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/UsbSettingsManager( 3523): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3523): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/DexInstaller(12641): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/PackageInfoHelper(12641): Provided clientMode=RELEASE, packageInfo=PackageInfo{388b5a82 com.google.android.apps.docs}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/TAG     (12641): onCreate()
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/CrossAppStateProvider(12641): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  (12689): MountEmulatedStorage()
E/Zygote  (12689): v2
I/libpersona(12689): KNOX_SDCARD checking this for 10190
I/libpersona(12689): KNOX_SDCARD not a persona
,I/SELinux (12689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12689): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11455): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12689 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12671): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12671): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver(12671): onReceive() : package name is not s health. Return !!!
,D/PackageManager( 3523): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Books/Books.apk
,D/RCPManagerService( 3523): PackageReceiver onReceive()
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10552
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/LocationWidgetApplication(11455): getLastUiLocationId() : mLastUiLocationId = -100
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 895us total 31.760ms
,D/TimaKeyStoreProvider(12689): TimaSignature is unavailable
,D/ActivityThread(12689): Added TimaKeyStore provider
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ActivityManager( 3523): Killing 10786:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 710us total 14.502ms
,D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 693us total 11.279ms
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=24_task.xml
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/StatusBar( 3689): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ResourcesManager(12689): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/PCWCLIENTTRACE_PushUtil(11848): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11848): sales region : global
I/PCWCLIENTTRACE_PushUtil(11848): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11848): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/NearbySource(12624): Nearby Source Create!
,D/NearbyContext(12624): Nearby Context Create!
D/PersonaManager( 3689): isKioskContainerExistOnDevice
D/PersonaManager( 3689): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3689): Icon Only
I/StatusBar( 3689): Icon Only
,D/PanelView( 3689): There is/are notification(s) 
D/PanelView( 3689): There is/are notification(s) 
,D/PersonaManager( 3689): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3689): Icon Only
I/StatusBar( 3689): Icon Only
D/PanelView( 3689): There is/are notification(s) 
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12689): onReceive()
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12689): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,E/Zygote  (12706): MountEmulatedStorage()
I/libpersona(12706): KNOX_SDCARD checking this for 10035
E/Zygote  (12706): v2
I/libpersona(12706): KNOX_SDCARD not a persona
,I/SELinux (12706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12706 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (12706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,I/ActivityManager( 3523): Killing 11607:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/TapandpayWidget:Utils(12689): Clear T&P info.
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/TapandpayWidget:TanpandpayAppWidgetProvider(12689): Widget is not attached.
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12624): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12624): Samsung link source created
D/TimaKeyStoreProvider(12706): TimaSignature is unavailable
D/ActivityThread(12706): Added TimaKeyStore provider
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Maps/Maps.apk
I/ActivityManager( 3523): Killing 12247:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/PanelView( 3689): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,E/SQLiteLog(12624): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/PackageBroadcastService( 4761): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4761): Clearing selected account for com.test.thalitest
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/SQLiteDatabase(12624): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12624): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12624): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12624): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12624): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12624): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12624): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12624): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12624): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12624): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12624): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12624): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12624): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12624): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12624): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12624): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12624): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12624): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12624): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12624): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12624): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12624): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12624): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12624): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12624): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12624): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12624): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12624): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12624): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/SQLiteLog( 4761): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4761): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/LocationSettingsChecker( 4761): Removing dialog suppression flag for package com.test.thalitest
E/DriveAsyncService( 4761): disk I/O error (code 3850)
E/DriveAsyncService( 4761): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4761): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4761): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4761): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4761): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4761): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4761): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4761): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4761): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4761): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4761): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4761): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4761): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4761): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4761): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4761): 	at java.lang.Thread.run(Thread.java:818)
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/SQLiteLog( 4761): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
E/SQLiteDatabase( 4761): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4761): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4761): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4761): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4761): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4761): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4761): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4761): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 4761): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4761): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4761): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4761): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4761): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4761): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4761): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4761): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ResourcesManager(11455): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
W/SQLiteOpenHelper( 4761): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4761): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4761): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 4761): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/ChimeraCfgMgr( 4761): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4761): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 4761): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 4761): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4761): Process: com.google.android.gms, PID: 4761
E/AndroidRuntime( 4761): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4761): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4761): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4761): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4761): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4761): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4761): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4761): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4761): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/ContactProvider(12624): getAllContactInfoList Start
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
D/ResourcesManager(11455): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/SQLiteLog( 4761): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 4761): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4761): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4761): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4761): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4761): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 4761): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 4761): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 4761): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 4761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4761): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 4761): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 4761): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4761): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4761): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4761): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 4761): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/FeatureConfig(12706): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager(11455): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,E/SQLiteLog( 4761): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 4761): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 4761): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 4761): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,D/MtpClient(12624): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12624): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/SharedPreferencesImpl(12624): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12706): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ChimeraCfgMgr( 4761): Loading module com.google.android.gms.games from APK com.google.android.play.games
W/ResourcesManager(12706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ChimeraModuleLdr( 4761): Module APK com.google.android.play.games already loaded
W/ResourcesManager(12706): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11455): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12706): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SQLiteLog( 4761): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4761): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
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
D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
E/ClearPendingStateOp( 4761): Runtime exception while performing operation
E/ClearPendingStateOp( 4761): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4761): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4761): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 4761): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4761): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 4761): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4761): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4761): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 4761): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4761): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4761): 	at ,android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4761): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4761): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4761): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4761): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4761): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 4761): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4761): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4761): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4761): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager(12706): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  (12742): MountEmulatedStorage()
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/Zygote  (12742): v2
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
I/libpersona(12742): KNOX_SDCARD checking this for 10052
I/libpersona(12742): KNOX_SDCARD not a persona
,I/SELinux (12742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3523): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12742 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (12742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/SELinux (12742): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 4761): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4761): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 4761): Sending signal. PID: 4761 SIG: 9
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
,E/SQLiteLog( 4615): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4615): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4615): Shutting down VM
,E/AndroidRuntime( 4615): FATAL EXCEPTION: main
E/AndroidRuntime( 4615): Process: com.google.android.gms.persistent, PID: 4615
E/AndroidRuntime( 4615): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4615): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4615): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4615): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4615): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4615): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4615): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4615): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4615): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4615): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4615): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4615): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4615): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4615): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4615): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4615): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4615): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4615): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4615): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4615): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4615): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4615): 	... 9 more
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(11455): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
W/ActivityManager( 3523): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager( 3523): Killing 4615:com.google.android.gms.persistent/u0a14 (adj 0): crash,
,W/ResourcesManager(12706): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
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
,E/JavaBinder( 3523): !!! FAILED BINDER TRANSACTION !!!
V/BackupManagerService( 3523): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ConnectivityService( 3523): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@74d346e)
,V/BackupManagerService( 3523): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
,D/TimaKeyStoreProvider(12742): TimaSignature is unavailable
,D/ActivityThread(12742): Added TimaKeyStore provider
D/ConnectivityService( 3523): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 3523): Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@1ce9deeb (in com.google.android.gms)
W/ActivityManager( 3523): android.os.TransactionTooLargeException
W/ActivityManager( 3523): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3523): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3523): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager( 3523): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1686)
W/ActivityManager( 3523): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:17705)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6129)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:7561)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:14542)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:14421)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15187)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14695)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14677)
W/ActivityManager( 3523): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1457)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ConnectivityService( 3523): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/BroadcastQueue( 3523): Unable to launch app com.google.android.gms/10014 for broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.android.mms/.freemessage.FreeMessageStatusReceiver (has extras) }: process is bad
,W/ResourcesManager(12706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/ActivityManager( 3523): Process com.google.android.gms (pid 4761)(adj 0) has died(288,1200)
W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20999ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30998ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30998ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 30997ms,
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 40997ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 40996ms
,W/ResourcesManager(12706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12742): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
,W/ResourcesManager(12742): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12742): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12742): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(12742): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12742): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12742): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager(12706): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/GpsStatusListenerHelper( 3523): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@dacc39c
D/LocationManagerService( 3523): Location listener died
I/LocationManagerService( 3523): remove 11eb0e48 by com.google.android.gms
,D/LocationManagerService( 3523): provider request: passive ProviderRequest[ON interval=0]
D/WifiService( 3523): Client connection lost with reason: 4
,D/LocationManagerService( 3523): Location listener died
,I/LocationManagerService( 3523): remove 3e9311a0 by com.google.android.gms
,D/LocationManagerService( 3523): provider request: passive ProviderRequest[ON interval=0]
,I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12706): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12763): MountEmulatedStorage()
E/Zygote  (12763): v2
I/libpersona(12763): KNOX_SDCARD checking this for 10036
I/libpersona(12763): KNOX_SDCARD not a persona
,I/SELinux (12763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
,I/SELinux (12763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12763): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12763 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog(12641): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 3523): Killing 8781:com.android.settings/1000 (adj 13): bgCount ##31
,E/SQLiteDatabase(12641): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12641): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12641): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12641): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12641): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12641): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12641): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12641): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12641): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12641): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12641): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12641): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12641): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12641): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12641): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12641): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12641): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12641): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12641): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12641): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12641): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12641): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12641): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12641): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12641): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12641): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12641): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12641): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12641): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12641): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12641): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12641): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12641): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at aEV.a(Gelly,InjectorStore.java:130)
E/SQLiteOpenHelper(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12641): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12641): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12641): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12641): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12641): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12641): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12641): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12641): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12641): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12641): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12641): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12641): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12641): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12641): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12641): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12641): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12641): Opened ClientFlag.db in read-only mode
E/ActivityThread(11823): Failed to find provider info for com.facebook.appmanager.installrecord
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12706): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager(12706): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,D/TimaKeyStoreProvider(12763): TimaSignature is unavailable
,D/ActivityThread(12763): Added TimaKeyStore provider
,E/SQLiteLog(12641): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12641): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12641): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12641): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12641): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12641): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12641): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12641): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12641): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12641): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12641): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12641): Process: com.google.android.apps.docs, PID: 12641
E/AndroidRuntime(12641): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12641): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12641): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12641): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12641): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12641): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12641): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12641): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12641): 	at aFp.run(AbstractDatabaseInstance.java:471)
,E/Zygote  (12780): MountEmulatedStorage()
E/Zygote  (12780): v2
I/libpersona(12780): KNOX_SDCARD checking this for 10031
I/libpersona(12780): KNOX_SDCARD not a persona
,I/SELinux (12780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SELinux (12780): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12780 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11908:com.sec.android.cloudagent/u0a2 (adj 13): bgCount ##31
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/WifiService( 3523): Client connection lost with reason: 4
W/ResourcesManager(12706): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ContactProvider(12624): getAllContactInfoList End
I/syncContacts(12624): thread: 1748, sync time = 683
,D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(12706): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SQLiteLog(12641): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12641): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12641): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512),
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12641): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12641): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12641): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12641): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12641): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12641): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12641): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12641): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12641): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12641): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12641): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12641): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12641): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12641): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12641): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12641): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12641): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12641): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12641): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12641): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12641): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12641): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12641): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12641): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper(12641): Opened ClientFlag.db in read-only mode
,D/Mms/MmsApp(12742): [start]    onCreate() consume time = 0.0
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,D/ResourcesManager(12706): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/Mms/ArtClassLoader(12742): init before art
,W/ResourcesManager(12706): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(12706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12780): TimaSignature is unavailable
,D/ActivityThread(12780): Added TimaKeyStore provider

```
