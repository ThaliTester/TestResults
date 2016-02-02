#### Test 575312435db8e90_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 52
--------- beginning of main
D/AndroidRuntime(11991): 
D/AndroidRuntime(11991): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11991): CheckJNI is OFF
D/AndroidRuntime(11991): readGMSProperty: start
D/AndroidRuntime(11991): readGMSProperty: already setted!!
D/AndroidRuntime(11991): readGMSProperty: end
D/AndroidRuntime(11991): addProductProperty: start
E/AffinityControl(11991): AffinityControl: registerfunction enter
D/AndroidRuntime(11991): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
D/FocusedStackFrame( 3522): Set to : 0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (12015): MountEmulatedStorage()
E/Zygote  (12015): v2
I/libpersona(12015): KNOX_SDCARD checking this for 10613
I/libpersona(12015): KNOX_SDCARD not a persona
I/SELinux (12015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=12015 uid=10613 gids={50613, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (12015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/AndroidRuntime(11991): Shutting down VM
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
E/SELinux (12015): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider(12015): TimaSignature is unavailable
D/ActivityThread(12015): Added TimaKeyStore provider
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager( 3522): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager( 3522): Display changed displayId=0
D/ResourcesManager(12015): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=13 Removed Mauncher (5/8)
I/SurfaceFlinger( 2849): id=13 Removed Mauncher (-2/8)
V/ActivityThread( 3999): updateVisibility : ActivityRecord{e563644 token=android.os.BinderProxy@37820336 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3999): onTrimMemory. Level: 20
I/WebViewFactory(12015): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12015): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12015): Loading: webviewchromium
,I/LibraryLoader(12015): Time to load native libraries: 4 ms (timestamps 5622-5626)
I/LibraryLoader(12015): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12015): Binding Chromium to main looper Looper (main, tid 1) {76c555c}
,I/LibraryLoader(12015): Expected native library version number "",actual native library version number ""
,I/chromium(12015): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12015): Initializing chromium process, renderers=0
,W/art     (12015): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12015): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12015): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(12015): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(12015): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(12015): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (12015): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(12015): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(12015): CordovaWebView is running on device made by: samsung
,W/art     (12015): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (12015): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(12015): performCreate Call secproduct feature valuefalse
D/Activity(12015): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(12015): Render dirty regions requested: true
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(12015): Initialized EGL, version 1.4
,I/OpenGLRenderer(12015): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278770928 
,D/OpenGLRenderer(12015): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(12015): Enabling debug mode 0
,D/mali_winsys(12015): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(12015): updateVisibility : ActivityRecord{1c9dcd8c token=android.os.BinderProxy@2f512773 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 3522): mDVFSHelper.release()
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{26809972 u0 com.test.thalitest/.MainActivity t26} time:246137
,W/IInputConnectionWrapper(12015): showStatusIcon on inactive InputConnection
,I/Timeline(12015): Timeline: Activity_idle id: android.os.BinderProxy@2f512773 time:246144
,I/chromium(12015): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(12015): 
,D/JsMessageQueue(12015): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(12015): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361619200
,I/chromium(12015): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(12015): Initializing JXcore engine
W/jxcore-log(12015): JXcore engine is ready
,E/auditd  ( 4620): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(12015): Starting JXcore engine
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log(12015): Platform android
W/jxcore-log(12015): 
W/jxcore-log(12015): Process ARCH arm
W/jxcore-log(12015): 
,I/jxcore-log(12015): JXcore Cordova bridge is ready!
I/jxcore-log(12015): 
W/jxcore-log(12015): JXcore engine is started
,I/jxcore-log(12015): Toggling radios to true
I/jxcore-log(12015): 
,D/BluetoothAdapter(12015): enable()
,D/BluetoothAdapter(12015): enable(): BT is already enabled..!
,D/WifiService( 3522): New client listening to asynchronous messages
,I/WifiManager(12015): packageName : com.test.thalitest
,D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3522): mCursor = null
,D/WifiService( 3522): setWifiEnabled: true pid=12015, uid=10613
E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3522): Permission Denial: getCurrentUser() from pid=12015, uid=10613 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3522): Failed getting userId using ActivityManagerNative
W/WifiService( 3522): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=12015, uid=10613 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3522): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3522): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3522): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3522): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3522): name = wifi_on
,I/WifiService( 3522): disconnect: pid=12015, uid=10613
,I/wpa_supplicant( 3825): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(12015): Radios toggled
I/jxcore-log(12015): 
,I/jxcore-log(12015): My device name is: samsung-SM-N910C
I/jxcore-log(12015): 
,I/wpa_supplicant( 3825): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3825): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3522): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3825): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): Disconnected - do not scan
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3522): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1),
,E/WifiStateMachine( 3522): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,E/WifiStateMachine( 3522): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3825): First Scan Start
E/WifiStateMachine( 3522): ConnectModeState: Network connection lost 
I/Hs20UtilService( 4109): Starting #8
I/wpa_supplicant( 3825): Scan requested (ret=0) - scan timeout 30 seconds
,I/Hs20UtilService( 4109): Message received 5007
E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/NearbySettings( 8827): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8827): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8827): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8827): DMSUtil.isNetworkConnected - flag-null, state-null
D/WifiP2pService( 3522): InactiveState{ what=143375 }
D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3522): New client listening to asynchronous messages
,I/NearbySettings( 8827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8827): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8827): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3522): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3522): Not allowed due to - mEnabled false
,D/ConnectivityService( 3522): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3522): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3522): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - currTime: 1454412491371
D/WifiStateMachine( 3522): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3522): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/EntConnectivity( 3522): Not allowed due to - mEnabled false
,D/Tethering( 3522): MasterInitialState.processMessage what=3
D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524292
I/SignOutReceiver(11523): NETWORK_STATE_CHANGED_ACTION
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3522): updateIfacesLocked()
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked(flags=0x1)
E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/SmartBondingService( 3522): getSBEnabled() enabled =false
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/WifiNetworkAgent( 3522): NetworkAgent: NetworkAgent channel lost
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
V/NetworkStats( 3522): performPollLocked() took 5ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,I/Hs20UtilService( 4109): Starting #9
,I/Hs20UtilService( 4109): Message received 5007
,D/NearbySettings( 8827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8827): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8827): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8827): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11523): NETWORK_STATE_CHANGED_ACTION
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
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3522): updateDataUsageMap
I/ApplicationPolicy( 3522): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3522): No Active Data Connection
,I/DBG_DM  ( 6247): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 6247): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  (12125): MountEmulatedStorage()
E/Zygote  (12125): v2
I/libpersona(12125): KNOX_SDCARD checking this for 10110
I/libpersona(12125): KNOX_SDCARD not a persona
,I/SELinux (12125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12125 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12125): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12125): TimaSignature is unavailable
,D/ActivityThread(12125): Added TimaKeyStore provider
,D/ResourcesManager(12125): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (12125): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(12125): not using cross-dex optimization: ART in use
,I/art     (12125): Thread[1,tid=12125,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(12125): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(12125): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(12125): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(12125): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12125): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12125): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(12125): loading pre-built fallback odex files
V/MultiDexClassLoader(12125): installing MultiDexClassLoader before application classloader
D/DexLibLoader(12125): released odex store lock
D/DexLibLoader(12125): DexLibLoader.loadAll took 15 ms
,W/ca      (12125): Verify
,W/LightSharedPreferencesImpl(12125): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12125): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12125): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12125): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12125): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12125): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12125): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12125): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12125): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12125): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12125): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12125): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12125): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12125): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12125): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12125): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12125): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12125): 	... 10 more
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (12150): MountEmulatedStorage()
I/libpersona(12150): KNOX_SDCARD checking this for 1000
E/Zygote  (12150): v2
I/libpersona(12150): KNOX_SDCARD not a persona
I/SELinux (12150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12150 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11249:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
W/appmanager(:<default>):b(12125): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12125): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12150): TimaSignature is unavailable
D/ActivityThread(12150): Added TimaKeyStore provider
,D/ResourcesManager(12150): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(12125): Exposure of experiment com.facebook.common.network.l@355de703 occurred when no user was logged in
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3265ed91 u0 ReceiverList{2b8b7bb8 12125 com.facebook.appmanager/10110/u0 remote:2d095e1b}}
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3265ed91 u0 ReceiverList{2b8b7bb8 12125 com.facebook.appmanager/10110/u0 remote:2d095e1b}}
I/PCWCLIENTTRACE_LOG(12150): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12150): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12150): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12150): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12150): sales region : global
I/PCWCLIENTTRACE_PushUtil(12150): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12150): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12150): noConnectivity : true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12181): MountEmulatedStorage()
I/libpersona(12181): KNOX_SDCARD checking this for 10135
E/Zygote  (12181): v2
I/libpersona(12181): KNOX_SDCARD not a persona
,I/SELinux (12181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12181): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12181 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11265:com.wsomacp/u0a28 (adj 15): bgCount ##31
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{79d6d85 u0 ReceiverList{c39f2fc 12125 com.facebook.appmanager/10110/u0 remote:217dd7ef}}
,D/TimaKeyStoreProvider(12181): TimaSignature is unavailable
,D/ActivityThread(12181): Added TimaKeyStore provider
,D/ResourcesManager(12181): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(12181): Database version: 104
,D/ResourcesManager(12181): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12181): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e4462f0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12181): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12181): GMSCore installation verified
,I/ConfigStore(12181): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12125): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12125): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12181): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12181): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(12125): Exposure of experiment com.facebook.imagepipeline.a.g@1aab9000 occurred when no user was logged in
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12181): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(12125): Exposure of experiment com.facebook.imagepipeline.a.d@390be6f5 occurred when no user was logged in
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3522): getStreamVolume 3 index 0
,I/MediaRouter(12181): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/art     (12125): Explicit concurrent mark sweep GC freed 44311(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 584us total 22.081ms
,W/appmanager(:<default>):m(12125): No feature status reporters found; is this dead code?
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3825): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3825): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3825): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3522): [1,454,412,492,427 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3522): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@244d308f sup_state=SCANNING debouncing=false
,E/Zygote  (12209): MountEmulatedStorage()
I/libpersona(12209): KNOX_SDCARD checking this for 10002
E/Zygote  (12209): v2
I/libpersona(12209): KNOX_SDCARD not a persona
,I/SELinux (12209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12209 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3522): setDetailed state send new extra info
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/TimaKeyStoreProvider(12209): TimaSignature is unavailable
D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityThread(12209): Added TimaKeyStore provider
,I/NetworkMonitor(12181): type=WIFI subType= reason=null isConnected=false
,D/ResourcesManager(12209): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3522): Killing 11234:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/ActivityManager( 3522): Killing 11287:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12230): MountEmulatedStorage()
I/libpersona(12230): KNOX_SDCARD checking this for 1000
E/Zygote  (12230): v2
I/libpersona(12230): KNOX_SDCARD not a persona
I/SELinux (12230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/SELinux (12230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/wpa_supplicant( 3825): Associated with C0.AA.48
E/SELinux (12230): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3522): setDetailed state send new extra info"NG700"
,I/ActivityManager( 3522): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12230 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/TimaKeyStoreProvider(12230): TimaSignature is unavailable
D/ActivityThread(12230): Added TimaKeyStore provider
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3825): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3825): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3825): Blacklist: Clear (temp) 
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3522): Network connection established
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3522): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3522): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/ResourcesManager(12230): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ConnectivityService( 3522): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3522): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3522): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3522): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3522): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3522): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
I/DIAGMON_AGENT(12230): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12230): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12230): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12230): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12230): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend false
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12247): MountEmulatedStorage()
E/Zygote  (12247): v2
I/libpersona(12247): KNOX_SDCARD checking this for 10012
I/libpersona(12247): KNOX_SDCARD not a persona
,I/SELinux (12247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12247): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12247 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12247): TimaSignature is unavailable
,D/ActivityThread(12247): Added TimaKeyStore provider
,D/ResourcesManager(12247): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3522): Killing 11210:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,I/FOTA_Client(12247): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12247): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12247): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12263): MountEmulatedStorage()
E/Zygote  (12263): v2
I/libpersona(12263): KNOX_SDCARD checking this for 10021
I/libpersona(12263): KNOX_SDCARD not a persona
,I/SELinux (12263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12263 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11323:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12263): TimaSignature is unavailable
,D/ActivityThread(12263): Added TimaKeyStore provider
,D/ResourcesManager(12263): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12263): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 12:28:12 GMT+01:00 2016
,I/KLMS-2.4.521: (12263): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12263): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12263): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12263): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12263): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12263): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12263): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12263): StateImplV2(): networkChangeListener().END
,E/Zygote  (12279): MountEmulatedStorage()
I/libpersona(12279): KNOX_SDCARD checking this for 10038
E/Zygote  (12279): v2
I/libpersona(12279): KNOX_SDCARD not a persona
I/SELinux (12279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12279 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12263): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3522): Killing 11383:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12279): TimaSignature is unavailable
,D/ActivityThread(12279): Added TimaKeyStore provider
,D/ResourcesManager(12279): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12279): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  (12294): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12294): version 5.5.6 starting
,E/dhcpcd  (12294): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  (12296): MountEmulatedStorage()
I/libpersona(12296): KNOX_SDCARD checking this for 1000
E/Zygote  (12296): v2
I/libpersona(12296): KNOX_SDCARD not a persona
I/SELinux (12296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12296): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12296 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11402:com.samsung.android.app.watchmanagerstub/u0a121 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11402/oom_score_adj; errno=22
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 424us total 10.843ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 681us total 9.540ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 8.266ms
D/TimaKeyStoreProvider(12296): TimaSignature is unavailable
,D/ActivityThread(12296): Added TimaKeyStore provider
,I/dhcpcd  (12294): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12294): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12294): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12294): bssid match
I/dhcpcd  (12294): wlan0: rebinding lease of 192.168.1.124
,D/ResourcesManager(12296): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12321): MountEmulatedStorage()
E/Zygote  (12321): v2
I/libpersona(12321): KNOX_SDCARD checking this for 10039
I/libpersona(12321): KNOX_SDCARD not a persona
,I/SELinux (12321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12321 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12321): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 11368:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12321): TimaSignature is unavailable
D/ActivityThread(12321): Added TimaKeyStore provider
,D/ResourcesManager(12321): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12321): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12321): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12321): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12321): PushLog.txt file is not deleted.
D/SPPClientService(12321): PushLog.txt file is not deleted.
D/SPPClientService(12321): ============PushLog. stop!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12338): MountEmulatedStorage()
I/libpersona(12338): KNOX_SDCARD checking this for 10045
E/Zygote  (12338): v2
I/libpersona(12338): KNOX_SDCARD not a persona
,I/SELinux (12338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12338): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12338 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11420:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11420/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12338): TimaSignature is unavailable
,D/ActivityThread(12338): Added TimaKeyStore provider
E/SPPClientService(12321): [[SystemStateMonitorService]] No Active Internet
,D/ResourcesManager(12338): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12338): [SSP] onCreated
,I/SA      (12338): [TPM] There is no property file
,I/SA      (12338): [SCU] isHaveSA() - false
,I/SA      (12338): [TPM] getModelProperty : null
I/SA      (12338): [TPM] getCSCProperty : null
,I/SA      (12338): [DM] init START
,I/SA      (12338): [DM] This device is not a Vodafone
,I/SA      (12338): checkReactivationActive for LOLLIPOP
I/SA      (12338): checkReactivationActive for reactiveActive
I/SA      (12338): setSupportRL : true
,I/SA      (12338): [SCU] isHaveSA() - false
I/SA      (12338): support phone number id : false
,I/SA      (12338): [DM] init END
I/SA      (12338): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12338): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12338): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12338): [SLFUCHKMGR] constructor called
,I/SA      (12338): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12338): [OR] == isSIMCardReady false ==
,I/SA      (12338): [SCU] == networkStateCheck == false
I/SA      (12338): [OR] onReceive END
,I/ActivityManager( 3522): Killing 11435:com.samsung.helphub/1000 (adj 15): bgCount ##31
,V/DownloadManager( 5736): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12359): MountEmulatedStorage()
I/libpersona(12359): KNOX_SDCARD checking this for 10067
E/Zygote  (12359): v2
I/libpersona(12359): KNOX_SDCARD not a persona
,I/SELinux (12359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12359): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12359 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12359): TimaSignature is unavailable
,D/ActivityThread(12359): Added TimaKeyStore provider
,D/ResourcesManager(12359): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12359): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12359): Other Intent
,I/ActivityManager( 3522): Killing 11470:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##31
,D/accuweather( 5196): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5196): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5196): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5196): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5196): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12375): MountEmulatedStorage()
E/Zygote  (12375): v2
,I/libpersona(12375): KNOX_SDCARD checking this for 1000
I/libpersona(12375): KNOX_SDCARD not a persona
I/SELinux (12375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12375 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12375): TimaSignature is unavailable
,D/ActivityThread(12375): Added TimaKeyStore provider
,D/ResourcesManager(12375): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12375): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12375): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12375): premStatus:2
,I/KnoxUsageLogPro(12375): isEulaShown : false
I/KnoxUsageLogPro(12375): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12390): MountEmulatedStorage()
E/Zygote  (12390): v2
I/libpersona(12390): KNOX_SDCARD checking this for 10090
I/libpersona(12390): KNOX_SDCARD not a persona
,I/SELinux (12390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12390): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12390 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/lowmemorykiller( 2827): Error writing /proc/11546/oom_score_adj; errno=22
I/ActivityManager( 3522): Killing 11546:com.samsung.android.snote:provider/u0a160 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12390): TimaSignature is unavailable
,D/ActivityThread(12390): Added TimaKeyStore provider
,D/ResourcesManager(12390): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12406): MountEmulatedStorage()
E/Zygote  (12406): v2
I/libpersona(12406): KNOX_SDCARD checking this for 10127
I/libpersona(12406): KNOX_SDCARD not a persona
,I/SELinux (12406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12406): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12406 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11566:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12406): TimaSignature is unavailable
,D/ActivityThread(12406): Added TimaKeyStore provider
,D/ResourcesManager(12406): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12406): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12406): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12406): stopCheckCategoryVersion
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12422): MountEmulatedStorage()
E/Zygote  (12422): v2
I/libpersona(12422): KNOX_SDCARD checking this for 10136
I/libpersona(12422): KNOX_SDCARD not a persona
,I/SELinux (12422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12422): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12422 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11584:com.sec.android.widgetapp.tapandpay/u0a190 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12422): TimaSignature is unavailable
,D/ActivityThread(12422): Added TimaKeyStore provider
,D/ResourcesManager(12422): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12422): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12422): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12422): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12422): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12422): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12422): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12422): Loading: webviewchromium
,I/LibraryLoader(12422): Time to load native libraries: 2 ms (timestamps 9715-9717)
I/LibraryLoader(12422): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12422): Binding Chromium to main looper Looper (main, tid 1) {37a4be1c}
,I/LibraryLoader(12422): Expected native library version number "",actual native library version number ""
,I/chromium(12422): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12422): Initializing chromium process, renderers=0
,W/art     (12422): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12422): Requires BLUETOOTH permission
W/chromium(12422): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12422): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12422): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12422): Starting up...
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12489): MountEmulatedStorage()
I/libpersona(12489): KNOX_SDCARD checking this for 10147
E/Zygote  (12489): v2
I/libpersona(12489): KNOX_SDCARD not a persona
,I/SELinux (12489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12489): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=12489 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11620:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12489): TimaSignature is unavailable
,D/ActivityThread(12489): Added TimaKeyStore provider
,D/ResourcesManager(12489): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(12489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 4632): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 4632): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  (12517): MountEmulatedStorage()
I/libpersona(12517): KNOX_SDCARD checking this for 10150
E/Zygote  (12517): v2
I/libpersona(12517): KNOX_SDCARD not a persona
,I/SELinux (12517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12517 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12517): TimaSignature is unavailable
,D/ActivityThread(12517): Added TimaKeyStore provider
,D/ResourcesManager(12517): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12517): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12517): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12517): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12517): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12517): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 78718(4MB) AllocSpace objects, 45(720KB) LOS objects, 23% free, 51MB/67MB, paused 1.540ms total 79.181ms
,I/QuickConnect(12517): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12533): MountEmulatedStorage()
E/Zygote  (12533): v2
I/libpersona(12533): KNOX_SDCARD checking this for 10178
I/libpersona(12533): KNOX_SDCARD not a persona
,I/SELinux (12533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12533): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12533 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11635:com.android.calendar/u0a164 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12533): TimaSignature is unavailable
,D/ActivityThread(12533): Added TimaKeyStore provider
,D/ResourcesManager(12533): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12533): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12533): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12533): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12533): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12533): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/BadgeProvider(11856): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/BadgeProvider(11856): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11856): sendNotify, [notify] : null
D/BadgeProvider(11856): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(11856): update, [BadgeCount] : badgecount=0
D/BadgeProvider(11856): update, [UpdateCount] : 1
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Launcher.Model( 3999): reloadBadges entered.
,E/Zygote  (12560): MountEmulatedStorage()
E/Zygote  (12560): v2
I/libpersona(12560): KNOX_SDCARD checking this for 1000
I/libpersona(12560): KNOX_SDCARD not a persona
,I/SELinux (12560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 11603:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 677us total 10.435ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 252us total 8.221ms
,D/TimaKeyStoreProvider(12560): TimaSignature is unavailable
,D/ActivityThread(12560): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 313us total 8.561ms
,D/ResourcesManager(12560): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3522): Killing 10911:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,I/dhcpcd  (12294): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/iu.Environment( 4757): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 4757): num queued entries: 0
,I/iu.UploadsManager( 4757): num updated entries: 0
I/iu.SyncManager( 4757): NEXT; no task
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12579): MountEmulatedStorage()
I/libpersona(12579): KNOX_SDCARD checking this for 10013
E/Zygote  (12579): v2
I/libpersona(12579): KNOX_SDCARD not a persona
,I/SELinux (12579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12579): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12579 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager( 3522): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/dhcpcd  (12294): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/TimaKeyStoreProvider(12579): TimaSignature is unavailable
,D/ActivityThread(12579): Added TimaKeyStore provider
,D/ResourcesManager(12579): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3522): Killing 10388:com.android.vending/u0a31 (adj 15): bgCount ##31
,I/Hs20UtilService( 4109): Starting #10
,I/Hs20UtilService( 4109): Message received 5007
,D/NearbySettings( 8827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8827): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8827): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8827): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11523): NETWORK_STATE_CHANGED_ACTION
,I/jxcore-log(12015): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(12015): 
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3522): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3522): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3522): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3522): Not connected state, yet.
E/WifiStateMachine( 3522): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3522): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3522): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3522): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3522): callSECApiInt - ID [210]
E/WifiStateMachine( 3522): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3522): updateNetworkInfo()
,D/ConnectivityService( 3522): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3522): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3522): updateDnsLinkProperty: enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.DnsPinger( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3522): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3522): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3522): Now, connected state.
E/WifiStateMachine( 3522): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3522): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3522): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3522): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3522): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,D/ConnectivityService( 3522): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3522): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityService( 3522): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
E/ConnectivityService( 3522): Unexpected mtu value: 0, wlan0
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4109): Starting #11
,I/Hs20UtilService( 4109): Message received 5007
,D/NearbySettings( 8827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8827): MountReceiver.onReceive - Keep current state
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3522): route cmd failed: 
W/NetworkManagementService( 3522): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '71 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 71 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3522): '
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3522): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3522): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3522): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
I/SignOutReceiver(11523): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
I/Hs20UtilService( 4109): Starting #12
I/Hs20UtilService( 4109): Message received 5007
D/NearbySettings( 8827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8827): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8827): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8827): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8827): MountReceiver.mPrefHandler - 7002
V/        ( 2845): QcRouteController
I/SignOutReceiver(11523): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
I/Hs20UtilService( 4109): Starting #13
I/Hs20UtilService( 4109): Message received 5007
,D/NearbySettings( 8827): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8827): MountReceiver.onReceive - Keep current state
,V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
,I/WifiStateMachine( 3522): callSECApi what=220
D/WifiStateMachine( 3522): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11523): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3522): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3522): LTETest block dns file not exists
D/ConnectivityService( 3522): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3522): updateNetworkInfo()
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3522): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Connected
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3522): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 3522):    accepting network in place of null
D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/CSLegacyTypeTracker( 3522): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/CSLegacyTypeTracker( 3522): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/ConnectivityService( 3522): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/Tethering( 3522): MasterInitialState.processMessage what=3
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524290
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
V/NetworkStats( 3522): updateIfacesLocked()
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked(flags=0x1)
,I/SurfaceFlinger( 2849): id=16 createSurf (1x1),1 flag=4, Uoast
D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked() took 3ms
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/PowerManagerService( 3522): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,I/System.out( 3522): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 11:28:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454412494695], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454412494677]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): Validated
D/ConnectivityService( 3522): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3522): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3522): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 4757): CM callback handler got msg 524290
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
,I/jxcore-log(12015): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(12015): 
,I/jxcore-log(12015): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(12015): 
,I/jxcore-log(12015): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(12015): 
,I/jxcore-log(12015): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(12015): 
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3522): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3522): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6247): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6247): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(12181): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5346): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5346): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(12150): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12150): sales region : global
I/PCWCLIENTTRACE_PushUtil(12150): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12150): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,I/DIAGMON_AGENT(12230): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12230): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12247): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12247): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12247): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12263): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 12:28:15 GMT+01:00 2016
,I/KLMS-2.4.521: (12263): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12263): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12263): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12263): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12263): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SO_AGENT(12279): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12263): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12263): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12263): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12263): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12263): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12263): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12263): KLMSIntentService(): onDestroy()
,E/SPPClientService(12321): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12338): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12338): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12338): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12338): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12338): [OR] == isSIMCardReady false ==
,I/SA      (12338): [SCU] == networkStateCheck == true
I/SA      (12338): [DM] getCountryCodeFromCSC : PL
I/SA      (12338): isChinaCountryCode : false
I/SA      (12338): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12338): [OR] == networkStateCheck true ==
,I/SA      (12338): [OR] GetMyCountryZoneTask
I/SA      (12338): [OR] onReceive END
,I/SA      (12338): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5736): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12338): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12338): [SSP] query invoked
,I/SCloudBackupReceiver(12359): Other Intent
,D/accuweather( 5196): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (12338): [TPMU] GetMccFromDB : null
,I/SA      (12338): [SCU] getMccFromPreferece mcc = 260
I/SA      (12338): [TPM] isNoProxy(default) : true
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5196): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5196): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5196): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5196): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5196): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12375): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12375): premStatus:2
,I/KnoxUsageLogPro(12375): isEulaShown : false
I/KnoxUsageLogPro(12375): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12406): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12406): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12406): stopCheckCategoryVersion
,D/QuickConnect(12517): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12517): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12517): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,I/iu.Environment( 4757): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4757): num queued entries: 0
I/iu.UploadsManager( 4757): num updated entries: 0
,I/iu.SyncManager( 4757): NEXT; no task
,D/WaitQueueForNetworkActivate(12579): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12579): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3522): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/GLSActivity( 4632): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4632): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/hcjo    (12579): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12579): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12579): exit::IDLE
D/InitializeManagerStateMachine(12579): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12579): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12579): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12579): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12579): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12579): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12579): entry::SUCCESS
D/hcjo    (12579): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12579): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12579): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/System.out( 4632): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4632): Tagging socket 67 with tag 1000040100000000{268436481,0} uid 10014, pid: 4632, getuid(): 10014
,D/InitializeManagerStateMachine(12579): exit::SUCCESS
D/InitializeManagerStateMachine(12579): entry::IDLE
,I/SA      (12338): [RC New] Execute method=[GET] start
,I/SA      (12338): [RC New] Security=[true]
,I/System.out(12338): Thread-1725(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12338): Thread-1725(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12338): Thread-1725(ApacheHTTPLog):isShipBuild true
I/System.out(12338): Thread-1725(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3522): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/GCM     ( 4632): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/SA      (12338): [RC New] [v2liruge] api execute + 812
I/SA      (12338): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(12338): AsyncTask #1 calls detatch()
,I/SA      (12338): [TPMU] getNetworkMcc : 
,I/SA      (12338): [SCU] saveMccToPreferece Start
I/SA      (12338): [SCU] RegionMCC : 260
I/SA      (12338): [SSP] query invoked
,I/SA      (12338): [TPMU] GetMccFromDB : null
I/SA      (12338): [SCU] getMccFromPreferece mcc = 260
I/SA      (12338): [SCU] saveMccToPreferece End
,I/SA      (12338): [RC New] executeRequest [v2liruge] end. 833
I/SA      (12338): [RC New] Execute end
I/SA      (12338): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12338): [OR] GetMyCountryZoneTask Success
,E/Watchdog( 3522): !@Sync 8
,I/dhcpcd  (12294): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4632): callingUid 10014, callindPid: 4632
,D/ResourcesManager(12181): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12181): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12181): Conditions not met for autocaching.
I/MusicLeanback(12181): Stop autocaching.
,D/WearableClient(12181): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12181): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12181): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12181): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12181): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12181): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12181): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1f2694c8 that was originally bound here
E/ActivityThread(12181): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1f2694c8 that was originally bound here
E/ActivityThread(12181): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12181): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12181): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12181): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12181): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12181): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12181): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12181): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12181): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12181): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12181): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12181): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12181): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12181): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12181): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12181): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12181): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12181): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12181): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12181): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12181): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12181): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12181): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12181): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3522): REQUEST_POWER_SAVE_ON
,I/jxcore-log(12015): Test app app.js loaded
I/jxcore-log(12015): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(12015): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@203b71f4 added. We now have 1 listener(s)
,I/jxcore-log(12015): BLE advertisement is supported
I/jxcore-log(12015): 
,I/chromium(12015): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger( 2849): id=16 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=16 Removed Uoast (-2/9)
D/PowerManagerService( 3522): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3522) eventTime = 254269
D/PowerManagerService( 3522): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3522 (0x0)
,D/PowerManagerService( 3522): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3522, ws=WorkSource{10060}) (elapsedTime=3477)
,E/WifiStateMachine( 3522): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/GAV4    (12422): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 3522): SIOP:: AP = 290, PST = 255, CUR = 50
,I/GAV2    (12489): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3522): Killing 11751:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/PackageManager( 3522): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-228, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:111
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PCWCLIENTTRACE_SYSTEMReceiver(12150): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(12150): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(12150): ================================================
,I/CSTORAGE(12150):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12150): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12150): [GetString-S]
E/art     (12150): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(12150): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12150): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12150): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(12150): sales region : global
,I/PCWCLIENTTRACE_PushUtil(12150): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12150): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12294): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12294): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12294): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12579): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12579): exit::IDLE
D/PreloadUpdateManagerStateMachine(12579): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12579): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (12579): RestApi Request Add : 2307
,I/System.out(12579): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12579): (HTTPLog)-Static: isShipBuild true
I/System.out(12579): (HTTPLog)-Thread-1775-1020746621: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12579): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10013
,I/System.out(12579): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12579): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12579, getuid(): 10013
,I/qtaguid (12579): Untagging socket 26
,D/hcjo    (12579): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (12579): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(12579): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12579): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12579): entry::REQ_UPDATE_CHECK
,I/Volley  (12579): RestApi Request Add : 2315
,I/System.out(12579): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(12579): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12579): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12579, getuid(): 10013
,I/qtaguid (12579): Untagging socket -1
,I/qtaguid (12579): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (12579): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger(12579): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine(12579): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(12579): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine(12579): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12579): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine(12579): entry::FINISH
,D/PreloadUpdateManagerStateMachine(12579): exit::FINISH
,D/PreloadUpdateManagerStateMachine(12579): entry::IDLE
,I/PowerManagerService( 3522): [PWL] Off : 140s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 256, CUR = -228
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:-41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:78
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = -41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 9
,I/art     ( 4632): Explicit concurrent mark sweep GC freed 82412(4MB) AllocSpace objects, 53(2MB) LOS objects, 34% free, 30MB/46MB, paused 1.996ms total 63.646ms
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 261, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 261, CUR = 48
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 180s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 261, CUR = 55
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3522): initializing...
,I/TLC_TIMA_PKM_initialize( 3522): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3522): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3522): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3522): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3522): device_id = 0x0
I/TZ: mc_tlc_communication( 3522): tlc_open() was called
I/TZ: mc_tlc_communication( 3522): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3522): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3522): Opening the session
,I/TZ: mc_tlc_communication( 3522): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3522): Trustlet response is completed
,E/Watchdog( 3522): !@Sync 10
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 260, CUR = 55
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 260, CUR = 53
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 260, CUR = 52
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 11
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 260, CUR = 50
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 225s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 48,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 46
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 12
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 254, CUR = 45
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 252, CUR = 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3522): [PWL] Off : 275s ago
,E/Watchdog( 3522): !@Sync 13
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 250, CUR = 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 249, CUR = 42
,V/AlarmManager( 3522): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 248, CUR = 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 14
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 247, CUR = 40
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 40
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 330s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 246, CUR = 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 15
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 38
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 245, CUR = 37
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 37
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 16
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 244, CUR = 36
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 35
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 390s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 243, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 17
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 36
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 242, CUR = 34
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 33
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 18
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 241, CUR = 33
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 33
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 455s ago
,E/Watchdog( 3522): !@Sync 19
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 32
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 33
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 31
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3522): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 31
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 32
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3522): Killing 11781:com.sec.android.app.camera/u0a168 (adj 13): bgCount ##31
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 30,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 21
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 31
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3522): [PWL] Off : 525s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 31
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 31
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 22
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 30
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 23
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 600s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3522): !@Sync 24
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 25
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 26
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/LightsService( 3522): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 4757): Aggregate from 1454411007270 (log), 1454411007270 (data)
,I/Sensors ( 3522): #>LightSensor r=255 g=249 b=203 c=542 atime=238 again=64 lux=92.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 92
I/Sensors ( 3522): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26,
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 680s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 27
,V/AlarmManager( 3522): waitForAlarm result :4
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 26,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 25
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 28
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 29
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,I/PowerManagerService( 3522): [PWL] Off : 765s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,I/GCM     ( 4757): Message from null null
E/GCM     ( 4757): Dropping message from null
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 21,
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 31
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 22
,I/PowerManagerService( 3522): [PWL] Off : 855s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 33
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 34
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 19
,E/Watchdog( 3522): !@Sync 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 950s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 19
,E/Watchdog( 3522): !@Sync 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 18,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,E/Watchdog( 3522): !@Sync 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 18
,E/Watchdog( 3522): !@Sync 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,E/Watchdog( 3522): !@Sync 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 16
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3522): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3522): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3522): Updating Usage Statistics in DB @ 1454413455136
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.a,ndroid.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3522): Done Updating Usage Statistics in DB @ 1454413455193
,E/Watchdog( 3522): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,E/Watchdog( 3522): !@Sync 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,E/Watchdog( 3522): !@Sync 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 17
,I/PowerManagerService( 3522): [PWL] Off : 1155s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,I/art     ( 3522): Background sticky concurrent mark sweep GC freed 114856(10MB) AllocSpace objects, 320(5MB) LOS objects, 13% free, 51MB/59MB, paused 3.300ms total 101.994ms
,D/SSRM:n  ( 3522): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 17
,E/Watchdog( 3522): !@Sync 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 239, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 13
,E/Watchdog( 3522): !@Sync 44
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 15,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 238, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 15
,E/Watchdog( 3522): !@Sync 45
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 15,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 237, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 15
,I/PowerManagerService( 3522): [PWL] Off : 1265s ago
,E/Watchdog( 3522): !@Sync 46
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 236, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 13
,E/Watchdog( 3522): !@Sync 47
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 13,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 235, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5635): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 14
,E/Watchdog( 3522): !@Sync 48
,TIME-OUT KILL (timeout was 1200000ms),I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5635): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:n  ( 3522): SIOP:: AP = 230, PST = 234, CUR = 13
D/AndroidRuntime(13611): 
D/AndroidRuntime(13611): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13611): CheckJNI is OFF
D/AndroidRuntime(13611): readGMSProperty: start
D/AndroidRuntime(13611): readGMSProperty: already setted!!
D/AndroidRuntime(13611): readGMSProperty: end
D/AndroidRuntime(13611): addProductProperty: start
E/AffinityControl(13611): AffinityControl: registerfunction enter
D/AndroidRuntime(13611): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3522): START PACKAGE DELETE: observer{300676151}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3522): !@killApplicatoin: 10613, uninstall pkg
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10613 user=-1: uninstall pkg
I/ActivityManager( 3522): Killing 12015:com.test.thalitest/u0a613 (adj 0): stop com.test.thalitest
I/ActivityManager( 3522):   Force finishing activity ActivityRecord{26809972 u0 com.test.thalitest/.MainActivity t26}
I/SurfaceFlinger( 2849): id=15 Removed NainActivit (5/8)
I/SurfaceFlinger( 2849): id=15 Removed NainActivit (-2/8)
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 3522): Skipping PackageSetting{f3e1c63 com.example.hello/10563} due to missing metadata
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10613 user=0: pkg removed
D/WifiService( 3522): Client connection lost with reason: 4
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 4757): Explicit concurrent mark sweep GC freed 7394(419KB) AllocSpace objects, 4(64KB) LOS objects, 20% free, 31MB/39MB, paused 2.492ms total 57.497ms
I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
I/art     ( 8990): Explicit concurrent mark sweep GC freed 29932(1668KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.163ms total 50.392ms
W/GeofencerStateMachine( 4632): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 3979): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3979): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/SamsungIME( 4491): mOCRHelper is null
I/art     ( 4053): Explicit concurrent mark sweep GC freed 772(45KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.159ms total 100.284ms
E/Zygote  (13634): MountEmulatedStorage()
E/Zygote  (13634): v2
I/libpersona(13634): KNOX_SDCARD checking this for 10063
I/libpersona(13634): KNOX_SDCARD not a persona
W/ResourceType( 5346): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5346): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/SELinux (13634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13634 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider(13634): TimaSignature is unavailable
I/art     ( 3522): Explicit concurrent mark sweep GC freed 30882(2MB) AllocSpace objects, 57(912KB) LOS objects, 23% free, 51MB/67MB, paused 2.005ms total 177.454ms
I/art     ( 3522): WaitForGcToComplete blocked for 162.793ms for cause Explicit
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ActivityThread(13634): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager(13634): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
D/RegisteredServicesCache( 3966): empty dynamic service
D/VRSetupWizardStub/PackageIntentReceiver(13634): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13634): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13634): packagename:com.test.thalitest
I/KLMS-2.4.521: (12263): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 12:48:22 GMT+01:00 2016
I/KLMS-2.4.521: (12263): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/KLMS-2.4.521: (12263): KLMSIntentService(): onCreate()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12263): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12263): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12263): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12263): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (12263): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.4.521: (12263): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Zygote  (13651): MountEmulatedStorage()
E/Zygote  (13651): v2
I/libpersona(13651): KNOX_SDCARD checking this for 10106
I/libpersona(13651): KNOX_SDCARD not a persona
I/SELinux (13651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13651): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13651 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/RCPManager(12375):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/art     ( 3522): Explicit concurrent mark sweep GC freed 8008(547KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 51MB/67MB, paused 1.924ms total 132.486ms
D/RCPManagerService( 3522):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
E/Zygote  (13666): MountEmulatedStorage()
E/Zygote  (13666): v2
I/libpersona(13666): KNOX_SDCARD checking this for 10050
I/libpersona(13666): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider(13651): TimaSignature is unavailable
I/SELinux (13666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ActivityThread(13651): Added TimaKeyStore provider
I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13666 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (13666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/TimaKeyStoreProvider(13666): TimaSignature is unavailable
D/ActivityThread(13666): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/PackageManager( 3522): delete codoeFile: 
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/AASAUninstall( 3522):  com.test.thalitest not target!
D/PackageManager( 3522): result of delete: 1{300676151}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(13651): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/AndroidRuntime(13611): Shutting down VM
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(13666): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/ResourcesManager(13666): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13666): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/elm:14491(13651): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/ResourcesManager(13666): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/elm:14491(13651): ELMEngine.ELMEngine( context ).
E/Zygote  (13681): MountEmulatedStorage()
I/libpersona(13681): KNOX_SDCARD checking this for 10101
E/Zygote  (13681): v2
I/libpersona(13681): KNOX_SDCARD not a persona
I/SELinux (13681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/elm:14491(13651): MDMBridge.setEnterpriseBridge()
W/ResourcesManager(13666): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13666): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SELinux (13681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/ActivityManager( 3522): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13681 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13681): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/KLMS-2.4.521: (12263): KLMSIntentService(): listeningToPackageRemoved().END
D/RCPManagerService( 3522): PackageReceiver onReceive()
I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10613
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
D/elm:14491(13651): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(13651): ElmAgentService : onCreate()
D/elm:14491(13651): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(13651): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13651): MDMBridge.getInstance()
D/elm:14491(13651): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(13651): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  (13694): MountEmulatedStorage()
I/libpersona(13694): KNOX_SDCARD checking this for 10183
E/Zygote  (13694): v2
I/libpersona(13694): KNOX_SDCARD not a persona
I/SELinux (13694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13694 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/SELinux (13694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13694): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(13681): TimaSignature is unavailable
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ActivityThread(13681): Added TimaKeyStore provider
E/Zygote  (13709): MountEmulatedStorage()
E/Zygote  (13709): v2
I/libpersona(13709): KNOX_SDCARD checking this for 10019
I/libpersona(13709): KNOX_SDCARD not a persona
I/SELinux (13709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13709 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (13709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(13694): TimaSignature is unavailable
D/ActivityThread(13694): Added TimaKeyStore provider
D/TaskPersister( 3522): removeObsoleteFile: deleting file=26_task.xml
D/elm:14491(13651): ElmAgentService : onDestroy().
I/KLMS-2.4.521: (12263): KLMSIntentService(): onDestroy()
D/ResourcesManager(13681): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/ActivityManager( 3522): Killing 11797:com.sec.android.widgetapp.digitalclock/u0a97 (adj 15): bgCount ##31
I/ActivityManager( 3522): Killing 11813:com.sec.android.widgetapp.dualclockdigital/u0a105 (adj 15): bgCount ##31
D/PackageManager( 3522): findPreferredActivity: No PreferredActivities set
D/TimaKeyStoreProvider(13709): TimaSignature is unavailable
D/ActivityThread(13709): Added TimaKeyStore provider
D/ResourcesManager(13694): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/ResourcesManager(13709): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/NearbySource(13666): Nearby Source Create!
D/NearbyContext(13666): Nearby Context Create!
E/SQLiteLog(13694): (284) automatic index on shooting_modes(title_id)
D/com.sec.android.service.health.upgrade.UninstallReceiver(13709): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(13709): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(13709): onReceive() : package name is not s health. Return !!!
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(13666): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(13666): Samsung link source created
E/Zygote  (13730): MountEmulatedStorage()
E/Zygote  (13730): v2
I/libpersona(13730): KNOX_SDCARD checking this for 10022
I/libpersona(13730): KNOX_SDCARD not a persona
I/SELinux (13730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=13730 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11831:com.android.mms/u0a52 (adj 13): bgCount ##31
D/DocsApplication(13681): Installing DEX configuration.
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/DexInstaller(13681): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper(13681): Provided clientMode=RELEASE, packageInfo=PackageInfo{1c75f8ad com.google.android.apps.docs}
D/TAG     (13681): onCreate()
D/CountryDetector( 3522): No listener is left
D/CrossAppStateProvider(13681): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/TimaKeyStoreProvider(13730): TimaSignature is unavailable
D/ActivityThread(13730): Added TimaKeyStore provider
E/Zygote  (13747): MountEmulatedStorage()
E/Zygote  (13747): v2
I/libpersona(13747): KNOX_SDCARD checking this for 10190
I/libpersona(13747): KNOX_SDCARD not a persona
I/SELinux (13747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13747 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (13747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 11766:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(13747): TimaSignature is unavailable
D/ActivityThread(13747): Added TimaKeyStore provider
D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ResourcesManager(13730): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(13730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13730): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13730): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
E/SharedPreferencesImpl(13666): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/ResourcesManager(13747): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(13747): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13747): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
E/Zygote  (13765): MountEmulatedStorage()
I/libpersona(13765): KNOX_SDCARD checking this for 10052
E/Zygote  (13765): v2
I/libpersona(13765): KNOX_SDCARD not a persona
I/TapandpayWidget:Utils(13747): Clear T&P info.
I/ActivityManager( 3522): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13765 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/LocationWidgetApplication(13730): onCreate() : start
D/LocationWidgetApplication(13730): countryCode = POLAND
I/SELinux (13765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Killing 11856:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
I/SELinux (13765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13765): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TapandpayWidget:TanpandpayAppWidgetProvider(13747): Widget is not attached.
I/ActivityManager( 3522): Killing 8827:com.android.settings/1000 (adj 13): bgCount ##31
D/ContactProvider(13666): getAllContactInfoList Start
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/LocationManagerService( 3522): getProviders()=[]
D/LocationManagerService( 3522): getProviders()=[passive]
D/LocationManagerService( 3522): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(13730): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(13730): getLastUiLocationId() : mLastUiLocationId = -100
D/PackageBroadcastService( 4757): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4757): Clearing selected account for com.test.thalitest
E/SQLiteLog(13730): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(13730): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(13730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13730): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(13730): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(13730): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(13730): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(13730): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(13730): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(13730): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(13730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(13730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13730): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13730): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13730): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(13730): Shutting down VM
E/AndroidRuntime(13730): FATAL EXCEPTION: main
E/AndroidRuntime(13730): Process: com.sec.android.widgetapp.locationwidget, PID: 13730
E/AndroidRuntime(13730): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13730): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(13730): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(13730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(13730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13730): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(13730): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(13730): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(13730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(13730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(13730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(13730): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13730): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(13730): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(13730): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(13730): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(13730): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(13730): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(13730): 	... 9 more
E/SQLiteLog( 4757): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4757): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/TimaKeyStoreProvider(13765): TimaSignature is unavailable
D/ChimeraCfgMgr( 4757): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4757): Module APK com.google.android.play.games already loaded
E/DriveAsyncService( 4757): disk I/O error (code 3850)
E/DriveAsyncService( 4757): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4757): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4757): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4757): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4757): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4757): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4757): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4757): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4757): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4757): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4757): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4757): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4757): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4757): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4757): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4757): 	at java.lang.Thread.run(Thread.java:818)
D/ActivityThread(13765): Added TimaKeyStore provider
D/MtpClient(13666): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED

```
