#### Test 575312431be71d2_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 254, CUR = 51
--------- beginning of main
D/AndroidRuntime(11867): 
D/AndroidRuntime(11867): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11867): CheckJNI is OFF
D/AndroidRuntime(11867): readGMSProperty: start
D/AndroidRuntime(11867): readGMSProperty: already setted!!
D/AndroidRuntime(11867): readGMSProperty: end
D/AndroidRuntime(11867): addProductProperty: start
E/AffinityControl(11867): AffinityControl: registerfunction enter
D/AndroidRuntime(11867): Calling main entry com.android.commands.am.Am
D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager( 3524): mDVFSHelper.acquire()
D/FocusedStackFrame( 3524): Set to : 0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (11886): MountEmulatedStorage()
I/libpersona(11886): KNOX_SDCARD checking this for 10616
E/Zygote  (11886): v2
I/libpersona(11886): KNOX_SDCARD not a persona
I/SELinux (11886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11886 uid=10616 gids={50616, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11886): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11867): Shutting down VM
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11886): TimaSignature is unavailable
D/ActivityThread(11886): Added TimaKeyStore provider
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3524): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3524): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(11886): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3999): updateVisibility : ActivityRecord{15f423a1 token=android.os.BinderProxy@1ccef28b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3999): onTrimMemory. Level: 20
I/WebViewFactory(11886): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11886): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11886): Loading: webviewchromium
I/LibraryLoader(11886): Time to load native libraries: 5 ms (timestamps 5721-5726)
I/LibraryLoader(11886): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11886): Binding Chromium to main looper Looper (main, tid 1) {27c55359}
I/LibraryLoader(11886): Expected native library version number "",actual native library version number ""
I/chromium(11886): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11886): Initializing chromium process, renderers=0
,W/art     (11886): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11886): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11886): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11886): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11886): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11886): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11886): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11886): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11886): CordovaWebView is running on device made by: samsung
,W/art     (11886): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11886): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11886): performCreate Call secproduct feature valuefalse
D/Activity(11886): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11886): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11886): Initialized EGL, version 1.4
I/OpenGLRenderer(11886): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1279823600 
,D/OpenGLRenderer(11886): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11886): Enabling debug mode 0
,D/mali_winsys(11886): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11886): updateVisibility : ActivityRecord{3dd4c4c9 token=android.os.BinderProxy@29295034 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{237da187 u0 com.test.thalitest/.MainActivity t25} time:246200
,W/IInputConnectionWrapper(11886): showStatusIcon on inactive InputConnection
,I/Timeline(11886): Timeline: Activity_idle id: android.os.BinderProxy@29295034 time:246206
,I/chromium(11886): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11886): 
,D/JsMessageQueue(11886): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11886): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359522048
,I/chromium(11886): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11886): Initializing JXcore engine
W/jxcore-log(11886): JXcore engine is ready
,E/auditd  ( 4596): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11886): Starting JXcore engine
,W/jxcore-log(11886): Platform android
W/jxcore-log(11886): 
W/jxcore-log(11886): Process ARCH arm
W/jxcore-log(11886): 
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11886): JXcore Cordova bridge is ready!
I/jxcore-log(11886): 
W/jxcore-log(11886): JXcore engine is started
,I/jxcore-log(11886): Toggling radios to true
I/jxcore-log(11886): 
,D/BluetoothAdapter(11886): enable()
,D/BluetoothAdapter(11886): enable(): BT is already enabled..!
,D/WifiService( 3524): New client listening to asynchronous messages
,I/WifiManager(11886): packageName : com.test.thalitest
,D/SecContentProvider( 3524): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3524): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3524): mCursor = null
,D/WifiService( 3524): setWifiEnabled: true pid=11886, uid=10616
E/WifiService( 3524): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3524): Permission Denial: getCurrentUser() from pid=11886, uid=10616 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3524): Failed getting userId using ActivityManagerNative
W/WifiService( 3524): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11886, uid=10616 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3524): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3524): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3524): name = wifi_on
,I/WifiService( 3524): disconnect: pid=11886, uid=10616
,I/wpa_supplicant( 3832): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11886): Radios toggled
I/jxcore-log(11886): 
,I/jxcore-log(11886): My device name is: samsung-SM-N910C
I/jxcore-log(11886): 
,I/wpa_supplicant( 3832): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3832): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3524): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3832): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): Disconnected - do not scan
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3524): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3524): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,E/WifiStateMachine( 3524): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3832): First Scan Start
,I/wpa_supplicant( 3832): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3524): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
,I/Hs20UtilService( 4108): Starting #8
D/NearbySettings( 8681): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8681): MountReceiver.onReceive - Start HandlerThread
I/Hs20UtilService( 4108): Message received 5007
D/NearbySettings( 8681): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8681): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8681): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3524): New client listening to asynchronous messages
,I/NearbySettings( 8681): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8681): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8681): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3524): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3524): Not allowed due to - mEnabled false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
I/SignOutReceiver(11328): NETWORK_STATE_CHANGED_ACTION
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3524): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - currTime: 1454419271401
,D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker( 3524): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3524): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 3980): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 6816): CM callback handler got msg 524292
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3524): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/Tethering( 3524): MasterInitialState.processMessage what=3
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3524): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,V/NetworkStats( 3524): updateIfacesLocked()
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked(flags=0x1)
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3524): UpdateStatsForKnox
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked() took 7ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4108): Starting #9
,I/Hs20UtilService( 4108): Message received 5007
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/NearbySettings( 8681): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8681): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8681): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8681): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8681): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11328): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3524): updateDataUsageMap
,I/ApplicationPolicy( 3524): updateDataUsageMap  idList is null 
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3524): No Active Data Connection
,I/DBG_DM  ( 6249): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/DBG_DM  ( 6249): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11977): MountEmulatedStorage()
I/libpersona(11977): KNOX_SDCARD checking this for 1000
E/Zygote  (11977): v2
I/libpersona(11977): KNOX_SDCARD not a persona
,I/SELinux (11977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11977 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 513us total 10.297ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 260us total 8.820ms
,D/TimaKeyStoreProvider(11977): TimaSignature is unavailable
,D/ActivityThread(11977): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 458us total 8.984ms
,D/ResourcesManager(11977): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11977): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11977): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11977): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11977): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11977): sales region : global
I/PCWCLIENTTRACE_PushUtil(11977): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11977): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11977): noConnectivity : true
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11993): MountEmulatedStorage()
E/Zygote  (11993): v2
I/libpersona(11993): KNOX_SDCARD checking this for 10135
I/libpersona(11993): KNOX_SDCARD not a persona
,I/SELinux (11993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11993): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11993 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11012:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11993): TimaSignature is unavailable
,D/ActivityThread(11993): Added TimaKeyStore provider
,D/ResourcesManager(11993): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11993): Database version: 104
,D/ResourcesManager(11993): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11993): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11993): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11993): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11993): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11993): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a79001d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11993): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11993): GMSCore installation verified
,I/ConfigStore(11993): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11993): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3524): getStreamVolume 3 index 0
,I/MediaRouter(11993): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12018): MountEmulatedStorage()
E/Zygote  (12018): v2
I/libpersona(12018): KNOX_SDCARD checking this for 10002
I/libpersona(12018): KNOX_SDCARD not a persona
,I/SELinux (12018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12018): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12018 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11993): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3524): Killing 10181:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12018): TimaSignature is unavailable
,D/ActivityThread(12018): Added TimaKeyStore provider
,D/ResourcesManager(12018): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3524): Killing 10707:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12037): MountEmulatedStorage()
I/libpersona(12037): KNOX_SDCARD checking this for 1000
E/Zygote  (12037): v2
I/libpersona(12037): KNOX_SDCARD not a persona
,I/SELinux (12037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12037): TimaSignature is unavailable
,D/ActivityThread(12037): Added TimaKeyStore provider
,D/CountryDetector( 3524): No listener is left
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 75408(4MB) AllocSpace objects, 49(784KB) LOS objects, 24% free, 49MB/65MB, paused 12.749ms total 96.894ms
,D/ResourcesManager(12037): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(12037): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 3832): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 3832): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3832): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3832): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3524): [1,454,419,272,443 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3524): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2d006665 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/DIAGMON_AGENT(12037): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12037): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12037): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12037): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12054): MountEmulatedStorage()
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD checking this for 10012
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12054): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12054 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3832): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,I/wpa_supplicant( 3832): Associated with C0.AA.48
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,D/ResourcesManager(12054): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 3832): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/wpa_supplicant( 3832): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3832): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3832): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3832): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3832): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3832): Blacklist: Clear (temp) 
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): Network connection established
,D/WifiNative-HAL( 3524): callSECApiVoid - ID [50]
E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3524): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3524): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3524): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3524): updateNetworkInfo()
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/ActivityManager( 3524): Killing 11051:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,E/WifiStateMachine( 3524): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3524): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client(12054): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12054): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3524): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/FOTA_Client(12054): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12071): MountEmulatedStorage()
I/libpersona(12071): KNOX_SDCARD checking this for 10021
E/Zygote  (12071): v2
I/libpersona(12071): KNOX_SDCARD not a persona
,I/SELinux (12071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12071 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11067:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12071): TimaSignature is unavailable
,D/ActivityThread(12071): Added TimaKeyStore provider
,D/ResourcesManager(12071): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12071): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 14:21:12 GMT+01:00 2016
,I/KLMS-2.4.521: (12071): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12071): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12071): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12071): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12071): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12071): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12071): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12071): StateImplV2(): networkChangeListener().END
,E/Zygote  (12087): MountEmulatedStorage()
,E/Zygote  (12087): v2
I/libpersona(12087): KNOX_SDCARD checking this for 10038
I/libpersona(12087): KNOX_SDCARD not a persona
,I/SELinux (12087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12087): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12087 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12071): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3524): Killing 11085:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12087): TimaSignature is unavailable
,D/ActivityThread(12087): Added TimaKeyStore provider
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/ResourcesManager(12087): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12087): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12102): MountEmulatedStorage()
E/Zygote  (12102): v2
I/libpersona(12102): KNOX_SDCARD checking this for 1000
I/libpersona(12102): KNOX_SDCARD not a persona
,I/SELinux (12102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11102:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12102): TimaSignature is unavailable
,D/ActivityThread(12102): Added TimaKeyStore provider
,D/ResourcesManager(12102): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12122): MountEmulatedStorage()
I/libpersona(12122): KNOX_SDCARD checking this for 10039
E/Zygote  (12122): v2
I/libpersona(12122): KNOX_SDCARD not a persona
I/SELinux (12122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12122): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12122 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11146:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12122): TimaSignature is unavailable
,D/ActivityThread(12122): Added TimaKeyStore provider
,D/ResourcesManager(12122): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12122): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12122): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12122): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12122): PushLog.txt file is not deleted.
D/SPPClientService(12122): PushLog.txt file is not deleted.
D/SPPClientService(12122): ============PushLog. stop!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12139): MountEmulatedStorage()
I/libpersona(12139): KNOX_SDCARD checking this for 10045
E/Zygote  (12139): v2
I/libpersona(12139): KNOX_SDCARD not a persona
,I/SELinux (12139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12139): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12139 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11126:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,E/SPPClientService(12122): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider(12139): TimaSignature is unavailable
,D/ActivityThread(12139): Added TimaKeyStore provider
,D/ResourcesManager(12139): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/dhcpcd  (12156): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12156): version 5.5.6 starting
,E/dhcpcd  (12156): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SA      (12139): [SSP] onCreated
,I/SA      (12139): [TPM] There is no property file
,I/SA      (12139): [SCU] isHaveSA() - false
,I/SA      (12139): [TPM] getModelProperty : null
I/SA      (12139): [TPM] getCSCProperty : null
,I/SA      (12139): [DM] init START
,I/SA      (12139): [DM] This device is not a Vodafone
,I/SA      (12139): checkReactivationActive for LOLLIPOP
I/SA      (12139): checkReactivationActive for reactiveActive
I/SA      (12139): setSupportRL : true
,I/SA      (12139): [SCU] isHaveSA() - false
I/SA      (12139): support phone number id : false
,I/SA      (12139): [DM] init END
I/SA      (12139): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12139): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12139): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12139): [SLFUCHKMGR] constructor called
,I/SA      (12139): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12139): [OR] == isSIMCardReady false ==
,I/SA      (12139): [SCU] == networkStateCheck == false
I/SA      (12139): [OR] onReceive END
,I/ActivityManager( 3524): Killing 11193:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/dhcpcd  (12156): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12156): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12156): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12156): bssid match
I/dhcpcd  (12156): wlan0: rebinding lease of 192.168.1.124
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12167): MountEmulatedStorage()
I/libpersona(12167): KNOX_SDCARD checking this for 10067
E/Zygote  (12167): v2
I/libpersona(12167): KNOX_SDCARD not a persona
,I/SELinux (12167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12167 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12167): TimaSignature is unavailable
,D/ActivityThread(12167): Added TimaKeyStore provider
,D/ResourcesManager(12167): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12167): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12167): Other Intent
,I/ActivityManager( 3524): Killing 11210:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/accuweather( 5200): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5200): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5200): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5200): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5200): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12183): MountEmulatedStorage()
E/Zygote  (12183): v2
I/libpersona(12183): KNOX_SDCARD checking this for 1000
I/libpersona(12183): KNOX_SDCARD not a persona
,I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 269us total 9.790ms
,D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
,D/ActivityThread(12183): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 266us total 8.765ms
,D/ResourcesManager(12183): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 401us total 8.822ms
W/ResourcesManager(12183): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12183): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12183): premStatus:2
,I/KnoxUsageLogPro(12183): isEulaShown : false
I/KnoxUsageLogPro(12183): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12198): MountEmulatedStorage()
E/Zygote  (12198): v2
I/libpersona(12198): KNOX_SDCARD checking this for 10090
I/libpersona(12198): KNOX_SDCARD not a persona
,I/SELinux (12198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12198): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12198 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 11227:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12198): TimaSignature is unavailable
,D/ActivityThread(12198): Added TimaKeyStore provider
,D/ResourcesManager(12198): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12214): MountEmulatedStorage()
E/Zygote  (12214): v2
I/libpersona(12214): KNOX_SDCARD checking this for 10127
I/libpersona(12214): KNOX_SDCARD not a persona
,I/SELinux (12214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12214 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11178:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12214): TimaSignature is unavailable
,D/ActivityThread(12214): Added TimaKeyStore provider
,D/ResourcesManager(12214): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12214): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12214): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12214): stopCheckCategoryVersion
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12230): MountEmulatedStorage()
I/libpersona(12230): KNOX_SDCARD checking this for 10136
E/Zygote  (12230): v2
I/libpersona(12230): KNOX_SDCARD not a persona
I/SELinux (12230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12230): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12230 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 11242:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12230): TimaSignature is unavailable
,D/ActivityThread(12230): Added TimaKeyStore provider
,D/ResourcesManager(12230): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12230): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12230): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12230): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12230): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12230): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12230): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12230): Loading: webviewchromium
,I/LibraryLoader(12230): Time to load native libraries: 2 ms (timestamps 9668-9670)
I/LibraryLoader(12230): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12230): Binding Chromium to main looper Looper (main, tid 1) {362a8119}
,I/LibraryLoader(12230): Expected native library version number "",actual native library version number ""
,I/chromium(12230): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12230): Initializing chromium process, renderers=0
,W/art     (12230): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12230): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12230): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
W/AudioManagerAndroid(12230): Requires BLUETOOTH permission
I/chromium(12230): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12230): Starting up...
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12298): MountEmulatedStorage()
E/Zygote  (12298): v2
I/libpersona(12298): KNOX_SDCARD checking this for 10150
I/libpersona(12298): KNOX_SDCARD not a persona
,I/SELinux (12298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12298 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11351:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12298): TimaSignature is unavailable
,D/ActivityThread(12298): Added TimaKeyStore provider
,D/ResourcesManager(12298): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12298): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12298): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12298): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12298): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12298): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12313): MountEmulatedStorage()
E/Zygote  (12313): v2
I/libpersona(12313): KNOX_SDCARD checking this for 10178
I/libpersona(12313): KNOX_SDCARD not a persona
,I/SELinux (12313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12313 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11368:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12313): TimaSignature is unavailable
,D/ActivityThread(12313): Added TimaKeyStore provider
,D/ResourcesManager(12313): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12313): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12313): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12313): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12313): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3524): exchangeData() failure , invalid userId
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12336): MountEmulatedStorage()
I/libpersona(12336): KNOX_SDCARD checking this for 10082
E/Zygote  (12336): v2
I/libpersona(12336): KNOX_SDCARD not a persona
I/SELinux (12336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12336): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12336 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12336): TimaSignature is unavailable
,D/ActivityThread(12336): Added TimaKeyStore provider
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12352): MountEmulatedStorage()
,E/Zygote  (12352): v2
I/libpersona(12352): KNOX_SDCARD checking this for 1000
I/libpersona(12352): KNOX_SDCARD not a persona
I/SELinux (12352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12352 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11385:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/ActivityManager( 3524): Killing 11402:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/ResourcesManager(12336): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/TimaKeyStoreProvider(12352): TimaSignature is unavailable
,D/ActivityThread(12352): Added TimaKeyStore provider
,D/BadgeProvider(12336): onCreate
D/BadgeProvider(12336): DatabaseHelper
,D/ResourcesManager(12352): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12336): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3524): Killing 11509:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/Launcher.Model( 3999): reloadBadges entered.
,D/BadgeProvider(12336): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12336): sendNotify, [notify] : null
D/BadgeProvider(12336): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12336): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12336): update, [UpdateCount] : 1
,I/iu.Environment( 6816): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6816): num queued entries: 0
,I/iu.UploadsManager( 6816): num updated entries: 0
I/iu.SyncManager( 6816): NEXT; no task
,W/ActivityManager( 3524): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12371): MountEmulatedStorage()
I/libpersona(12371): KNOX_SDCARD checking this for 10013
E/Zygote  (12371): v2
I/libpersona(12371): KNOX_SDCARD not a persona
,I/SELinux (12371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12371): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12371 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12371): TimaSignature is unavailable
,D/ActivityThread(12371): Added TimaKeyStore provider
,D/ResourcesManager(12371): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3524): Killing 11551:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4108): Starting #10
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8681): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8681): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8681): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8681): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8681): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11328): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12156): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12156): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11886): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11886): 
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend true
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3524): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3524): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3524): Not connected state, yet.
E/WifiStateMachine( 3524): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3524): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3524): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3524): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3524): callSECApiInt - ID [210]
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3524): updateNetworkInfo()
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3524): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3524): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4108): Starting #11
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8681): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8681): MountReceiver.onReceive - Keep current state
E/WifiStateMachine( 3524): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3524): Now, connected state.
E/WifiStateMachine( 3524): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3524): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 3524): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 3524): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
D/ConnectivityService( 3524): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/WifiStateMachine( 3524): ConnectedState Enter  mScreenOn=false scanperiod=20000
E/ConnectivityService( 3524): Unexpected mtu value: 0, wlan0
V/        ( 2845): QcRouteController
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3524): callSECApiVoid - ID [212]
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11328): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4108): Starting #12
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8681): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8681): DMSUtil.isNetworkConnected - flag-null, state-null
V/        ( 2845): QcRouteController
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8681): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8681): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8681): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8681): MountReceiver.mPrefHandler - 7002
,V/        ( 2845): QcRouteController
,I/SignOutReceiver(11328): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/Hs20UtilService( 4108): Starting #13
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8681): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8681): MountReceiver.onReceive - Keep current state
,V/        ( 2845): QcRouteController
,I/WifiStateMachine( 3524): callSECApi what=220
D/WifiStateMachine( 3524): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11328): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3524): route cmd failed: 
W/NetworkManagementService( 3524): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3524): '
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3524): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3524): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3524): LTETest block dns file not exists
D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3524): updateNetworkInfo()
E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3524): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3524):    accepting network in place of null
D/TelephonyNetworkFactory( 3980): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 3524): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3524): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3524): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3524): MasterInitialState.processMessage what=3
I/System.out( 3524): (HTTPLog)-Static: isSBSettingEnabled false
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
V/NetworkStats( 3524): updateIfacesLocked()
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked(flags=0x1)
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3524): UpdateStatsForKnox
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=4, Uoast
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
V/NetworkStats( 3524): performPollLocked() took 3ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 6816): CM callback handler got msg 524290
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/PowerManagerService( 3524): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524
D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/System.out( 3524): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:21:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454419274510], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454419274498]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Validated
D/ConnectivityService( 3524): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6816): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11886): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11886): 
,I/jxcore-log(11886): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11886): 
,I/jxcore-log(11886): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(11886): 
,I/jxcore-log(11886): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11886): 
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3524): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3524): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6249): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6249): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11993): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5316): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5316): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11977): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11977): sales region : global
I/PCWCLIENTTRACE_PushUtil(11977): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11977): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12037): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12037): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,I/FOTA_Client(12054): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12054): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12054): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12071): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 14:21:15 GMT+01:00 2016
,I/KLMS-2.4.521: (12071): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12071): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12071): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12071): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12071): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SO_AGENT(12087): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12071): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12071): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12071): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12071): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12071): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12071): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12071): KLMSIntentService(): onDestroy()
,E/SPPClientService(12122): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12139): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (12139): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12139): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12139): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12139): [OR] == isSIMCardReady false ==
,I/SA      (12139): [SCU] == networkStateCheck == true
I/SA      (12139): [DM] getCountryCodeFromCSC : PL
I/SA      (12139): isChinaCountryCode : false
I/SA      (12139): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12139): [OR] == networkStateCheck true ==
I/SA      (12139): [OR] GetMyCountryZoneTask
I/SA      (12139): [OR] onReceive END
,I/SA      (12139): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SCloudBackupReceiver(12167): Other Intent
,I/SA      (12139): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12139): [SSP] query invoked
,D/accuweather( 5200): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (12139): [TPMU] GetMccFromDB : null
I/SA      (12139): [SCU] getMccFromPreferece mcc = 260
I/SA      (12139): [TPM] isNoProxy(default) : true
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5200): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5200): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5200): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5200): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5200): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12183): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12183): premStatus:2
,I/KnoxUsageLogPro(12183): isEulaShown : false
,I/KnoxUsageLogPro(12183): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12214): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12214): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12214): stopCheckCategoryVersion
,D/QuickConnect(12298): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12298): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12298): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,I/iu.Environment( 6816): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6816): num queued entries: 0
,I/iu.UploadsManager( 6816): num updated entries: 0
,I/iu.SyncManager( 6816): NEXT; no task
,D/WaitQueueForNetworkActivate(12371): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12371): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3524): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12371): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12371): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12371): exit::IDLE
D/InitializeManagerStateMachine(12371): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12371): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12371): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12371): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12371): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12371): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12371): entry::SUCCESS
D/hcjo    (12371): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12371): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12371): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12371): exit::SUCCESS
D/InitializeManagerStateMachine(12371): entry::IDLE
,I/SA      (12139): [RC New] Execute method=[GET] start
,I/SA      (12139): [RC New] Security=[true]
,I/System.out(12139): Thread-1705(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12139): Thread-1705(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12139): Thread-1705(ApacheHTTPLog):isShipBuild true
I/System.out(12139): Thread-1705(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3524): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (12139): [RC New] [v2liruge] api execute + 1100
I/SA      (12139): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(12139): AsyncTask #1 calls detatch()
,I/SA      (12139): [TPMU] getNetworkMcc : 
,I/SA      (12139): [SCU] saveMccToPreferece Start
I/SA      (12139): [SCU] RegionMCC : 260
I/SA      (12139): [SSP] query invoked
,I/SA      (12139): [TPMU] GetMccFromDB : null
I/SA      (12139): [SCU] getMccFromPreferece mcc = 260
I/SA      (12139): [SCU] saveMccToPreferece End
,I/SA      (12139): [RC New] executeRequest [v2liruge] end. 1122
I/SA      (12139): [RC New] Execute end
I/SA      (12139): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12139): [OR] GetMyCountryZoneTask Success
,E/Watchdog( 3524): !@Sync 8
,I/dhcpcd  (12156): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4620): callingUid 10014, callindPid: 4620
,D/ResourcesManager(11993): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11993): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11993): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11993): Using the GMSCore's GoogleHttpClient
,D/WearableClient(11993): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11993): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11993): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11993): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11993): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils(11993): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 57813(3MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 49MB/65MB, paused 1.220ms total 81.043ms
,I/MusicLeanback(11993): Conditions not met for autocaching.
I/MusicLeanback(11993): Stop autocaching.
,E/ActivityThread(11993): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1b031f95 that was originally bound here
E/ActivityThread(11993): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1b031f95 that was originally bound here
E/ActivityThread(11993): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11993): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11993): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11993): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11993): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11993): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11993): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11993): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11993): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11993): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11993): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11993): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11993): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11993): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11993): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11993): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11993): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11993): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11993): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11993): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11993): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11993): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11993): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11993): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11993): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3524): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log(11886): Test app app.js loaded
I/jxcore-log(11886): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11886): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f7ada91 added. We now have 1 listener(s)
,I/jxcore-log(11886): BLE advertisement is supported
I/jxcore-log(11886): 
,I/chromium(11886): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (8/9)
I/SurfaceFlinger( 2849): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3524): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3524) eventTime = 254221
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524 (0x0)
D/PowerManagerService( 3524): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3524, ws=WorkSource{10060}) (elapsedTime=3475)
,I/GAV4    (12230): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 3524): SIOP:: AP = 290, PST = 255, CUR = 50
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:-238, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:93
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/PackageManager( 3524): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PCWCLIENTTRACE_SYSTEMReceiver(11977): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11977): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11977): ================================================
,I/CSTORAGE(11977):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11977): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11977): [GetString-S]
,E/art     (11977): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11977): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11977): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11977): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11977): sales region : global
I/PCWCLIENTTRACE_PushUtil(11977): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11977): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12156): wlan0: sending IPv6 Router Solicitation
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12493
,I/dhcpcd  (12156): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12156): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12371): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12371): exit::IDLE
D/PreloadUpdateManagerStateMachine(12371): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12371): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12371): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12371): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12371): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12371): entry::IDLE
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 256, CUR = -238
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:-47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{955a2b3 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 180s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 260, CUR = -47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:67
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 9
,I/art     ( 4620): Explicit concurrent mark sweep GC freed 87898(4MB) AllocSpace objects, 40(1863KB) LOS objects, 34% free, 30MB/46MB, paused 1.940ms total 64.591ms
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 261, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 262, CUR = 44
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 262, CUR = 51
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3524): initializing...
,I/TLC_TIMA_PKM_initialize( 3524): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3524): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3524): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3524): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3524): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3524): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3524): device_id = 0x0
I/TZ: mc_tlc_communication( 3524): tlc_open() was called
,I/TZ: mc_tlc_communication( 3524): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3524): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3524): Opening the session
,I/TZ: mc_tlc_communication( 3524): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3524): Trustlet response is completed
,E/Watchdog( 3524): !@Sync 10
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 260, CUR = 54
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12575
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 225s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 260, CUR = 53
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 260, CUR = 50
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 11
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 260, CUR = 48
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 257, CUR = 47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 256, CUR = 45
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 275s ago
,E/Watchdog( 3524): !@Sync 12
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 255, CUR = 44
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 253, CUR = 43
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 252, CUR = 43,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3524): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 13
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 251, CUR = 43
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 251, CUR = 41
,V/AlarmManager( 3524): waitForAlarm result :8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 330s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 40
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 14
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 39
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 250, CUR = 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 15
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 249, CUR = 37
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 248, CUR = 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 390s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 247, CUR = 36
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 16
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 247, CUR = 36
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 247, CUR = 36
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 246, CUR = 35
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 17
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 245, CUR = 36
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 245, CUR = 35
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 245, CUR = 35
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 455s ago
,E/Watchdog( 3524): !@Sync 18
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 244, CUR = 34
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 243, CUR = 33
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 243, CUR = 32
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 19
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 243, CUR = 33
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 242, CUR = 31
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 242, CUR = 31
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3524): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 242, CUR = 31
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 525s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 241, CUR = 31
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Killing 11569:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 241, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 21
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 241, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 22
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 30
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 29
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 600s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 23
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 28
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 24
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 25
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 680s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 26
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 27
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 28
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 24
,I/PowerManagerService( 3524): [PWL] Off : 765s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 29
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 23
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/LightsService( 3524): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/Sensors ( 3524): Light old sensor_state 0, new sensor_state : 512 en : 1
I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3524): #>LightSensor r=127 g=122 b=101 c=265 atime=238 again=64 lux=43.000000
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 43
,I/Sensors ( 3524): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3524): unregisterListener ::   
,D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 23
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 24
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 31
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 21
,I/PowerManagerService( 3524): [PWL] Off : 855s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 33
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 34,
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 950s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 20
,E/Watchdog( 3524): !@Sync 35
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 21
,E/Watchdog( 3524): !@Sync 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18
,E/Watchdog( 3524): !@Sync 37
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18
,E/Watchdog( 3524): !@Sync 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 17,
,E/Watchdog( 3524): !@Sync 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3524): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3524): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3524): Updating Usage Statistics in DB @ 1454420235207
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3524): 	,at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3524): Done Updating Usage Statistics in DB @ 1454420235270
,E/Watchdog( 3524): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 17
,E/Watchdog( 3524): !@Sync 41
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 17
,I/PowerManagerService( 3524): [PWL] Off : 1155s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16
,E/Watchdog( 3524): !@Sync 42
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16,
,E/Watchdog( 3524): !@Sync 43
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 14
,E/Watchdog( 3524): !@Sync 44
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,I/PowerManagerService( 3524): [PWL] Off : 1265s ago
,E/Watchdog( 3524): !@Sync 45
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15,
,E/Watchdog( 3524): !@Sync 46
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,E/Watchdog( 3524): !@Sync 47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 16
,E/Watchdog( 3524): !@Sync 48
,TIME-OUT KILL (timeout was 1200000ms),I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
D/BatteryService( 3524): stay LED for fully charged
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5625): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5625): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 15
D/AndroidRuntime(13337): 
D/AndroidRuntime(13337): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13337): CheckJNI is OFF
D/AndroidRuntime(13337): readGMSProperty: start
D/AndroidRuntime(13337): readGMSProperty: already setted!!
D/AndroidRuntime(13337): readGMSProperty: end
D/AndroidRuntime(13337): addProductProperty: start
E/AffinityControl(13337): AffinityControl: registerfunction enter
D/AndroidRuntime(13337): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3524): START PACKAGE DELETE: observer{785671813}
D/PackageManager( 3524): pkg{<packageName>}
D/PackageManager( 3524): user{0}
D/PackageManager( 3524): caller{2000}
D/PackageManager( 3524): flags{3}
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3524): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3524): !@killApplicatoin: 10616, uninstall pkg
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10616 user=-1: uninstall pkg
I/ActivityManager( 3524): Killing 11886:com.test.thalitest/u0a616 (adj 0): stop com.test.thalitest
I/ActivityManager( 3524):   Force finishing activity ActivityRecord{237da187 u0 com.test.thalitest/.MainActivity t25}
I/SurfaceFlinger( 2849): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/WifiService( 3524): Client connection lost with reason: 4
W/PackageSettings( 3524): Skipping PackageSetting{ff34459 com.example.hello/10563} due to missing metadata
I/art     ( 3524): Background sticky concurrent mark sweep GC freed 88522(9MB) AllocSpace objects, 371(5MB) LOS objects, 13% free, 49MB/57MB, paused 3.734ms total 165.133ms
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10616 user=0: pkg removed
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 8869): Explicit concurrent mark sweep GC freed 26882(1540KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.281ms total 38.416ms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/InputReader( 3524): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 4513): mOCRHelper is null
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/GeofencerStateMachine( 4620): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/art     ( 6816): Explicit concurrent mark sweep GC freed 7201(312KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.380ms total 75.271ms
I/art     ( 4046): Explicit concurrent mark sweep GC freed 2350(105KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.165ms total 54.313ms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/LWLocationManager(11528): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11528): getLastUiLocationId() : mLastUiLocationId = -100
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
W/ResourceType( 5316): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5316): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
E/Zygote  (13355): MountEmulatedStorage()
E/Zygote  (13355): v2
I/libpersona(13355): KNOX_SDCARD checking this for 10063
I/libpersona(13355): KNOX_SDCARD not a persona
I/SELinux (13355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13355 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (13355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11528): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/TimaKeyStoreProvider(13355): TimaSignature is unavailable
D/ActivityThread(13355): Added TimaKeyStore provider
D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
D/ResourcesManager(11528): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager(13355): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(11528): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/RegisteredServicesCache( 3965): empty dynamic service
D/VRSetupWizardStub/PackageIntentReceiver(13355): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13355): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13355): packagename:com.test.thalitest
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(11528): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/KLMS-2.4.521: (12071): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 14:41:22 GMT+01:00 2016
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.521: (12071): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager(11528): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.521: (12071): KLMSIntentService(): onCreate()
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.521: (12071): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.521: (12071): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/art     ( 3524): Explicit concurrent mark sweep GC freed 17178(1349KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 48MB/64MB, paused 1.937ms total 118.132ms
E/Zygote  (13373): MountEmulatedStorage()
I/libpersona(13373): KNOX_SDCARD checking this for 10106
E/Zygote  (13373): v2
I/libpersona(13373): KNOX_SDCARD not a persona
I/SELinux (13373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13373 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (12071): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux (13373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/SELinux (13373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.4.521: (12071): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (12071): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.4.521: (12071): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/PackageManager( 3524): delete codoeFile: 
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/AASAUninstall( 3524):  com.test.thalitest not target!
D/PackageManager( 3524): result of delete: 1{785671813}
D/AndroidRuntime(13337): Shutting down VM
D/TimaKeyStoreProvider(13373): TimaSignature is unavailable
D/ActivityThread(13373): Added TimaKeyStore provider
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/RCPManager(12183):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
E/Zygote  (13389): MountEmulatedStorage()
E/Zygote  (13389): v2
I/libpersona(13389): KNOX_SDCARD checking this for 10050
I/libpersona(13389): KNOX_SDCARD not a persona
I/SELinux (13389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13389 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (13389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 3524): PackageReceiver onReceive()
I/HarmonyEASService( 3524): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/KnoxMUMContainerPolicy( 3524): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3524): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3524): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): uID is 10616
V/EnterpriseBillingPolicy( 3524): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - end - null
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8748(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 631us total 13.387ms
D/TaskPersister( 3524): removeObsoleteFile: deleting file=25_task.xml
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 842us total 10.521ms
D/ResourcesManager(13373): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/KLMS-2.4.521: (12071): KLMSIntentService(): listeningToPackageRemoved().END
D/TimaKeyStoreProvider(13389): TimaSignature is unavailable
D/ActivityThread(13389): Added TimaKeyStore provider
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 632us total 10.428ms
W/ResourcesManager(11528): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/elm:14491(13373): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(13373): ELMEngine.ELMEngine( context ).
D/elm:14491(13373): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  (13404): MountEmulatedStorage()
E/Zygote  (13404): v2
I/libpersona(13404): KNOX_SDCARD checking this for 10183
I/libpersona(13404): KNOX_SDCARD not a persona
I/SELinux (13404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13404): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13404 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/TimaKeyStoreProvider(13404): TimaSignature is unavailable
D/ActivityThread(13404): Added TimaKeyStore provider
D/elm:14491(13373): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(13373): ElmAgentService : onCreate()
D/ResourcesManager(13389): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/elm:14491(13373): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(13373): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13373): MDMBridge.getInstance()
D/elm:14491(13373): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(13373): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(13389): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13389): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11528): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11528): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11528): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11528): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (12071): KLMSIntentService(): onDestroy()
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(13404): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
E/Zygote  (13421): MountEmulatedStorage()
E/Zygote  (13421): v2
I/libpersona(13421): KNOX_SDCARD checking this for 10101
I/libpersona(13421): KNOX_SDCARD not a persona
I/SELinux (13421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13421 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (13421): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/SQLiteLog(13404): (284) automatic index on shooting_modes(title_id)
D/elm:14491(13373): ElmAgentService : onDestroy().
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (13436): MountEmulatedStorage()
E/Zygote  (13436): v2
I/libpersona(13436): KNOX_SDCARD checking this for 10019
I/libpersona(13436): KNOX_SDCARD not a persona
I/SELinux (13436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13436 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 11528:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
D/TimaKeyStoreProvider(13421): TimaSignature is unavailable
D/ActivityThread(13421): Added TimaKeyStore provider
I/ActivityManager( 3524): Killing 11604:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(13436): TimaSignature is unavailable
D/ActivityThread(13436): Added TimaKeyStore provider
E/Zygote  (13452): MountEmulatedStorage()
I/libpersona(13452): KNOX_SDCARD checking this for 10190
E/Zygote  (13452): v2
I/libpersona(13452): KNOX_SDCARD not a persona
I/SELinux (13452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13452 uid=10190 gids={50190, 9997} abi=armeabi-v7a
I/SELinux (13452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 10828:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
D/ResourcesManager(13421): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(13436): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
D/com.sec.android.service.health.upgrade.UninstallReceiver(13436): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(13436): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(13436): onReceive() : package name is not s health. Return !!!
I/ActivityManager( 3524): Killing 11454:com.android.vending/u0a31 (adj 13): bgCount ##31
W/BroadcastQueue( 3524): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.locationwidget/com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider}
W/BroadcastQueue( 3524): android.os.DeadObjectException
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3524): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3524): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3524): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3524): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(13452): TimaSignature is unavailable
D/ActivityThread(13452): Added TimaKeyStore provider
E/Zygote  (13469): MountEmulatedStorage()
E/Zygote  (13469): v2
I/libpersona(13469): KNOX_SDCARD checking this for 10022
I/libpersona(13469): KNOX_SDCARD not a persona
I/SELinux (13469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=13469 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
E/SELinux (13469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 3524): Spurious death for ProcessRecord{1216f192 13469:com.sec.android.widgetapp.locationwidget/u0a22}, curProc for 11528: null
D/DocsApplication(13421): Installing DEX configuration.
D/NearbySource(13389): Nearby Source Create!
D/NearbyContext(13389): Nearby Context Create!
D/TimaKeyStoreProvider(13469): TimaSignature is unavailable
D/ActivityThread(13469): Added TimaKeyStore provider
D/DexInstaller(13421): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper(13421): Provided clientMode=RELEASE, packageInfo=PackageInfo{1d4d946 com.google.android.apps.docs}
D/TAG     (13421): onCreate()
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(13389): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(13389): Samsung link source created
D/CrossAppStateProvider(13421): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/ResourcesManager(13452): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/ResourcesManager(13469): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
W/ResourcesManager(13469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13469): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider(13389): getAllContactInfoList Start
D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/SharedPreferencesImpl(13389): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
I/TapandpayWidget:TanpandpayAppWidgetProvider(13452): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13452): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(13452): Clear T&P info.
E/Zygote  (13489): MountEmulatedStorage()
E/Zygote  (13489): v2
I/libpersona(13489): KNOX_SDCARD checking this for 10052
D/TapandpayWidget:TanpandpayAppWidgetProvider(13452): Widget is not attached.
I/libpersona(13489): KNOX_SDCARD not a persona
I/ActivityManager( 3524): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13489 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux (13489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Killing 12336:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
I/SELinux (13489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13489): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 8681:com.android.settings/1000 (adj 13): bgCount ##31
I/LocationWidgetApplication(13469): onCreate() : start
D/LocationWidgetApplication(13469): countryCode = POLAND
D/PackageBroadcastService( 6816): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6816): Clearing selected account for com.test.thalitest
D/TimaKeyStoreProvider(13489): TimaSignature is unavailable
D/ActivityThread(13489): Added TimaKeyStore provider
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3524): displayNotification : [02h,02h,01h]
D/ChimeraCfgMgr( 6816): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6816): Module APK com.google.android.play.games already loaded
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3524): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/LocationManagerService( 3524): getProviders()=[]
D/UsbHostManager( 3524): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3524): displayNotification : [0ah,00h,01h]
D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(13469): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(13469): getLastUiLocationId() : mLastUiLocationId = -100

```
