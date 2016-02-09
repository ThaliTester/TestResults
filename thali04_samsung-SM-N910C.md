#### Test 587523534d3a10e_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
D/SSRM:n  ( 3495): SIOP:: AP = 260, PST = 275, CUR = 70
--------- beginning of main
D/AndroidRuntime(12031): 
D/AndroidRuntime(12031): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12031): CheckJNI is OFF
D/AndroidRuntime(12031): readGMSProperty: start
D/AndroidRuntime(12031): readGMSProperty: already setted!!
D/AndroidRuntime(12031): readGMSProperty: end
D/AndroidRuntime(12031): addProductProperty: start
D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3495): online:4, current avg:68, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
D/BatteryService( 3495): stay LED for fully charged
D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3495): Plugged
I/MotionRecognitionService( 3495): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5627): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/AffinityControl(12031): AffinityControl: registerfunction enter
D/AndroidRuntime(12031): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3495): inState():  stateMachine is null !!
I/PersonaManagerService( 3495): PersonaId don't exist
I/ActivityManager( 3495): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3495): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3495): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3495): mDVFSHelper.acquire()
D/FocusedStackFrame( 3495): Set to : 0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (12054): MountEmulatedStorage()
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD checking this for 10647
I/libpersona(12054): KNOX_SDCARD not a persona
I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3495): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=12054 uid=10647 gids={50647, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12054): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(12031): Shutting down VM
D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
D/ActivityThread(12054): Added TimaKeyStore provider
V/WindowOrientationListener( 3495): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3495): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3495): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3495): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3495): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager( 3495): Display changed displayId=0
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{16dfcf41 token=android.os.BinderProxy@2257588 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
D/ResourcesManager(12054): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/WebViewFactory(12054): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12054): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12054): Loading: webviewchromium
I/LibraryLoader(12054): Time to load native libraries: 6 ms (timestamps 5349-5355)
I/LibraryLoader(12054): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12054): Binding Chromium to main looper Looper (main, tid 1) {3d312f9}
I/LibraryLoader(12054): Expected native library version number "",actual native library version number ""
I/chromium(12054): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(12054): Initializing chromium process, renderers=0
W/art     (12054): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(12054): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(12054): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(12054): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(12054): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(12054): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (12054): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(12054): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(12054): CordovaWebView is running on device made by: samsung
W/art     (12054): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (12054): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(12054): performCreate Call secproduct feature valuefalse
D/Activity(12054): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(12054): Render dirty regions requested: true
D/ActivityManager( 3495): post active user change for 0
D/KnoxTimeoutHandler( 3495): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3495): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3495): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3495): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(12054): Initialized EGL, version 1.4
I/OpenGLRenderer(12054): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1280937712 
D/OpenGLRenderer(12054): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(12054): Enabling debug mode 0
D/mali_winsys(12054): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(12054): updateVisibility : ActivityRecord{d21ac69 token=android.os.BinderProxy@39b46854 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3495): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3495): mDVFSHelper.release()
I/Timeline( 3495): Timeline: Activity_windows_visible id: ActivityRecord{3fe1a7b8 u0 com.test.thalitest/.MainActivity t25} time:205808
W/IInputConnectionWrapper(12054): showStatusIcon on inactive InputConnection
I/Timeline(12054): Timeline: Activity_idle id: android.os.BinderProxy@39b46854 time:205814
I/chromium(12054): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(12054): 
D/JsMessageQueue(12054): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(12054): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358529280
I/chromium(12054): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(12054): Initializing JXcore engine
W/jxcore-log(12054): JXcore engine is ready
,E/auditd  ( 4628): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3495): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3495): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(12054): Starting JXcore engine
,W/jxcore-log(12054): Platform android
W/jxcore-log(12054): 
W/jxcore-log(12054): Process ARCH arm
W/jxcore-log(12054): 
,W/ContextImpl( 3495): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(12054): JXcore Cordova bridge is ready!
I/jxcore-log(12054): 
W/jxcore-log(12054): JXcore engine is started
,I/jxcore-log(12054): Toggling radios to true
I/jxcore-log(12054): 
,D/BluetoothAdapter(12054): enable()
,D/BluetoothAdapter(12054): enable(): BT is already enabled..!
,D/WifiService( 3495): New client listening to asynchronous messages
,I/WifiManager(12054): packageName : com.test.thalitest
,D/SecContentProvider( 3495): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3495): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3495): mCursor = null
,D/WifiService( 3495): setWifiEnabled: true pid=12054, uid=10647
E/WifiService( 3495): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3495): Permission Denial: getCurrentUser() from pid=12054, uid=10647 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3495): Failed getting userId using ActivityManagerNative
W/WifiService( 3495): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=12054, uid=10647 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3495): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3495): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3495): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3495): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3495): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3495): name = wifi_on
,I/WifiService( 3495): disconnect: pid=12054, uid=10647
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3495): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): Disconnected - do not scan
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log(12054): Radios toggled
I/jxcore-log(12054): 
E/WifiStateMachine( 3495): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3495): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3495): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(12054): My device name is: samsung-SM-N910C
I/jxcore-log(12054): 
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3495): do suspend true
,D/WifiP2pService( 3495): InactiveState{ what=143375 }
,D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3495): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3495): updateNetworkInfo()
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3495): updateNetworkInfo()
,D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/Hs20UtilService( 4113): Starting #8
I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8779): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8779): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine( 3495): Start Disconnecting Watchdog 1
E/WifiStateMachine( 3495): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3495): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3495): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3495): do suspend true
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiP2pService( 3495): InactiveState{ what=143375 }
D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
,D/WifiService( 3495): New client listening to asynchronous messages
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11539): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3495): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
E/WifiStateMachine( 3495): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/EntConnectivity( 3495): Not allowed due to - mEnabled false
D/ConnectivityService( 3495): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker( 3495): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3495): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 6942): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 3978): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine( 3495): updateConfiguredNetworkExpiration - currTime: 1455029566047
D/WifiStateMachine( 3495): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/EntConnectivity( 3495): Not allowed due to - mEnabled false
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
D/ConnectivityService( 3495): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3833): First Scan Start
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3495): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3495): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3495): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3495): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/Tethering( 3495): MasterInitialState.processMessage what=3
D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/SmartBondingService( 3495): getSBEnabled() enabled =false
V/NetworkStats( 3495): updateIfacesLocked()
V/NetworkStats( 3495): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3495): UpdateStatsForKnox
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): performPollLocked() took 3ms
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
I/Hs20UtilService( 4113): Starting #9
I/Hs20UtilService( 4113): Message received 5007
,D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11539): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3978): FileWriteThread : threadType = 3
,D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3495): updateDataUsageMap
,I/ApplicationPolicy( 3495): updateDataUsageMap  idList is null 
D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/GpsLocationProvider( 3495): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3495): No Active Data Connection
,I/DBG_DM  ( 6279): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6279): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12145): MountEmulatedStorage()
E/Zygote  (12145): v2
I/libpersona(12145): KNOX_SDCARD checking this for 1000
I/libpersona(12145): KNOX_SDCARD not a persona
,I/SELinux (12145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12145): TimaSignature is unavailable
,D/ActivityThread(12145): Added TimaKeyStore provider
,D/ResourcesManager(12145): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12145): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12145): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12145): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12145): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12145): sales region : global
I/PCWCLIENTTRACE_PushUtil(12145): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12145): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12145): noConnectivity : true
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12161): MountEmulatedStorage()
E/Zygote  (12161): v2
I/libpersona(12161): KNOX_SDCARD checking this for 10135
I/libpersona(12161): KNOX_SDCARD not a persona
,I/SELinux (12161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12161): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12161 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11315:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12161): TimaSignature is unavailable
,D/ActivityThread(12161): Added TimaKeyStore provider
,D/ResourcesManager(12161): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(12161): Database version: 104
,D/ResourcesManager(12161): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12161): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12161): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12161): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d1aa5bd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12161): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12161): GMSCore installation verified
,I/ConfigStore(12161): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12161): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12161): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12161): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3495): getStreamVolume 3 index 0
,I/MediaRouter(12161): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12186): MountEmulatedStorage()
E/Zygote  (12186): v2
I/libpersona(12186): KNOX_SDCARD checking this for 10002
I/libpersona(12186): KNOX_SDCARD not a persona
,I/SELinux (12186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12186): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12186 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(12161): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3495): Killing 11360:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12186): TimaSignature is unavailable
,D/ActivityThread(12186): Added TimaKeyStore provider
,D/ResourcesManager(12186): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3495): Killing 11338:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12205): MountEmulatedStorage()
I/libpersona(12205): KNOX_SDCARD checking this for 1000
E/Zygote  (12205): v2
I/libpersona(12205): KNOX_SDCARD not a persona
I/SELinux (12205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12205 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12205): TimaSignature is unavailable
,D/ActivityThread(12205): Added TimaKeyStore provider
,D/ResourcesManager(12205): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 75206(4MB) AllocSpace objects, 34(544KB) LOS objects, 24% free, 49MB/65MB, paused 1.379ms total 86.533ms
,I/DIAGMON_AGENT(12205): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12205): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12205): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12205): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12205): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12222): MountEmulatedStorage()
E/Zygote  (12222): v2
I/libpersona(12222): KNOX_SDCARD checking this for 10012
I/libpersona(12222): KNOX_SDCARD not a persona
,I/SELinux (12222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12222): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12222 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3833): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 3833): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3833): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3833): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3495): [1,455,029,567,134 ms] noteScanEnd no scan source
,D/TimaKeyStoreProvider(12222): TimaSignature is unavailable
,D/ActivityThread(12222): Added TimaKeyStore provider
,E/WifiStateMachine( 3495): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@71e0f81 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3495): setDetailed state send new extra info
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,D/ResourcesManager(12222): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3495): Killing 11408:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/FOTA_Client(12222): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12222): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12222): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12238): MountEmulatedStorage()
E/Zygote  (12238): v2
I/libpersona(12238): KNOX_SDCARD checking this for 10021
I/libpersona(12238): KNOX_SDCARD not a persona
,I/SELinux (12238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12238 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11427:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 512us total 13.055ms
,I/wpa_supplicant( 3833): Associated with C0.AA.48
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3495): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
D/TimaKeyStoreProvider(12238): TimaSignature is unavailable
,D/ActivityThread(12238): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 456us total 8.579ms
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 514us total 8.718ms
,D/ResourcesManager(12238): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12238): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:52:47 GMT+01:00 2016
,I/KLMS-2.4.521: (12238): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12238): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12238): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12238): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12238): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12238): StateImplV2(): networkChangeListener().END
,E/Zygote  (12254): MountEmulatedStorage()
E/Zygote  (12254): v2
I/libpersona(12254): KNOX_SDCARD checking this for 10038
I/libpersona(12254): KNOX_SDCARD not a persona
,I/SELinux (12254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12254 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (12254): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onDestroy()
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/ActivityManager( 3495): Killing 11393:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
E/WifiStateMachine( 3495): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3495): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3495): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3833): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3833): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3833): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3833): Blacklist: Clear (temp) 
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/TimaKeyStoreProvider(12254): TimaSignature is unavailable
,D/ActivityThread(12254): Added TimaKeyStore provider
,E/WifiStateMachine( 3495): Network connection established
,D/WifiNative-HAL( 3495): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3495): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3495): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3495): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3495): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3495): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3495): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3495): updateNetworkInfo()
D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/ResourcesManager(12254): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/WifiStateMachine( 3495): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3495): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3495): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3495): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SO_AGENT(12254): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3495): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
,E/Zygote  (12270): MountEmulatedStorage()
I/libpersona(12270): KNOX_SDCARD checking this for 1000
E/Zygote  (12270): v2
I/libpersona(12270): KNOX_SDCARD not a persona
,I/SELinux (12270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12270): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12270 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11443:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider(12270): TimaSignature is unavailable
,D/ActivityThread(12270): Added TimaKeyStore provider
,D/ResourcesManager(12270): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12290): MountEmulatedStorage()
,E/Zygote  (12290): v2
I/libpersona(12290): KNOX_SDCARD checking this for 10039
I/libpersona(12290): KNOX_SDCARD not a persona
I/SELinux (12290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12290 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12290): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Killing 11454:com.samsung.helphub/1000 (adj 13): bgCount ##31
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3495): do suspend false
,D/TimaKeyStoreProvider(12290): TimaSignature is unavailable
,D/ActivityThread(12290): Added TimaKeyStore provider
,D/SecContentProvider2( 3495): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3495): mCursor = null
D/WifiP2pService( 3495): InactiveState{ what=143375 }
,D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
,D/ResourcesManager(12290): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12290): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12290): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12290): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12290): PushLog.txt file is not deleted.
D/SPPClientService(12290): PushLog.txt file is not deleted.
D/SPPClientService(12290): ============PushLog. stop!
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12307): MountEmulatedStorage()
I/libpersona(12307): KNOX_SDCARD checking this for 10045
E/Zygote  (12307): v2
I/libpersona(12307): KNOX_SDCARD not a persona
,I/SELinux (12307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12307): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12307 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SPPClientService(12290): [[SystemStateMonitorService]] No Active Internet
,I/ActivityManager( 3495): Killing 11489:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12307): TimaSignature is unavailable
,D/ActivityThread(12307): Added TimaKeyStore provider
,D/ResourcesManager(12307): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12307): [SSP] onCreated
,I/SA      (12307): [TPM] There is no property file
,I/SA      (12307): [SCU] isHaveSA() - false
,I/SA      (12307): [TPM] getModelProperty : null
I/SA      (12307): [TPM] getCSCProperty : null
,I/SA      (12307): [DM] init START
,I/SA      (12307): [DM] This device is not a Vodafone
,I/SA      (12307): checkReactivationActive for LOLLIPOP
,I/SA      (12307): checkReactivationActive for reactiveActive
I/SA      (12307): setSupportRL : true
,I/SA      (12307): [SCU] isHaveSA() - false
I/SA      (12307): support phone number id : false
,I/SA      (12307): [DM] init END
I/SA      (12307): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12307): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12307): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (12307): [SLFUCHKMGR] constructor called
,I/SA      (12307): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12307): [OR] == isSIMCardReady false ==
,I/SA      (12307): [SCU] == networkStateCheck == false
I/SA      (12307): [OR] onReceive END
,I/ActivityManager( 3495): Killing 11562:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,V/DownloadManager( 5721): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12328): MountEmulatedStorage()
E/Zygote  (12328): v2
I/libpersona(12328): KNOX_SDCARD checking this for 10067
I/libpersona(12328): KNOX_SDCARD not a persona
,I/SELinux (12328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12328): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12328 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12328): TimaSignature is unavailable
,D/ActivityThread(12328): Added TimaKeyStore provider
,D/ResourcesManager(12328): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12328): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12328): Other Intent
,I/ActivityManager( 3495): Killing 11579:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/accuweather( 5361): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/dhcpcd  (12344): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12344): version 5.5.6 starting
,E/dhcpcd  (12344): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5361): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5361): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5361): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5361): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5361): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5361): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12352): MountEmulatedStorage()
I/libpersona(12352): KNOX_SDCARD checking this for 1000
E/Zygote  (12352): v2
I/libpersona(12352): KNOX_SDCARD not a persona
,I/SELinux (12352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/dhcpcd  (12344): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12344): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12344): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  (12344): bssid match
I/dhcpcd  (12344): wlan0: rebinding lease of 192.168.1.124
I/SELinux (12352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12352 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12352): TimaSignature is unavailable
,D/ActivityThread(12352): Added TimaKeyStore provider
,D/ResourcesManager(12352): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12352): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12352): premStatus:2
,I/KnoxUsageLogPro(12352): isEulaShown : false
I/KnoxUsageLogPro(12352): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12367): MountEmulatedStorage()
I/libpersona(12367): KNOX_SDCARD checking this for 10090
E/Zygote  (12367): v2
I/libpersona(12367): KNOX_SDCARD not a persona
,I/SELinux (12367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12367): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12367 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11597:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12367): TimaSignature is unavailable
D/ActivityThread(12367): Added TimaKeyStore provider
D/ResourcesManager(12367): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (12383): MountEmulatedStorage()
I/libpersona(12383): KNOX_SDCARD checking this for 10127
E/Zygote  (12383): v2
I/libpersona(12383): KNOX_SDCARD not a persona
I/SELinux (12383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12383 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11613:com.facebook.system/u0a10 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12383): TimaSignature is unavailable
D/ActivityThread(12383): Added TimaKeyStore provider
D/ResourcesManager(12383): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
D/KeyguardWallpaperUpdator(12383): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12383): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12383): stopCheckCategoryVersion
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (12399): MountEmulatedStorage()
I/libpersona(12399): KNOX_SDCARD checking this for 10136
E/Zygote  (12399): v2
I/libpersona(12399): KNOX_SDCARD not a persona
I/SELinux (12399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12399): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12399 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11722:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12399): TimaSignature is unavailable
D/ActivityThread(12399): Added TimaKeyStore provider
D/ResourcesManager(12399): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12399): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12399): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12399): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12399): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
I/WebViewFactory(12399): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12399): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(12399): Loading: webviewchromium
I/LibraryLoader(12399): Time to load native libraries: 2 ms (timestamps 9310-9312)
I/LibraryLoader(12399): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(12399): Binding Chromium to main looper Looper (main, tid 1) {35d0e0b9}
I/LibraryLoader(12399): Expected native library version number "",actual native library version number ""
I/chromium(12399): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(12399): Initializing chromium process, renderers=0
W/art     (12399): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(12399): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(12399): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12399): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12399): Requires BLUETOOTH permission
I/NSApplication(12399): Starting up...
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (12466): MountEmulatedStorage()
E/Zygote  (12466): v2
I/libpersona(12466): KNOX_SDCARD checking this for 10147
I/libpersona(12466): KNOX_SDCARD not a persona
I/SELinux (12466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12466): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=12466 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11759:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
E/lowmemorykiller( 2828): Error writing /proc/11759/oom_score_adj; errno=22
D/TimaKeyStoreProvider(12466): TimaSignature is unavailable
D/ActivityThread(12466): Added TimaKeyStore provider
D/ResourcesManager(12466): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/ResourcesManager(12466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/GLSActivity( 4671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 4671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Zygote  (12494): MountEmulatedStorage()
I/libpersona(12494): KNOX_SDCARD checking this for 10150
E/Zygote  (12494): v2
I/libpersona(12494): KNOX_SDCARD not a persona
I/SELinux (12494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3495): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12494 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12494): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 281us total 10.810ms
D/TimaKeyStoreProvider(12494): TimaSignature is unavailable
D/ActivityThread(12494): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 304us total 8.107ms
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 431us total 7.820ms
D/ResourcesManager(12494): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
W/ResourcesManager(12494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12494): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12494): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/QuickConnect(12494): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect(12494): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12494): PeriphStartReceiver.onReceive - no need to start
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (12512): MountEmulatedStorage()
E/Zygote  (12512): v2
I/libpersona(12512): KNOX_SDCARD checking this for 10178
I/libpersona(12512): KNOX_SDCARD not a persona
I/SELinux (12512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3495): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12512 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux (12512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Killing 11779:com.android.calendar/u0a164 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12512): TimaSignature is unavailable
D/ActivityThread(12512): Added TimaKeyStore provider
D/ResourcesManager(12512): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager(12512): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12512): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12512): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12512): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12512): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
E/Zygote  (12538): MountEmulatedStorage()
I/libpersona(12538): KNOX_SDCARD checking this for 10082
E/Zygote  (12538): v2
I/libpersona(12538): KNOX_SDCARD not a persona
I/SELinux (12538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12538): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12538 uid=10082 gids={50082, 9997} abi=armeabi-v7a
D/TimaKeyStoreProvider(12538): TimaSignature is unavailable
D/ActivityThread(12538): Added TimaKeyStore provider
D/RCPManagerService( 3495): exchangeData() failure , invalid userId
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/Zygote  (12554): MountEmulatedStorage()
I/libpersona(12554): KNOX_SDCARD checking this for 1000
E/Zygote  (12554): v2
I/libpersona(12554): KNOX_SDCARD not a persona
I/SELinux (12554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3495): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12554 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3495): Killing 11740:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
I/ActivityManager( 3495): Killing 10262:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(12554): TimaSignature is unavailable
D/ActivityThread(12554): Added TimaKeyStore provider
D/ResourcesManager(12538): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/BadgeProvider(12538): onCreate
D/BadgeProvider(12538): DatabaseHelper
D/ResourcesManager(12554): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
D/BadgeProvider(12538): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/ActivityManager( 3495): Killing 10954:com.android.mms/u0a52 (adj 13): bgCount ##31
D/BadgeProvider(12538): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12538): sendNotify, [notify] : null
D/BadgeProvider(12538): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12538): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12538): update, [UpdateCount] : 1
D/Launcher.Model( 4000): reloadBadges entered.
,W/ActivityManager( 3495): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 6942): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 6942): num queued entries: 0
I/iu.UploadsManager( 6942): num updated entries: 0
I/iu.SyncManager( 6942): NEXT; no task
D/CountryDetector( 3495): No listener is left
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12572): MountEmulatedStorage()
I/libpersona(12572): KNOX_SDCARD checking this for 10013
E/Zygote  (12572): v2
I/libpersona(12572): KNOX_SDCARD not a persona
,I/SELinux (12572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12572): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12572 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12572): TimaSignature is unavailable
,D/ActivityThread(12572): Added TimaKeyStore provider
,D/ResourcesManager(12572): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 31364(1863KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 1.306ms total 81.480ms
,I/ActivityManager( 3495): Killing 11833:com.sec.android.widgetapp.digitalclock/u0a97 (adj 13): bgCount ##31
,I/Hs20UtilService( 4113): Starting #10
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11539): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12344): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12344): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(12054): 
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3495): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3495): do suspend true
,D/WifiP2pService( 3495): InactiveState{ what=143375 }
D/WifiP2pService( 3495): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3495): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3495): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3495): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3495): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3495): Not connected state, yet.
E/WifiStateMachine( 3495): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3495): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3495): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3495): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3495): callSECApiInt - ID [210]
E/WifiStateMachine( 3495): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3495): updateNetworkInfo()
,D/ConnectivityService( 3495): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine( 3495): updateDnsLinkProperty: enter
D/ConnectivityService( 3495): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine.DnsPinger( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3495): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
I/Hs20UtilService( 4113): Starting #11
I/Hs20UtilService( 4113): Message received 5007
D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3495): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3495): Now, connected state.
E/WifiStateMachine( 3495): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3495): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/NearbySettings( 8779): MountReceiver.onReceive - Keep current state
I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
D/ConnectivityService( 3495): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/ConnectivityService( 3495): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 3495): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/WifiStateMachine( 3495): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 3495): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3495): callSECApiVoid - ID [212]
E/ConnectivityService( 3495): Unexpected mtu value: 0, wlan0
V/        ( 2845): QcRouteController
E/WifiStateMachine( 3495): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiStateMachine( 3495): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3495): route cmd failed: 
W/NetworkManagementService( 3495): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '71 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 71 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3495): '
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3495): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3495): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3495): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3495): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3495): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3495): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
I/SignOutReceiver(11539): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 4113): Starting #12
I/Hs20UtilService( 4113): Message received 5007
D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/        ( 2845): QcRouteController
V/NearbySettings( 8779): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8779): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8779): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8779): MountReceiver.mPrefHandler - 7002
V/        ( 2845): QcRouteController
I/SignOutReceiver(11539): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
I/Hs20UtilService( 4113): Starting #13
,I/Hs20UtilService( 4113): Message received 5007
,D/NearbySettings( 8779): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8779): MountReceiver.onReceive - Keep current state
,V/        ( 2845): QcRouteController
,I/WifiStateMachine( 3495): callSECApi what=220
D/WifiStateMachine( 3495): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService( 3495): Setting Dns servers for network 503 to [/192.168.1.1]
,I/SignOutReceiver(11539): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3495): LTETest block dns file not exists
,E/ConnectivityService( 3495): updateNetworkInfo()
D/ConnectivityService( 3495): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3495): updateNetworkInfo()
D/ConnectivityService( 3495): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3495): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Connected
D/ConnectivityService( 3495): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3495):    accepting network in place of null
,D/TelephonyNetworkFactory( 3978): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3495): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3495): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3495): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3495): MasterInitialState.processMessage what=3
D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/EntConnectivity( 3495): Not allowed due to - mEnabled false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): updateIfacesLocked()
V/NetworkStats( 3495): performPollLocked(flags=0x1)
,D/ConnectivityService( 3495): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/NetworkStatsFactory( 3495): UpdateStatsForKnox
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6942): CM callback handler got msg 524290
,D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): performPollLocked() took 2ms
I/System.out( 3495): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
V/NetworkStats( 3495): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
D/NtpTrustedTime( 3495): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3495): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3495
,D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/System.out( 3495): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:52:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455029569265], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455029569244]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3495): Validated
,D/ConnectivityService( 3495): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3495): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3495): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3495): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6942): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(12054): 
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(12054): 
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(12054): 
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(12054): 
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(12054): 
,D/ConnectivityService( 3495): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3495): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3495): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3495): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3495): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
D/SmartBondingService( 3495): getSBEnabled() enabled =false
,D/SmartBondingService( 3495): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3495): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6279): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6279): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(12161): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5221): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5221): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(12145): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12145): sales region : global
I/PCWCLIENTTRACE_PushUtil(12145): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12145): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12205): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12205): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3495): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3495): mCursor = null
,I/FOTA_Client(12222): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12222): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12222): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12238): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:52:49 GMT+01:00 2016
,I/KLMS-2.4.521: (12238): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12238): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12238): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SO_AGENT(12254): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12238): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12238): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12238): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12238): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12238): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12238): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onDestroy()
,E/SPPClientService(12290): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12307): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (12307): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12307): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12307): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12307): [OR] == isSIMCardReady false ==
,I/SA      (12307): [SCU] == networkStateCheck == true
I/SA      (12307): [DM] getCountryCodeFromCSC : PL
I/SA      (12307): isChinaCountryCode : false
I/SA      (12307): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12307): [OR] == networkStateCheck true ==
,I/SA      (12307): [OR] GetMyCountryZoneTask
I/SA      (12307): [OR] onReceive END
,I/SA      (12307): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5721): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12307): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12307): [SSP] query invoked
,I/SCloudBackupReceiver(12328): Other Intent
,I/SA      (12307): [TPMU] GetMccFromDB : null
I/SA      (12307): [SCU] getMccFromPreferece mcc = 260
I/SA      (12307): [TPM] isNoProxy(default) : true
,D/accuweather( 5361): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5361): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5361): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5361): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5361): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5361): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5361): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12352): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12352): premStatus:2
,I/KnoxUsageLogPro(12352): isEulaShown : false
I/KnoxUsageLogPro(12352): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12383): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12383): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12383): stopCheckCategoryVersion
,D/QuickConnect(12494): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12494): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12494): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,D/RCPManagerService( 3495): exchangeData() failure , invalid userId
,I/iu.Environment( 6942): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6942): num queued entries: 0
,I/iu.UploadsManager( 6942): num updated entries: 0
I/iu.SyncManager( 6942): NEXT; no task
,D/WaitQueueForNetworkActivate(12572): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12572): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3495): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12572): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12572): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12572): exit::IDLE
D/InitializeManagerStateMachine(12572): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12572): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12572): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12572): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12572): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12572): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12572): entry::SUCCESS
D/hcjo    (12572): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12572): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12572): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12572): exit::SUCCESS
D/InitializeManagerStateMachine(12572): entry::IDLE
,I/SA      (12307): [RC New] Execute method=[GET] start
,I/SA      (12307): [RC New] Security=[true]
,I/System.out(12307): Thread-1735(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12307): Thread-1735(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12307): Thread-1735(ApacheHTTPLog):isShipBuild true
I/System.out(12307): Thread-1735(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3495): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (12307): [RC New] [v2liruge] api execute + 554
I/SA      (12307): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12307): AsyncTask #1 calls detatch()
,I/SA      (12307): [TPMU] getNetworkMcc : 
,I/SA      (12307): [SCU] saveMccToPreferece Start
I/SA      (12307): [SCU] RegionMCC : 260
I/SA      (12307): [SSP] query invoked
,I/SA      (12307): [TPMU] GetMccFromDB : null
I/SA      (12307): [SCU] getMccFromPreferece mcc = 260
I/SA      (12307): [SCU] saveMccToPreferece End
,I/SA      (12307): [RC New] executeRequest [v2liruge] end. 574
I/SA      (12307): [RC New] Execute end
I/SA      (12307): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12307): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12344): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4671): callingUid 10014, callindPid: 4671
,D/ResourcesManager(12161): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12161): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12161): Conditions not met for autocaching.
I/MusicLeanback(12161): Stop autocaching.
,D/WearableClient(12161): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12161): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12161): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12161): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12161): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12161): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12161): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@4627935 that was originally bound here
E/ActivityThread(12161): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@4627935 that was originally bound here
E/ActivityThread(12161): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12161): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12161): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12161): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12161): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12161): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12161): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12161): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12161): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12161): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12161): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12161): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12161): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12161): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12161): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12161): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12161): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12161): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12161): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12161): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12161): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12161): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12161): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12161): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12161): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(12054): 
,I/WifiStateMachine( 3495): REQUEST_POWER_SAVE_ON
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(12054): 
,I/jxcore-log(12054): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(12054): 
,E/WifiStateMachine( 3495): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (-2/9)
D/PowerManagerService( 3495): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3495) eventTime = 213944
D/PowerManagerService( 3495): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3495 (0x0)
D/PowerManagerService( 3495): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3495, ws=WorkSource{10060}) (elapsedTime=3466)
,I/ClearcutLoggerApiImpl( 4671): disconnect managed GoogleApiClient
,I/jxcore-log(12054): Test app app.js loaded
I/jxcore-log(12054): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12054): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23012249 added. We now have 1 listener(s)
,I/jxcore-log(12054): BLE advertisement is supported
I/jxcore-log(12054): 
,I/chromium(12054): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(12054): --= Surplus to requirements =--
I/jxcore-log(12054): 
I/jxcore-log(12054): ****TEST TOOK:  ms ****
I/jxcore-log(12054): 
I/jxcore-log(12054): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(12054): 
,I/GAV4    (12399): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12670): 
D/AndroidRuntime(12670): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12670): CheckJNI is OFF
D/AndroidRuntime(12670): readGMSProperty: start
D/AndroidRuntime(12670): readGMSProperty: already setted!!
,D/AndroidRuntime(12670): readGMSProperty: end
D/AndroidRuntime(12670): addProductProperty: start
,D/SSRM:n  ( 3495): SIOP:: AP = 300, PST = 275, CUR = 68
,I/GAV2    (12466): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3495): Killing 11848:com.sec.android.app.camera/u0a168 (adj 15): bgCount ##31
,E/AffinityControl(12670): AffinityControl: registerfunction enter
,D/AndroidRuntime(12670): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3495): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3495): START PACKAGE DELETE: observer{826103043}
D/PackageManager( 3495): pkg{<packageName>}
D/PackageManager( 3495): user{0}
D/PackageManager( 3495): caller{2000}
D/PackageManager( 3495): flags{3}
D/PersonaManagerService( 3495): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3495): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3495): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3495): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3495): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3495): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3495): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3495): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3495): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3495): !@killApplicatoin: 10647, uninstall pkg
,I/ActivityManager( 3495): Force stopping com.test.thalitest appid=10647 user=-1: uninstall pkg
,I/ActivityManager( 3495): Killing 12054:com.test.thalitest/u0a647 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3495):   Force finishing activity ActivityRecord{3fe1a7b8 u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3495): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3495): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3495): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3495): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3495): Skipping PackageSetting{304352ec com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3495): Force stopping com.test.thalitest appid=10647 user=0: pkg removed
,D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/WifiService( 3495): Client connection lost with reason: 4
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3495): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     ( 6942): Explicit concurrent mark sweep GC freed 3614(157KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 2.648ms total 70.848ms
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/GeofencerStateMachine( 4671): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4445): mOCRHelper is null
,I/art     ( 8982): Explicit concurrent mark sweep GC freed 30055(1675KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 760us total 73.630ms
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/ResourceType( 5221): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5221): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12683): MountEmulatedStorage()
,E/Zygote  (12683): v2
I/libpersona(12683): KNOX_SDCARD checking this for 10063
,I/libpersona(12683): KNOX_SDCARD not a persona
,I/ActivityManager( 3495): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12683 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12683): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 3495): Explicit concurrent mark sweep GC freed 45279(3MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 49MB/65MB, paused 2.369ms total 138.595ms
,D/TimaKeyStoreProvider(12683): TimaSignature is unavailable
,D/ActivityThread(12683): Added TimaKeyStore provider
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(12683): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/SecContentProvider2( 3495): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3495): mCursor = null
,D/BatteryService( 3495): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3495): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3495): online:4, current avg:-233, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-461
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/BatteryService( 3495): stay LED for fully charged
,D/VRSetupWizardStub/PackageIntentReceiver(12683): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12683): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12683): packagename:com.test.thalitest
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.521: (12238): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 15:52:53 GMT+01:00 2016
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/RegisteredServicesCache( 3959): empty dynamic service
,D/EnterpriseDeviceManagerService( 3495): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3495): Admin package name: com.google.android.gms
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/KLMS-2.4.521: (12238): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
I/splitIntent( 3495): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/splitIntent( 3495): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Books/Books.apk
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onCreate()
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/KLMS-2.4.521: (12238): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.521: (12238): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12238): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (12238): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  (12701): MountEmulatedStorage()
E/Zygote  (12701): v2
I/libpersona(12701): KNOX_SDCARD checking this for 10106
I/libpersona(12701): KNOX_SDCARD not a persona
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/SELinux (12701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12238): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/ActivityManager( 3495): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12701 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/PackageManager( 3495): delete codoeFile: 
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,I/AASAUninstall( 3495):  com.test.thalitest not target!
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/PackageManager( 3495): result of delete: 1{826103043}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/AndroidRuntime(12670): Shutting down VM
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/PackageManager( 3495): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Zygote  (12715): MountEmulatedStorage()
E/Zygote  (12715): v2
I/libpersona(12715): KNOX_SDCARD checking this for 10050
I/libpersona(12715): KNOX_SDCARD not a persona
,I/SELinux (12715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(12701): TimaSignature is unavailable
,I/ActivityManager( 3495): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12715 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityThread(12701): Added TimaKeyStore provider
,I/SELinux (12715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/TimaKeyStoreProvider(12715): TimaSignature is unavailable
,D/ActivityThread(12715): Added TimaKeyStore provider
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (12238): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/RCPManager(12352):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3495): PackageReceiver onReceive()
I/HarmonyEASService( 3495): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/RCPManagerService( 3495):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3495): queryAllProviders():  providerCallBack is not register for 0
,D/KnoxMUMContainerPolicy( 3495): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3495): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 3495): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3495): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3495): uID is 10647
V/EnterpriseBillingPolicy( 3495): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3495): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3495): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3495): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3495): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3495): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3495): getBillingProfileForVpnEngine - end - null
,I/KLMS-2.4.521: (12238): KLMSIntentService(): onDestroy()
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12715): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12715): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ResourcesManager(12701): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/ResourcesManager(12715): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12715): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12715): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12715): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(12715): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12715): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12715): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12731): MountEmulatedStorage()
E/Zygote  (12731): v2
I/libpersona(12731): KNOX_SDCARD checking this for 10101
I/libpersona(12731): KNOX_SDCARD not a persona
,I/SELinux (12731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3495): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12731 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12731): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/BatteryService( 3495): Sending ACTION_BATTERY_CHANGED.
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12701): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12701): ELMEngine.ELMEngine( context ).
,D/elm:14491(12701): MDMBridge.setEnterpriseBridge()
,E/Zygote  (12744): MountEmulatedStorage()
,E/Zygote  (12744): v2
I/libpersona(12744): KNOX_SDCARD checking this for 10183
I/libpersona(12744): KNOX_SDCARD not a persona
,I/SELinux (12744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3495): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12744 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/TaskPersister( 3495): removeObsoleteFile: deleting file=25_task.xml
E/SELinux (12744): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12701): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12701): ElmAgentService : onCreate()
,D/elm:14491(12701): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12701): MainReceiver.listeningToPackageRemoved()
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
W/ResourceType( 3495): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/elm:14491(12701): MDMBridge.getInstance()
D/elm:14491(12701): MDMBridge.getAllLicenseInfoFromSDK()
D/TimaKeyStoreProvider(12731): TimaSignature is unavailable
,D/ActivityThread(12731): Added TimaKeyStore provider
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14491(12701): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService( 3495): Plugged
I/MotionRecognitionService( 3495): setPowerConnected  = true
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3495): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3495): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3495): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3495): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,V/HeadsetService( 5627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/HeadsetStateMachine( 5627): Disconnected process message: 10
D/ResourcesManager( 3495): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/TimaKeyStoreProvider(12744): TimaSignature is unavailable
,D/ActivityThread(12744): Added TimaKeyStore provider
,D/ResourcesManager( 3495): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/elm:14491(12701): ElmAgentService : onDestroy().
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 3495): Killing 11863:com.sec.android.widgetapp.dualclockdigital/u0a105 (adj 13): bgCount ##31
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3495): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(12731): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3495): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12744): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/Zygote  (12765): MountEmulatedStorage()
I/libpersona(12765): KNOX_SDCARD checking this for 10019
E/Zygote  (12765): v2
I/libpersona(12765): KNOX_SDCARD not a persona
I/SELinux (12765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/PackageManager( 3495): findPreferredActivity: No PreferredActivities set
I/SELinux (12765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12765 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 10909:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/UsbSettingsManager( 3495): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3495): onPackageRemoved : com.test.thalitest
,D/TimaKeyStoreProvider(12765): TimaSignature is unavailable
,D/ActivityThread(12765): Added TimaKeyStore provider
,D/NearbySource(12715): Nearby Source Create!
,D/NearbyContext(12715): Nearby Context Create!
,E/SQLiteLog(12744): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12715): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12715): Samsung link source created
,D/ResourcesManager(12765): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (12782): MountEmulatedStorage()
E/Zygote  (12782): v2
I/libpersona(12782): KNOX_SDCARD checking this for 10190
I/libpersona(12782): KNOX_SDCARD not a persona
,I/SELinux (12782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12782 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/DocsApplication(12731): Installing DEX configuration.
,E/SQLiteLog(12715): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/TimaKeyStoreProvider(12782): TimaSignature is unavailable
,D/ActivityThread(12782): Added TimaKeyStore provider
,E/SQLiteDatabase(12715): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12715): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12715): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12715): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12715): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12715): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12715): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12715): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12715): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12715): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12715): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12715): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12715): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12715): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12715): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12715): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12715): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12715): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12715): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12715): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12715): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12715): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12715): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12715): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12715): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12715): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12715): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12715): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12715): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12715): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12715): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12715): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12715): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12715): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12715): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper(12715): Opened local.db in read-only mode
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 886us total 29.969ms
,D/DexInstaller(12731): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/ActivityManager( 3495): Killing 11666:com.android.vending/u0a31 (adj 13): bgCount ##31
I/PackageInfoHelper(12731): Provided clientMode=RELEASE, packageInfo=PackageInfo{2a46ec66 com.google.android.apps.docs}
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TAG     (12731): onCreate()
,D/CrossAppStateProvider(12731): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12765): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12765): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.433ms total 19.841ms
D/com.sec.android.service.health.upgrade.UninstallReceiver(12765): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12782): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.143ms total 14.702ms
,D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3495): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3495): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3495): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3495): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3495): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3495): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3495): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12782): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12782): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,E/Zygote  (12805): MountEmulatedStorage()
E/Zygote  (12805): v2
I/libpersona(12805): KNOX_SDCARD checking this for 10022
I/libpersona(12805): KNOX_SDCARD not a persona
I/SELinux (12805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/TapandpayWidget:Utils(12782): Clear T&P info.
E/SELinux (12805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12805 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3495): Killing 11810:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,D/ContactProvider(12715): getAllContactInfoList Start
,D/UsbHostManager( 3495): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
,D/UsbHostManager( 3495): displayNotification : [09h,00h,00h]
,D/TimaKeyStoreProvider(12805): TimaSignature is unavailable
,D/ActivityThread(12805): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 3495): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12782): Widget is not attached.
,I/ActivityManager( 3495): Killing 12538:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
D/ResourcesManager(12805): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12805): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12805): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12805): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/UsbHostManager( 3495): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3495): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/MtpClient(12715): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(12715): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/EventHub( 3495): Removing device '/dev/input/event10' due to inotify event
,E/SharedPreferencesImpl(12715): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/LocationWidgetApplication(12805): onCreate() : start
D/LocationWidgetApplication(12805): countryCode = POLAND
,I/EventHub( 3495): Removing device '/dev/input/event7' due to inotify event
,D/PackageBroadcastService( 6942): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6942): Clearing selected account for com.test.thalitest
,E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3495): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3495): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  (12824): MountEmulatedStorage()
,E/Zygote  (12824): v2
I/libpersona(12824): KNOX_SDCARD checking this for 10052
I/libpersona(12824): KNOX_SDCARD not a persona
,I/SELinux (12824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27,
,I/SELinux (12824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12824): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3495): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12824 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/EventHub( 3495): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteLog( 6942): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/EventHub( 3495): Removing device '/dev/input/event11' due to inotify event
,E/DriveAsyncService( 6942): disk I/O error (code 3850)
E/DriveAsyncService( 6942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6942): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6942): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6942): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6942): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6942): 	at java.lang.Thread.run(Thread.java:818)
,I/LocationSettingsChecker( 6942): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 6942): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6942): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6942): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6942): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6942): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6942): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6942): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaKeyStoreProvider(12824): TimaSignature is unavailable
,D/ActivityThread(12824): Added TimaKeyStore provider
,W/SQLiteOpenHelper( 6942): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6942): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6942): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6942): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6942): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 6942): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6942): Process: com.google.android.gms, PID: 6942
E/AndroidRuntime( 6942): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6942): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6942): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6942): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6942): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6942): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6942): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6942): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6942): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3495): Removing device '/dev/input/event12' due to inotify event
,D/LocationManagerService( 3495): getProviders()=[]
D/LocationManagerService( 3495): getProviders()=[passive]
D/LocationManagerService( 3495): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12805): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12805): getLastUiLocationId() : mLastUiLocationId = -100
,E/SQLiteLog(12805): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12805): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12805): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12805): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12805): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12805): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12805): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12805): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12805): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12805): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12805): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12805): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12805): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12805): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(12805): Shutting down VM
,E/AndroidRuntime(12805): FATAL EXCEPTION: main
E/AndroidRuntime(12805): Process: com.sec.android.widgetapp.locationwidget, PID: 12805
E/AndroidRuntime(12805): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12805): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12805): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12805): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12805): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12805): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12805): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12805): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12805): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12805): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12805): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12805): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12805): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12805): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12805): 	... 9 more
,I/EventHub( 3495): Removing device '/dev/input/event13' due to inotify event
,V/ApplicationPolicy( 3495): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,V/ApplicationPolicy( 3495): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/EventHub( 3495): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12824): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/SQLiteLog( 6942): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 6942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 6942): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/ClearPendingStateOp( 6942): Runtime exception while performing operation
E/ClearPendingStateOp( 6942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6942): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6942): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6942): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6942): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 6942): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6942): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6942): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6942): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6942): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6942): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6942): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6942): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 6942): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6942): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6942): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager(12824): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,E/PhenotypeInitializer( 6942): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6942): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6942): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager(12824): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 3495): Killing 8779:com.android.settings/1000 (adj 13): bgCount ##31
E/DropBoxManagerService( 3495): Can't write: system_app_crash
E/DropBoxManagerService( 3495): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3495): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3495): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3495): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3495): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3495): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3495): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3495): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3495): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3495): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3495): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3495): 	... 5 more
,W/ResourcesManager(12824): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12824): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     ( 4671): Explicit concurrent mark sweep GC freed 73268(4MB) AllocSpace objects, 27(1104KB) LOS objects, 34% free, 30MB/46MB, paused 2.641ms total 123.668ms
,W/ResourcesManager(12824): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12824): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/DropBoxManagerService( 3495): Can't write: system_app_crash
E/DropBoxManagerService( 3495): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3495): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3495): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3495): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3495): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3495): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3495): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3495): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3495): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3495): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3495): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3495): 	... 5 more
,E/SQLiteLog( 6942): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6942): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/PCWCLIENTTRACE_SYSTEMReceiver(12145): mConnectivityHandler : connected
,E/GMPM-SVC( 6942): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,D/ChimeraCfgMgr( 6942): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6942): Module APK com.google.android.play.games already loaded
,D/ContactProvider(12715): getAllContactInfoList End
,I/syncContacts(12715): thread: 1803, sync time = 572
,E/SharedPreferencesImpl( 6942): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak

```
