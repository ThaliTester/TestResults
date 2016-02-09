#### Test 58135655e9e7eb8_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3518): SIOP:: AP = 260, PST = 274, CUR = 66
--------- beginning of main
D/AndroidRuntime(11830): 
D/AndroidRuntime(11830): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11830): CheckJNI is OFF
D/AndroidRuntime(11830): readGMSProperty: start
D/AndroidRuntime(11830): readGMSProperty: already setted!!
D/AndroidRuntime(11830): readGMSProperty: end
D/AndroidRuntime(11830): addProductProperty: start
E/AffinityControl(11830): AffinityControl: registerfunction enter
D/AndroidRuntime(11830): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3518): inState():  stateMachine is null !!
I/PersonaManagerService( 3518): PersonaId don't exist
I/ActivityManager( 3518): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3518): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3518): mDVFSHelper.acquire()
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/Zygote  (11848): MountEmulatedStorage()
E/Zygote  (11848): v2
I/libpersona(11848): KNOX_SDCARD checking this for 10644
I/libpersona(11848): KNOX_SDCARD not a persona
I/SELinux (11848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3518): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11848 uid=10644 gids={50644, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11848): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11830): Shutting down VM
D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11848): TimaSignature is unavailable
D/ActivityThread(11848): Added TimaKeyStore provider
D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3518): stay LED for fully charged
D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
I/MotionRecognitionService( 3518): Plugged
I/MotionRecognitionService( 3518): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
V/ActivityThread( 6243): updateVisibility : ActivityRecord{1450f6b0 token=android.os.BinderProxy@27f9f3ad {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager(11848): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5654): Disconnected process message: 10
I/WebViewFactory(11848): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11848): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11848): Loading: webviewchromium
I/LibraryLoader(11848): Time to load native libraries: 4 ms (timestamps 5258-5262)
I/LibraryLoader(11848): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11848): Binding Chromium to main looper Looper (main, tid 1) {3d50e2c3}
I/LibraryLoader(11848): Expected native library version number "",actual native library version number ""
I/chromium(11848): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11848): Initializing chromium process, renderers=0
W/art     (11848): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11848): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11848): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11848): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11848): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11848): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11848): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11848): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11848): CordovaWebView is running on device made by: samsung
W/art     (11848): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11848): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11848): performCreate Call secproduct feature valuefalse
D/Activity(11848): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11848): Render dirty regions requested: true
D/ActivityManager( 3518): post active user change for 0
D/KnoxTimeoutHandler( 3518): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3518): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11848): Initialized EGL, version 1.4
I/OpenGLRenderer(11848): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1281957616 
D/OpenGLRenderer(11848): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11848): Enabling debug mode 0
D/mali_winsys(11848): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11848): updateVisibility : ActivityRecord{272002b3 token=android.os.BinderProxy@281e49e6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3518): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3518): mDVFSHelper.release()
I/Timeline( 3518): Timeline: Activity_windows_visible id: ActivityRecord{d46d06d u0 com.test.thalitest/.MainActivity t26} time:215650
W/IInputConnectionWrapper(11848): showStatusIcon on inactive InputConnection
I/Timeline(11848): Timeline: Activity_idle id: android.os.BinderProxy@281e49e6 time:215657
D/JsMessageQueue(11848): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(11848): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11848): 
D/jxcore_app_log(11848): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1260401920
I/chromium(11848): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11848): Initializing JXcore engine
W/jxcore-log(11848): JXcore engine is ready
,E/auditd  ( 4602): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3518): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3518): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11848): Starting JXcore engine
,W/jxcore-log(11848): Platform android
W/jxcore-log(11848): 
W/jxcore-log(11848): Process ARCH arm
W/jxcore-log(11848): 
,I/jxcore-log(11848): JXcore Cordova bridge is ready!
I/jxcore-log(11848): 
W/jxcore-log(11848): JXcore engine is started
,I/jxcore-log(11848): Toggling radios to true
I/jxcore-log(11848): 
,D/BluetoothAdapter(11848): enable()
,D/BluetoothAdapter(11848): enable(): BT is already enabled..!
,D/WifiService( 3518): New client listening to asynchronous messages
,I/WifiManager(11848): packageName : com.test.thalitest
,D/SecContentProvider( 3518): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3518): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3518): mCursor = null
,D/WifiService( 3518): setWifiEnabled: true pid=11848, uid=10644
E/WifiService( 3518): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3518): Permission Denial: getCurrentUser() from pid=11848, uid=10644 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3518): Failed getting userId using ActivityManagerNative
W/WifiService( 3518): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11848, uid=10644 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3518): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3518): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3518): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3518): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3518): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3518): name = wifi_on
,I/WifiService( 3518): disconnect: pid=11848, uid=10644
,I/wpa_supplicant( 3825): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11848): Radios toggled
I/jxcore-log(11848): 
I/jxcore-log(11848): My device name is: samsung-SM-N910C
I/jxcore-log(11848): 
I/wpa_supplicant( 3825): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3825): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3518): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3825): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): Disconnected - do not scan
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3518): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3518): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3518): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3518): do suspend true
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
,D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3518): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3518): updateNetworkInfo()
D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3518): updateNetworkInfo()
D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
I/Hs20UtilService( 4115): Starting #8
I/Hs20UtilService( 4115): Message received 5007
D/NearbySettings( 8850): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8850): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8850): MountReceiver.onReceive - Create mPrefHandler
,E/WifiStateMachine( 3518): Start Disconnecting Watchdog 1
D/NearbySettings( 8850): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> SCANNING
V/NearbySettings( 8850): DMSUtil.isNetworkConnected - flag-null, state-null
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3825): First Scan Start
,E/WifiStateMachine( 3518): ConnectModeState: Network connection lost 
,I/wpa_supplicant( 3825): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3518): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine( 3518): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3518): do suspend true
,D/WifiService( 3518): New client listening to asynchronous messages
,I/NearbySettings( 8850): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8850): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8850): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11479): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3518): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
E/WifiStateMachine( 3518): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
D/EntConnectivity( 3518): Not allowed due to - mEnabled false
D/ConnectivityService( 3518): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3518): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3518): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 3972): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524292
,D/WifiStateMachine( 3518): updateConfiguredNetworkExpiration - currTime: 1455021658185
D/WifiStateMachine( 3518): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3518): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3518): NetworkAgent: NetworkAgent channel lost
,D/EntConnectivity( 3518): Not allowed due to - mEnabled false
D/ConnectivityService( 3518): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3518): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/Tethering( 3518): MasterInitialState.processMessage what=3
D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3518): UpdateStatsForKnox
V/NetworkStats( 3518): updateIfacesLocked()
V/NetworkStats( 3518): performPollLocked(flags=0x1)
,D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,V/NetworkStats( 3518): performPollLocked() took 3ms
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,I/Hs20UtilService( 4115): Starting #9
,I/Hs20UtilService( 4115): Message received 5007
,D/NearbySettings( 8850): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8850): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8850): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8850): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8850): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,I/SignOutReceiver(11479): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3972): FileWriteThread : threadType = 3
,D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3518): updateDataUsageMap
I/ApplicationPolicy( 3518): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
,D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3518): No Active Data Connection
D/GpsLocationProvider( 3518): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11940): MountEmulatedStorage()
I/libpersona(11940): KNOX_SDCARD checking this for 10110
E/Zygote  (11940): v2
I/libpersona(11940): KNOX_SDCARD not a persona
,I/SELinux (11940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11940): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11940 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11940): TimaSignature is unavailable
,D/ActivityThread(11940): Added TimaKeyStore provider
,D/ResourcesManager(11940): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11940): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11940): not using cross-dex optimization: ART in use
,I/art     (11940): Thread[1,tid=11940,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x889ebf28,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11940): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11940): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
V/DexLibLoader(11940): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11940): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
,D/DexLibLoader(11940): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11940): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11940): loading pre-built fallback odex files
V/MultiDexClassLoader(11940): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11940): released odex store lock
D/DexLibLoader(11940): DexLibLoader.loadAll took 18 ms
,W/ca      (11940): Verify
,W/LightSharedPreferencesImpl(11940): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11940): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11940): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11940): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11940): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11940): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11940): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11940): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11940): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11940): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11940): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11940): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11940): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11940): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11940): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11940): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11940): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11940): 	... 10 more
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/Zygote  (11965): MountEmulatedStorage()
I/libpersona(11965): KNOX_SDCARD checking this for 1000
E/Zygote  (11965): v2
I/libpersona(11965): KNOX_SDCARD not a persona
I/SELinux (11965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11082:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 486us total 10.294ms
,W/appmanager(:<default>):b(11940): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 269us total 8.421ms
,D/TimaKeyStoreProvider(11965): TimaSignature is unavailable
,D/ActivityThread(11965): Added TimaKeyStore provider
,W/appmanager(:<default>):b(11940): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 430us total 8.896ms
,D/ResourcesManager(11965): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11965): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11965): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11965): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11965): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11965): sales region : global
I/PCWCLIENTTRACE_PushUtil(11965): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11965): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11965): noConnectivity : true
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl(11940): Exposure of experiment com.facebook.common.network.l@13c60cb6 occurred when no user was logged in
,E/Zygote  (11988): MountEmulatedStorage()
I/libpersona(11988): KNOX_SDCARD checking this for 10135
E/Zygote  (11988): v2
I/libpersona(11988): KNOX_SDCARD not a persona
,I/SELinux (11988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3518): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11988 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11988): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11988): TimaSignature is unavailable
,D/ActivityThread(11988): Added TimaKeyStore provider
,I/ActivityManager( 3518): Killing 11091:com.policydm/1000 (adj 15): bgCount ##31
,W/BroadcastQueue( 3518): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{113ab068 u0 ReceiverList{13b6b78b 11940 com.facebook.appmanager/10110/u0 remote:1b7da95a}}
,W/BroadcastQueue( 3518): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{113ab068 u0 ReceiverList{13b6b78b 11940 com.facebook.appmanager/10110/u0 remote:1b7da95a}}
,D/ResourcesManager(11988): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3518): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1bb408ac u0 ReceiverList{1ac0f65f 11940 com.facebook.appmanager/10110/u0 remote:9690efe}}
,I/MusicStore(11988): Database version: 104
,D/ResourcesManager(11988): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11988): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11988): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11988): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11988): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11988): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@124666e7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11988): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11988): GMSCore installation verified
,I/ConfigStore(11988): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11988): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11940): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/ContextImpl(11940): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11988): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11988): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11940): Exposure of experiment com.facebook.imagepipeline.a.g@7a44537 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11940): Exposure of experiment com.facebook.imagepipeline.a.d@17dd8d10 occurred when no user was logged in
,D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3518): getStreamVolume 3 index 0
,I/MediaRouter(11988): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3825): nl80211: Received scan results (2 BSSes)
I/wpa_supplicant( 3825): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3825): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3825): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3518): [1,455,021,659,242 ms] noteScanEnd no scan source
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3518): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1554c632 sup_state=SCANNING debouncing=false
,I/art     (11940): Explicit concurrent mark sweep GC freed 49797(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 559us total 23.659ms
W/appmanager(:<default>):m(11940): No feature status reporters found; is this dead code?
,E/Zygote  (12024): MountEmulatedStorage()
E/Zygote  (12024): v2
I/libpersona(12024): KNOX_SDCARD checking this for 10002
I/libpersona(12024): KNOX_SDCARD not a persona
,I/SELinux (12024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12024 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3518): setDetailed state send new extra info
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11988): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12024): TimaSignature is unavailable
,D/ActivityThread(12024): Added TimaKeyStore provider
,I/ActivityManager( 3518): Killing 11112:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11112/oom_score_adj; errno=22
,D/ResourcesManager(12024): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3825): Associated with C0.AA.48
E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3518): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,I/ActivityManager( 3518): Killing 11133:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12045): MountEmulatedStorage()
E/Zygote  (12045): v2
I/libpersona(12045): KNOX_SDCARD checking this for 1000
I/libpersona(12045): KNOX_SDCARD not a persona
,I/SELinux (12045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12045 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3518): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3518): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3825): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 3825): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3825): Blacklist: Clear (temp) 
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3518): Network connection established
,D/WifiNative-HAL( 3518): callSECApiVoid - ID [50]
E/WifiStateMachine( 3518): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3518): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3518): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3518): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3518): L2ConnectedState "NG700" nid=0
D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3518): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3518): updateNetworkInfo()
D/TimaKeyStoreProvider(12045): TimaSignature is unavailable
,D/ActivityThread(12045): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3518): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3518): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3518): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3518): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(12045): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3518): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12045): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12045): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12045): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12045): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12045): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3518): do suspend false
,D/SecContentProvider2( 3518): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3518): mCursor = null
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12062): MountEmulatedStorage()
E/Zygote  (12062): v2
I/libpersona(12062): KNOX_SDCARD checking this for 10012
I/libpersona(12062): KNOX_SDCARD not a persona
,I/SELinux (12062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12062): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12062 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12062): TimaSignature is unavailable
,D/ActivityThread(12062): Added TimaKeyStore provider
,D/ResourcesManager(12062): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3518): Killing 11150:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(12062): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/lowmemorykiller( 2828): Error writing /proc/11150/oom_score_adj; errno=22
,I/FOTA_Client(12062): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12062): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12078): MountEmulatedStorage()
I/libpersona(12078): KNOX_SDCARD checking this for 10021
E/Zygote  (12078): v2
I/libpersona(12078): KNOX_SDCARD not a persona
,I/SELinux (12078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12078 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 10960:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12078): TimaSignature is unavailable
,D/ActivityThread(12078): Added TimaKeyStore provider
,D/ResourcesManager(12078): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12078): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 13:40:59 GMT+01:00 2016
,I/KLMS-2.4.521: (12078): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12078): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12078): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12078): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12078): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12078): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12078): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12078): StateImplV2(): networkChangeListener().END
,E/Zygote  (12095): MountEmulatedStorage()
E/Zygote  (12095): v2
I/libpersona(12095): KNOX_SDCARD checking this for 10038
I/libpersona(12095): KNOX_SDCARD not a persona
,I/SELinux (12095): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12095): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12095): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12095 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12078): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3518): Killing 11167:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
D/TimaKeyStoreProvider(12095): TimaSignature is unavailable
D/ActivityThread(12095): Added TimaKeyStore provider
D/ResourcesManager(12095): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
E/dhcpcd  (12110): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  (12110): version 5.5.6 starting
E/dhcpcd  (12110): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/SO_AGENT(12095): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12116): MountEmulatedStorage()
I/libpersona(12116): KNOX_SDCARD checking this for 1000
E/Zygote  (12116): v2
I/libpersona(12116): KNOX_SDCARD not a persona
I/SELinux (12116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027,
E/SELinux (12116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3518): Killing 11228:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,I/dhcpcd  (12110): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12110): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12110): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12110): bssid match
I/dhcpcd  (12110): wlan0: rebinding lease of 192.168.1.124
,D/TimaKeyStoreProvider(12116): TimaSignature is unavailable
,D/ActivityThread(12116): Added TimaKeyStore provider
,D/ResourcesManager(12116): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12137): MountEmulatedStorage()
I/libpersona(12137): KNOX_SDCARD checking this for 10039
E/Zygote  (12137): v2
I/libpersona(12137): KNOX_SDCARD not a persona
,I/SELinux (12137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12137): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12137 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11210:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11210/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12137): TimaSignature is unavailable
,D/ActivityThread(12137): Added TimaKeyStore provider
,D/ResourcesManager(12137): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12137): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12137): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12137): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12137): PushLog.txt file is not deleted.
D/SPPClientService(12137): PushLog.txt file is not deleted.
D/SPPClientService(12137): ============PushLog. stop!
,I/SA      (11288): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11288): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11288): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11288): [SLFUCHKMGR] constructor called
,E/SPPClientService(12137): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11288): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11288): [OR] == isSIMCardReady false ==
,I/SA      (11288): [SCU] == networkStateCheck == false
I/SA      (11288): [OR] onReceive END
,V/DownloadManager( 5488): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3518): Killing 11246:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11246/oom_score_adj; errno=22
E/lowmemorykiller( 2828): Error writing /proc/11246/oom_score_adj; errno=22
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12157): MountEmulatedStorage()
I/libpersona(12157): KNOX_SDCARD checking this for 10067
E/Zygote  (12157): v2
I/libpersona(12157): KNOX_SDCARD not a persona
,I/SELinux (12157): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12157): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12157): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12157 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12157): TimaSignature is unavailable
,D/ActivityThread(12157): Added TimaKeyStore provider
,D/ResourcesManager(12157): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12157): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12157): Other Intent
,I/ActivityManager( 3518): Killing 11187:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5215): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5215): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12173): MountEmulatedStorage()
E/Zygote  (12173): v2
I/libpersona(12173): KNOX_SDCARD checking this for 1000
I/libpersona(12173): KNOX_SDCARD not a persona
,I/SELinux (12173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12173): TimaSignature is unavailable
,D/ActivityThread(12173): Added TimaKeyStore provider
,D/ResourcesManager(12173): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12173): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12173): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12173): premStatus:2
,I/KnoxUsageLogPro(12173): isEulaShown : false
I/KnoxUsageLogPro(12173): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12188): MountEmulatedStorage()
I/libpersona(12188): KNOX_SDCARD checking this for 10090
E/Zygote  (12188): v2
I/libpersona(12188): KNOX_SDCARD not a persona
I/SELinux (12188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12188): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12188 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11341:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8757(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 733us total 11.261ms
,D/TimaKeyStoreProvider(12188): TimaSignature is unavailable
,D/ActivityThread(12188): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 287us total 8.402ms
,D/ResourcesManager(12188): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 260us total 8.609ms
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12204): MountEmulatedStorage()
I/libpersona(12204): KNOX_SDCARD checking this for 10127
E/Zygote  (12204): v2
I/libpersona(12204): KNOX_SDCARD not a persona
,I/SELinux (12204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12204 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11359:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12204): TimaSignature is unavailable
,D/ActivityThread(12204): Added TimaKeyStore provider
,D/ResourcesManager(12204): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12204): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12204): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12204): stopCheckCategoryVersion
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12220): MountEmulatedStorage()
I/libpersona(12220): KNOX_SDCARD checking this for 10136
E/Zygote  (12220): v2
I/libpersona(12220): KNOX_SDCARD not a persona
,I/SELinux (12220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12220): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12220 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11310:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12220): TimaSignature is unavailable
,D/ActivityThread(12220): Added TimaKeyStore provider
,D/ResourcesManager(12220): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12220): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12220): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12220): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12220): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/AlarmManager( 3518): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,I/WebViewFactory(12220): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12220): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12220): Loading: webviewchromium
,I/LibraryLoader(12220): Time to load native libraries: 3 ms (timestamps 9071-9074)
I/LibraryLoader(12220): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12220): Binding Chromium to main looper Looper (main, tid 1) {25888a83}
,I/LibraryLoader(12220): Expected native library version number "",actual native library version number ""
,I/chromium(12220): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12220): Initializing chromium process, renderers=0
,W/art     (12220): Attempt to remove local handle scope entry from IRT, ignoring
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/chromium(12220): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(12220): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12220): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12220): Requires BLUETOOTH permission
,I/NSApplication(12220): Starting up...
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12288): MountEmulatedStorage()
I/libpersona(12288): KNOX_SDCARD checking this for 10150
E/Zygote  (12288): v2
I/libpersona(12288): KNOX_SDCARD not a persona
I/SELinux (12288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12288 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11377:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12288): TimaSignature is unavailable
,D/ActivityThread(12288): Added TimaKeyStore provider
,D/ResourcesManager(12288): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12288): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12288): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12288): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12288): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12288): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12303): MountEmulatedStorage()
E/Zygote  (12303): v2
I/libpersona(12303): KNOX_SDCARD checking this for 10178
I/libpersona(12303): KNOX_SDCARD not a persona
,I/SELinux (12303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12303 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11392:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12303): TimaSignature is unavailable
,D/ActivityThread(12303): Added TimaKeyStore provider
,D/ResourcesManager(12303): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12303): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12303): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12303): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12303): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12303): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,E/Zygote  (12326): MountEmulatedStorage()
I/libpersona(12326): KNOX_SDCARD checking this for 10082
E/Zygote  (12326): v2
I/libpersona(12326): KNOX_SDCARD not a persona
I/SELinux (12326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12326): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12326 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12342): MountEmulatedStorage()
I/libpersona(12342): KNOX_SDCARD checking this for 1000
E/Zygote  (12342): v2
I/libpersona(12342): KNOX_SDCARD not a persona
,I/SELinux (12342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11502:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12326): TimaSignature is unavailable
,D/ActivityThread(12326): Added TimaKeyStore provider
,I/ActivityManager( 3518): Killing 11519:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12342): TimaSignature is unavailable
,D/ActivityThread(12342): Added TimaKeyStore provider
,I/art     ( 3518): Explicit concurrent mark sweep GC freed 78817(4MB) AllocSpace objects, 38(608KB) LOS objects, 24% free, 49MB/65MB, paused 1.239ms total 85.642ms
,D/ResourcesManager(12326): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12342): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/ActivityManager( 3518): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12326): onCreate
D/BadgeProvider(12326): DatabaseHelper
,I/ActivityManager( 3518): Killing 11537:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/BadgeProvider(12326): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 3999): reloadBadges entered.
,D/BadgeProvider(12326): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12326): sendNotify, [notify] : null
D/BadgeProvider(12326): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12326): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12326): update, [UpdateCount] : 1
,I/iu.Environment( 6758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6758): num queued entries: 0
I/iu.UploadsManager( 6758): num updated entries: 0
,I/iu.SyncManager( 6758): NEXT; no task
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12360): MountEmulatedStorage()
I/libpersona(12360): KNOX_SDCARD checking this for 10013
E/Zygote  (12360): v2
I/libpersona(12360): KNOX_SDCARD not a persona
,I/SELinux (12360): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12360): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12360): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12360 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12360): TimaSignature is unavailable
,D/ActivityThread(12360): Added TimaKeyStore provider
,D/ResourcesManager(12360): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/dhcpcd  (12110): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/ActivityManager( 3518): Killing 11572:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/dhcpcd  (12110): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/Hs20UtilService( 4115): Starting #10
,I/Hs20UtilService( 4115): Message received 5007
,D/NearbySettings( 8850): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8850): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8850): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8850): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8850): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11479): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3518): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3518): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3518): do suspend true
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11848): 
,D/WifiP2pService( 3518): InactiveState{ what=143375 }
D/WifiP2pService( 3518): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3518): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3518): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3518): Not connected state, yet.
E/WifiStateMachine( 3518): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3518): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3518): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3518): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3518): callSECApiInt - ID [210]
E/WifiStateMachine( 3518): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3518): updateNetworkInfo()
,D/ConnectivityService( 3518): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3518): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3518): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3518): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4115): Starting #11
,D/NearbySettings( 8850): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 4115): Message received 5007
I/NearbySettings( 8850): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3518): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/SignOutReceiver(11479): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3518): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine( 3518): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3518): Now, connected state.
E/WifiStateMachine( 3518): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3518): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService( 3518): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3518): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3518): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3518): evaluateTrafficStatsPolling
,V/        ( 2845): QcRouteController
,D/WifiNative-HAL( 3518): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3518): ConnectedState Enter  mScreenOn=false scanperiod=20000
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
,I/WifiStateMachine( 3518): REQUEST_POWER_SAVE_ON
,I/Hs20UtilService( 4115): Starting #12
,I/Hs20UtilService( 4115): Message received 5007
,V/        ( 2845): QcRouteController
,D/NearbySettings( 8850): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8850): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8850): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8850): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8850): MountReceiver.onReceive - Set preference state off
,V/        ( 2845): QcRouteController
,V/NearbySettings( 8850): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11479): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4115): Starting #13
,I/Hs20UtilService( 4115): Message received 5007
,D/NearbySettings( 8850): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8850): MountReceiver.onReceive - Keep current state
V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/WifiStateMachine( 3518): callSECApi what=220
D/WifiStateMachine( 3518): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11479): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3518): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3518): LTETest block dns file not exists
,D/ConnectivityService( 3518): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3518): updateNetworkInfo()
E/ConnectivityService( 3518): updateNetworkInfo()
D/ConnectivityService( 3518): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3518): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3518): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3518):    accepting network in place of null
,D/TelephonyNetworkFactory( 3972): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3518): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3518): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3518): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 3518): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 3518): MasterInitialState.processMessage what=3
D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 3518): Not allowed due to - mEnabled false
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3518): updateIfacesLocked()
V/NetworkStats( 3518): performPollLocked(flags=0x1)
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3518): UpdateStatsForKnox
I/System.out( 3518): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524290
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,V/NetworkStats( 3518): performPollLocked() took 3ms
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
V/NetworkStats( 3518): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
,D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
D/NtpTrustedTime( 3518): currentTimeMillis() cache hit
,D/PowerManagerService( 3518): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3518
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
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
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/System.out( 3518): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:41:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455021661279], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455021661262]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3518): Validated
D/ConnectivityService( 3518): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3518): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3518): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3518): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524290
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
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11848): 
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11848): 
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11848): 
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11848): 
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11848): 
,D/ConnectivityService( 3518): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3518): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3518): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
,D/SmartBondingService( 3518): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3518): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6243): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11988): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5362): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5362): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11965): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11965): sales region : global
I/PCWCLIENTTRACE_PushUtil(11965): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11965): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12045): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12045): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3518): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3518): mCursor = null
,I/FOTA_Client(12062): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12062): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12062): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12078): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 13:41:01 GMT+01:00 2016
,I/KLMS-2.4.521: (12078): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12078): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12078): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12078): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12078): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12078): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(12095): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12078): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12078): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12078): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12078): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12078): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12078): KLMSIntentService(): onDestroy()
,E/SPPClientService(12137): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11288): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11288): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11288): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11288): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11288): [OR] == isSIMCardReady false ==
,I/SA      (11288): [SCU] == networkStateCheck == true
,I/SA      (11288): [DM] getCountryCodeFromCSC : PL
I/SA      (11288): isChinaCountryCode : false
I/SA      (11288): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11288): [OR] == networkStateCheck true ==
I/SA      (11288): [OR] GetMyCountryZoneTask
I/SA      (11288): [OR] onReceive END
,I/SA      (11288): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5488): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11288): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11288): [SSP] query invoked
,I/SCloudBackupReceiver(12157): Other Intent
,I/SA      (11288): [TPMU] GetMccFromDB : null
I/SA      (11288): [SCU] getMccFromPreferece mcc = 260
I/SA      (11288): [TPM] isNoProxy(default) : true
,D/accuweather( 5215): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5215): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12173): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12173): premStatus:2
,I/KnoxUsageLogPro(12173): isEulaShown : false
I/KnoxUsageLogPro(12173): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12204): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12204): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12204): stopCheckCategoryVersion
,E/WifiStateMachine( 3518): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3518): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3518): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,D/SmartBondingService( 3518): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3518): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
D/SmartBondingService( 3518): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3518): route cmd failed: 
W/NetworkManagementService( 3518): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3518): '
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3518): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3518): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3518): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3518): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3518): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3518): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6758): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/QuickConnect(12288): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12288): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12288): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,D/RCPManagerService( 3518): exchangeData() failure , invalid userId
,I/iu.Environment( 6758): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6758): num queued entries: 0
I/iu.UploadsManager( 6758): num updated entries: 0
,I/iu.SyncManager( 6758): NEXT; no task
,D/WaitQueueForNetworkActivate(12360): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12360): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3518): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12360): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12360): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12360): exit::IDLE
D/InitializeManagerStateMachine(12360): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12360): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12360): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12360): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12360): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12360): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12360): entry::SUCCESS
D/hcjo    (12360): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12360): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12360): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12360): exit::SUCCESS
D/InitializeManagerStateMachine(12360): entry::IDLE
,I/SA      (11288): [RC New] Execute method=[GET] start
,I/SA      (11288): [RC New] Security=[true]
,I/System.out(11288): Thread-1560(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11288): Thread-1560(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11288): Thread-1560(ApacheHTTPLog):isShipBuild true
I/System.out(11288): Thread-1560(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3518): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (11288): [RC New] [v2liruge] api execute + 584
I/SA      (11288): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11288): AsyncTask #1 calls detatch()
,I/SA      (11288): [TPMU] getNetworkMcc : 
,I/SA      (11288): [SCU] saveMccToPreferece Start
I/SA      (11288): [SCU] RegionMCC : 260
I/SA      (11288): [SSP] query invoked
,I/SA      (11288): [TPMU] GetMccFromDB : null
I/SA      (11288): [SCU] getMccFromPreferece mcc = 260
I/SA      (11288): [SCU] saveMccToPreferece End
,I/SA      (11288): [RC New] executeRequest [v2liruge] end. 603
I/SA      (11288): [RC New] Execute end
I/SA      (11288): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11288): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12110): wlan0: sending IPv6 Router Solicitation
,E/Watchdog( 3518): !@Sync 7
,D/WearableService( 4617): callingUid 10014, callindPid: 4617
,D/ResourcesManager(11988): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11988): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11988): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11988): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11988): Conditions not met for autocaching.
I/MusicLeanback(11988): Stop autocaching.
,D/WearableClient(11988): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11988): WearableClientImpl.onPostInitHandler: done
D/WearableClient(11988): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11988): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11988): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11988): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/ActivityThread(11988): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@33936f9f that was originally bound here
E/ActivityThread(11988): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@33936f9f that was originally bound here
E/ActivityThread(11988): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11988): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11988): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11988): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11988): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11988): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11988): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11988): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11988): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11988): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11988): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11988): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11988): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11988): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11988): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11988): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11988): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11988): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11988): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11988): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11988): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11988): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11848): 
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11848): 
,I/jxcore-log(11848): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11848): 
,I/WifiStateMachine( 3518): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3518): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3518): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3518) eventTime = 223456
,D/PowerManagerService( 3518): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3518 (0x0)
D/PowerManagerService( 3518): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3518, ws=WorkSource{10060}) (elapsedTime=3478)
,I/jxcore-log(11848): Test app app.js loaded
I/jxcore-log(11848): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11848): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ce0d93 added. We now have 1 listener(s)
,I/jxcore-log(11848): BLE advertisement is supported
I/jxcore-log(11848): 
I/chromium(11848): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11848): --= Surplus to requirements =--
I/jxcore-log(11848): 
I/jxcore-log(11848): ****TEST TOOK:  ms ****
I/jxcore-log(11848): 
I/jxcore-log(11848): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11848): 
,D/AndroidRuntime(12455): 
D/AndroidRuntime(12455): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12455): CheckJNI is OFF
,D/AndroidRuntime(12455): readGMSProperty: start
D/AndroidRuntime(12455): readGMSProperty: already setted!!
,D/AndroidRuntime(12455): readGMSProperty: end
D/AndroidRuntime(12455): addProductProperty: start
,I/GAV4    (12220): Thread[GAThread,5,main]: No campaign data found.
,E/AffinityControl(12455): AffinityControl: registerfunction enter
,D/AndroidRuntime(12455): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3518): START PACKAGE DELETE: observer{838899963}
D/PackageManager( 3518): pkg{<packageName>}
D/PackageManager( 3518): user{0}
D/PackageManager( 3518): caller{2000}
D/PackageManager( 3518): flags{3}
D/PersonaManagerService( 3518): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3518): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3518): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3518): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3518): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3518): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3518): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3518): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3518): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3518): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3518): !@killApplicatoin: 10644, uninstall pkg
I/ActivityManager( 3518): Force stopping com.test.thalitest appid=10644 user=-1: uninstall pkg
I/ActivityManager( 3518): Killing 11848:com.test.thalitest/u0a644 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3518):   Force finishing activity ActivityRecord{d46d06d u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3518): mDVFSHelper.acquire()
,W/PackageSettings( 3518): Skipping PackageSetting{246cb596 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3518): Force stopping com.test.thalitest appid=10644 user=0: pkg removed
,E/JavaBinder( 3518): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3518):   Force finishing activity ActivityRecord{d46d06d u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3518): Duplicate finish request for ActivityRecord{d46d06d u0 com.test.thalitest/.MainActivity t26 f}
,E/JavaBinder( 3518): !!! FAILED BINDER TRANSACTION !!!
,I/art     ( 8989): Explicit concurrent mark sweep GC freed 30861(1709KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 348us total 24.012ms
I/art     ( 6758): Explicit concurrent mark sweep GC freed 26218(1507KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 587us total 25.994ms
I/art     ( 4053): Explicit concurrent mark sweep GC freed 33198(2036KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 387us total 18.496ms
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/WifiService( 3518): Client connection lost with reason: 4
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 12
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 12
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/LWLocationManager(11555): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11555): getLastUiLocationId() : mLastUiLocationId = -100
,I/InputReader( 3518): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/GeofencerStateMachine( 4617): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4510): mOCRHelper is null
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/ResourceType( 5362): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5362): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12468): MountEmulatedStorage()
E/Zygote  (12468): v2
I/libpersona(12468): KNOX_SDCARD checking this for 10063
I/libpersona(12468): KNOX_SDCARD not a persona
,I/ActivityManager( 3518): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12468 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/art     ( 3518): Suspending all threads took: 8.675ms
,D/TimaKeyStoreProvider(12468): TimaSignature is unavailable
,D/ActivityThread(12468): Added TimaKeyStore provider
,D/SecContentProvider2( 3518): uri = 14 selection = getSealedState
D/SecContentProvider2( 3518): mCursor = null
,I/art     ( 3518): Explicit concurrent mark sweep GC freed 54015(3MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 49MB/65MB, paused 10.859ms total 131.748ms
,D/ApplicationPolicy( 3518): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/ResourcesManager(11555): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 12
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager(12468): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6243): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6243): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6243): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager( 3518): post active user change for 0
D/KnoxTimeoutHandler( 3518): postActiveUserChange for user 0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3518): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/VRSetupWizardStub/PackageIntentReceiver(12468): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12468): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12468): packagename:com.test.thalitest
D/ResourcesManager(11555): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/PointerIcon( 3518): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3518): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3518): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3518): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6243): updateVisibility : ActivityRecord{1450f6b0 token=android.os.BinderProxy@27f9f3ad {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/KLMS-2.4.521: (12078): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 13:41:05 GMT+01:00 2016
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SecContentProvider2( 3518): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3518): mCursor = null
,I/KLMS-2.4.521: (12078): KLMSAbstractReciever(): onReceive().END.
,D/PackageManager( 3518): delete codoeFile: 
I/splitIntent( 3518): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3518): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager(11555): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/AASAUninstall( 3518):  com.test.thalitest not target!
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/PackageManager( 3518): result of delete: 1{838899963}
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/EnterpriseDeviceManagerService( 3518): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3518): Admin package name: com.google.android.gms
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12078): KLMSIntentService(): onCreate()
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Books/Books.apk
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/AndroidRuntime(12455): Shutting down VM
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (12078): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12078): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  (12487): MountEmulatedStorage()
E/Zygote  (12487): v2
I/libpersona(12487): KNOX_SDCARD checking this for 10106
I/libpersona(12487): KNOX_SDCARD not a persona
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.521: (12078): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SELinux (12487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3518): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12487 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(11555): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SELinux (12487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/KLMS-2.4.521: (12078): KLMSIntentService(): PACKAGE_REMOVED
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/SELinux (12487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RegisteredServicesCache( 3963): empty dynamic service
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/KLMS-2.4.521: (12078): KLMSIntentService(): listeningToPackageRemoved().START
,D/InputMethodManagerService( 3518): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.4.521: (12078): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11555): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/InputMethodManagerService( 3518): Got RemoteException sending setActive(false) notification to pid 11848 uid 10644
W/ContextImpl( 3518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider(12487): TimaSignature is unavailable
,D/ActivityThread(12487): Added TimaKeyStore provider
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/Timeline( 6243): Timeline: Activity_idle id: android.os.BinderProxy@27f9f3ad time:224345
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RCPManager(12173):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3518):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3518): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ActivityManager( 3518): mDVFSHelper.release()
I/Timeline( 3518): Timeline: Activity_windows_visible id: ActivityRecord{232c6bc7 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:224352
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12487): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/elm:14491(12487): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12487): ELMEngine.ELMEngine( context ).
D/elm:14491(12487): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  (12505): MountEmulatedStorage()
I/libpersona(12505): KNOX_SDCARD checking this for 10050
E/Zygote  (12505): v2
I/libpersona(12505): KNOX_SDCARD not a persona
,I/SELinux (12505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux (12505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/SELinux (12505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12505 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491(12487): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12487): ElmAgentService : onCreate()
,D/elm:14491(12487): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,I/KLMS-2.4.521: (12078): KLMSIntentService(): listeningToPackageRemoved().END
D/RCPManagerService( 3518): PackageReceiver onReceive()
I/HarmonyEASService( 3518): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3518): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3518): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3518): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3518): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3518): uID is 10644
V/EnterpriseBillingPolicy( 3518): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3518): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3518): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3518): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3518): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3518): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3518): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12487): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12487): MDMBridge.getInstance()
D/elm:14491(12487): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.4.521: (12078): KLMSIntentService(): onDestroy()
D/elm:14491(12487): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
D/TimaKeyStoreProvider(12505): TimaSignature is unavailable
D/ActivityThread(12505): Added TimaKeyStore provider
,W/ResourcesManager(11555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  (12521): MountEmulatedStorage()
E/Zygote  (12521): v2
I/libpersona(12521): KNOX_SDCARD checking this for 10183
I/libpersona(12521): KNOX_SDCARD not a persona
,I/SELinux (12521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SELinux (12521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12521 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/elm:14491(12487): ElmAgentService : onDestroy().
,D/KnoxTimeoutHandler( 3518): handleActiveUserChange for user 0
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 727us total 13.050ms
,D/SSRM:n  ( 3518): SIOP:: AP = 310, PST = 273, CUR = 62
,D/TimaKeyStoreProvider(12521): TimaSignature is unavailable
,D/ActivityThread(12521): Added TimaKeyStore provider
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(11555): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(12505): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 340us total 9.124ms
,W/ResourcesManager(12505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12505): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12505): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12505): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12505): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12505): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 248us total 7.950ms
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11555): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11555): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11555): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11555): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourceType( 3518): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (12537): MountEmulatedStorage()
E/Zygote  (12537): v2
I/libpersona(12537): KNOX_SDCARD checking this for 10101
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona(12537): KNOX_SDCARD not a persona
I/SELinux (12537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12537): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12537 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3518): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3518): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3518): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/TaskPersister( 3518): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3518): removeObsoleteFile: deleting file=24_task.xml
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12537): TimaSignature is unavailable
,D/ActivityThread(12537): Added TimaKeyStore provider
,D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/ResourcesManager(12521): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
I/libpersona(12552): KNOX_SDCARD checking this for 10019
E/Zygote  (12552): MountEmulatedStorage()
I/libpersona(12552): KNOX_SDCARD not a persona
E/Zygote  (12552): v2
D/PanelView( 3692): There is/are notification(s) 
I/SELinux (12552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,I/SELinux (12552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12552 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/ActivityManager( 3518): Killing 11588:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager(11555): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3518): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/ActivityManager( 3518): Killing 11555:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12552): TimaSignature is unavailable
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ActivityThread(12552): Added TimaKeyStore provider
,D/ResourcesManager(12537): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/SQLiteLog(12521): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/Zygote  (12569): MountEmulatedStorage()
E/Zygote  (12569): v2
I/libpersona(12569): KNOX_SDCARD checking this for 10190
I/libpersona(12569): KNOX_SDCARD not a persona
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux (12569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3518): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
E/SELinux (12569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12569 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3518): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3518): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3518): onPackageRemoved : com.test.thalitest
,I/ActivityManager( 3518): Killing 10874:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12569): TimaSignature is unavailable
,D/ActivityThread(12569): Added TimaKeyStore provider
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12552): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12552): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12552): onReceive() : package name is not s health. Return !!!
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/ActivityManager( 3518): Killing 11712:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/ResourcesManager(12569): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/DocsApplication(12537): Installing DEX configuration.
,E/JavaBinder( 3518): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 3518): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.locationwidget/com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider}
W/BroadcastQueue( 3518): android.os.TransactionTooLargeException
W/BroadcastQueue( 3518): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3518): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3518): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3518): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3518): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3518): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3518): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3518): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3518): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3518): findPreferredActivity: No PreferredActivities set
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12569): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12569): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(12569): Clear T&P info.
,E/Zygote  (12586): MountEmulatedStorage()
I/libpersona(12586): KNOX_SDCARD checking this for 10022
E/Zygote  (12586): v2
I/libpersona(12586): KNOX_SDCARD not a persona
,I/SELinux (12586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/TapandpayWidget:TanpandpayAppWidgetProvider(12569): Widget is not attached.
,E/SELinux (12586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3518): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12586 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/DexInstaller(12537): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12537): Provided clientMode=RELEASE, packageInfo=PackageInfo{3e91b28 com.google.android.apps.docs}
,D/TAG     (12537): onCreate()
,D/TimaKeyStoreProvider(12586): TimaSignature is unavailable
,I/ActivityManager( 3518): Killing 12326:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
D/ActivityThread(12586): Added TimaKeyStore provider
,D/CrossAppStateProvider(12537): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager(12586): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12586): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12586): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6758): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6758): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6758): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6758): Module APK com.google.android.play.games already loaded
,D/NearbySource(12505): Nearby Source Create!
,D/NearbyContext(12505): Nearby Context Create!
,D/ChimeraCfgMgr( 6758): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6758): Module APK com.google.android.play.games already loaded
,I/LocationWidgetApplication(12586): onCreate() : start
,D/LocationWidgetApplication(12586): countryCode = POLAND
,E/NetworkScheduler.SchedulerReceiver( 4617): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4617): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 6758): Removing dialog suppression flag for package com.test.thalitest
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12505): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12505): Samsung link source created
,D/gH_CompatibleDatabase( 6758): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6758): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6758): (10) POSIX Error : 9 SQLite Error : 3850
D/gH_CompatibleDatabase( 6758): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/AndroidRuntime( 6758): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6758): Process: com.google.android.gms, PID: 6758
E/AndroidRuntime( 6758): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6758): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6758): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6758): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6758): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LocationManagerService( 3518): getProviders()=[]
D/LocationManagerService( 3518): getProviders()=[passive]
D/LocationManagerService( 3518): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12586): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12586): getLastUiLocationId() : mLastUiLocationId = -100
,E/SQLiteLog(12586): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12586): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12586): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12586): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12586): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12586): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12586): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12586): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12586): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12586): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12586): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12586): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12586): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12586): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12586): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12586): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12586): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12586): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12586): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12586): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12586): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12586): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(12586): Shutting down VM
E/AndroidRuntime(12586): FATAL EXCEPTION: main
E/AndroidRuntime(12586): Process: com.sec.android.widgetapp.locationwidget, PID: 12586
E/AndroidRuntime(12586): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12586): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12586): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12586): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12586): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12586): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12586): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12586): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12586): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12586): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12586): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12586): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12586): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12586): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12586): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12586): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12586): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12586): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12586): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12586): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12586): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12586): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12586): 	... 9 more
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/SQLiteLog(12505): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
E/Zygote  (12610): MountEmulatedStorage()
E/Zygote  (12610): v2
I/libpersona(12610): KNOX_SDCARD checking this for 10031
I/libpersona(12610): KNOX_SDCARD not a persona
E/SQLiteDatabase(12505): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12505): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12505): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12505): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12505): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12505): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12505): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12505): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12505): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12505): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12505): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12505): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12505): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12505): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12505): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12505): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12505): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12505): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12505): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12505): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12505): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12505): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12505): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12505): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12505): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12505): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12505): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12505): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12505): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12505): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12505): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12505): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12505): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12505): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12505): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12505): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12505): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/SELinux (12610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3518): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12610 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/SQLiteOpenHelper(12505): Opened local.db in read-only mode
I/SELinux (12610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/SELinux (12610): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/SQLiteLog( 6758): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6758): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
V/ApplicationPolicy( 3518): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
E/ClearPendingStateOp( 6758): Runtime exception while performing operation
E/ClearPendingStateOp( 6758): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6758): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6758): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6758): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6758): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6758): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6758): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6758): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 6758): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6758): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6758): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6758): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6758): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6758): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6758): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6758): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6758): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6758): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6758): 	at java.lang.Thread.run(Thread.java:818)
I/PCWCLIENTTRACE_PushUtil(11965): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11965): sales region : global
I/PCWCLIENTTRACE_PushUtil(11965): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11965): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/SQLiteLog( 6758): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6758): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6758): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6758): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 6758): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6758): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6758): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6758): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6758): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6758): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityThread(11940): Failed to find provider info for com.facebook.appmanager.installrecord
E/SQLiteLog( 6758): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6758): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 6758): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SharedPreferencesImpl( 6758): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,D/TimaKeyStoreProvider(12610): TimaSignature is unavailable
D/ActivityThread(12610): Added TimaKeyStore provider
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/DropBoxManagerService( 3518): Can't write: system_app_wtf
E/DropBoxManagerService( 3518): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3518): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3518): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3518): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3518): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3518): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3518): 	... 5 more
E/DropBoxManagerService( 3518): Can't write: system_app_crash
E/DropBoxManagerService( 3518): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3518): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3518): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3518): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3518): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3518): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3518): 	... 5 more
E/DropBoxManagerService( 3518): Can't write: system_app_crash
E/DropBoxManagerService( 3518): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3518): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3518): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3518): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3518): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3518): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3518): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3518): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3518): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3518): 	... 5 more
E/Zygote  (12631): MountEmulatedStorage()
E/Zygote  (12631): v2
I/libpersona(12631): KNOX_SDCARD checking this for 10035
I/libpersona(12631): KNOX_SDCARD not a persona
I/SELinux (12631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3518): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12631 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (12631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 6758): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6758): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 6758): Sending signal. PID: 6758 SIG: 9
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3518): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3518): displayNotification : [0ah,00h,00h]
D/ResourcesManager(12610): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
I/Process (12586): Sending signal. PID: 12586 SIG: 9
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3518): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3518): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3518): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3518): displayNotification : [09h,00h,00h]
D/WifiDisplayAdapter( 3518): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/UsbHostManager( 3518): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3518): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3518): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/TimaKeyStoreProvider(12631): TimaSignature is unavailable
D/ActivityThread(12631): Added TimaKeyStore provider
,D/ContactProvider(12505): getAllContactInfoList Start
,E/SharedPreferencesImpl(12505): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12631): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/Zygote  (12654): MountEmulatedStorage()
E/Zygote  (12654): v2
I/libpersona(12654): KNOX_SDCARD checking this for 10052
I/libpersona(12654): KNOX_SDCARD not a persona
,I/SELinux (12654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12654): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3518): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12654 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/MtpClient(12505): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12505): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/ActivityManager( 3518): Killing 8850:com.android.settings/1000 (adj 13): bgCount ##31
,I/FeatureConfig(12631): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/UsbHostManager( 3518): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3518): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ConnectivityService( 3518): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@138a67e3)
,D/ConnectivityService( 3518): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager( 3518): Process com.google.android.gms (pid 6758)(adj 0) has died(288,1186)
E/ConnectivityService( 3518): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/EventHub( 3518): Removing device '/dev/input/event10' due to inotify event
,W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,D/ResourcesManager(12631): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
,D/TimaKeyStoreProvider(12654): TimaSignature is unavailable
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
,W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
,W/ResourcesManager(12631): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20998ms
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30997ms
D/ActivityThread(12654): Added TimaKeyStore provider
W/ActivityManager( 3518): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30995ms
,D/ResourcesManager(12631): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiService( 3518): Client connection lost with reason: 4
,D/ResourcesManager(12631): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/ActivityManager( 3518): Process com.sec.android.widgetapp.locationwidget (pid 12586)(adj 9) has died(284,1186)
,I/EventHub( 3518): Removing device '/dev/input/event7' due to inotify event
,W/ResourcesManager(12631): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12631): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/EventHub( 3518): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(12631): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/EventHub( 3518): Removing device '/dev/input/event9' due to inotify event
,W/ResourcesManager(12631): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12631): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3518): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12654): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/EventHub( 3518): Removing device '/dev/input/event11' due to inotify event
,W/ResourcesManager(12654): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,E/Zygote  (12675): MountEmulatedStorage()
I/libpersona(12675): KNOX_SDCARD checking this for 10036
E/Zygote  (12675): v2
I/libpersona(12675): KNOX_SDCARD not a persona
I/SELinux (12675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/PackageManager( 3518): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/AndroidRuntime( 3518): *** FATAL EXCEPTION IN SYSTEM PROCESS: PackageManager
E/AndroidRuntime( 3518): java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
E/AndroidRuntime( 3518): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1463)
E/AndroidRuntime( 3518): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1610)
E/AndroidRuntime( 3518): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:1157)
E/AndroidRuntime( 3518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3518): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 3518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3518): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/SELinux (12675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027,
,E/SELinux (12675): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/EventHub( 3518): Removing device '/dev/input/event12' due to inotify event,
D/ResourcesManager(12631): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/ActivityManager( 3518): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12675 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/EventHub( 3518): Removing device '/dev/input/event13' due to inotify event
,W/ResourcesManager(12654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12654): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12654): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12654): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12654): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/EventHub( 3518): Removing device '/dev/input/event14' due to inotify event
,W/ResourcesManager(12631): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12675): TimaSignature is unavailable
,D/ActivityThread(12675): Added TimaKeyStore provider
,D/ResourcesManager(12631): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ContactProvider(12505): getAllContactInfoList End
,I/syncContacts(12505): thread: 1763, sync time = 542
,D/BatteryService( 3518): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3518): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3518): online:4, current avg:-300, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3518): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3518): stay LED for fully charged
,W/ResourcesManager(12631): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12631): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
