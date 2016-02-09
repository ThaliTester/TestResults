#### Test 5841644866d9c0e_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3451): SIOP:: AP = 250, PST = 259, CUR = 46
--------- beginning of main
D/AndroidRuntime(11794): 
D/AndroidRuntime(11794): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BatteryService( 3451): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3451): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3451): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3451): stay LED for fully charged
D/BatteryService( 3451): Sending ACTION_BATTERY_CHANGED.
D/AndroidRuntime(11794): CheckJNI is OFF
I/MotionRecognitionService( 3451): Plugged
I/MotionRecognitionService( 3451): setPowerConnected  = true
D/AndroidRuntime(11794): readGMSProperty: start
D/AndroidRuntime(11794): readGMSProperty: already setted!!
D/AndroidRuntime(11794): readGMSProperty: end
D/AndroidRuntime(11794): addProductProperty: start
D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5617): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5617): Disconnected process message: 10
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/AffinityControl(11794): AffinityControl: registerfunction enter
D/AndroidRuntime(11794): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3451): inState():  stateMachine is null !!
I/PersonaManagerService( 3451): PersonaId don't exist
I/ActivityManager( 3451): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3451): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3451): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3451): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3451): mDVFSHelper.acquire()
D/FocusedStackFrame( 3451): Set to : 0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/Zygote  (11819): MountEmulatedStorage()
I/ActivityManager( 3451): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11819 uid=10643 gids={50643, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  (11819): v2
I/libpersona(11819): KNOX_SDCARD checking this for 10643
I/libpersona(11819): KNOX_SDCARD not a persona
I/SELinux (11819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11819): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3451): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3451): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3451): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3451): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime(11794): Shutting down VM
D/TimaKeyStoreProvider(11819): TimaSignature is unavailable
D/ActivityThread(11819): Added TimaKeyStore provider
V/WindowOrientationListener( 3451): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3451): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3451): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3451): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3451): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(11819): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2851): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2851): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{17fe8f0a token=android.os.BinderProxy@2021f955 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
,I/WebViewFactory(11819): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11819): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11819): Loading: webviewchromium
,I/LibraryLoader(11819): Time to load native libraries: 4 ms (timestamps 5604-5608)
I/LibraryLoader(11819): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11819): Binding Chromium to main looper Looper (main, tid 1) {3a1de8cf}
,I/LibraryLoader(11819): Expected native library version number "",actual native library version number ""
,I/chromium(11819): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11819): Initializing chromium process, renderers=0
,W/art     (11819): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11819): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11819): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11819): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11819): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11819): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11819): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11819): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11819): CordovaWebView is running on device made by: samsung
,W/art     (11819): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11819): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11819): performCreate Call secproduct feature valuefalse
D/Activity(11819): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11819): Render dirty regions requested: true
,D/ActivityManager( 3451): post active user change for 0
D/KnoxTimeoutHandler( 3451): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3451): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2851): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3451): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3451): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3451): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3451): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3451): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3451): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11819): Initialized EGL, version 1.4
,I/OpenGLRenderer(11819): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1278766832 
,D/OpenGLRenderer(11819): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11819): Enabling debug mode 0
,D/mali_winsys(11819): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11819): updateVisibility : ActivityRecord{396b31ea token=android.os.BinderProxy@295261ad {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3451): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3451): Timeline: Activity_windows_visible id: ActivityRecord{137b69ae u0 com.test.thalitest/.MainActivity t25} time:216058
W/ActivityManager( 3451): mDVFSHelper.release()
,W/IInputConnectionWrapper(11819): showStatusIcon on inactive InputConnection
I/Timeline(11819): Timeline: Activity_idle id: android.os.BinderProxy@295261ad time:216063
,I/chromium(11819): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11819): 
,D/JsMessageQueue(11819): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11819): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358472832
,I/chromium(11819): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11819): Initializing JXcore engine
W/jxcore-log(11819): JXcore engine is ready
,E/auditd  ( 4604): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3451): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3451): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11819): Starting JXcore engine
,W/jxcore-log(11819): Platform android
W/jxcore-log(11819): 
W/jxcore-log(11819): Process ARCH arm
W/jxcore-log(11819): 
,I/jxcore-log(11819): JXcore Cordova bridge is ready!
I/jxcore-log(11819): 
W/jxcore-log(11819): JXcore engine is started
,I/jxcore-log(11819): Toggling radios to true
I/jxcore-log(11819): 
,D/BluetoothAdapter(11819): enable()
,D/BluetoothAdapter(11819): enable(): BT is already enabled..!
,D/WifiService( 3451): New client listening to asynchronous messages
I/WifiManager(11819): packageName : com.test.thalitest
D/SecContentProvider( 3451): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3451): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3451): mCursor = null
D/WifiService( 3451): setWifiEnabled: true pid=11819, uid=10643
E/WifiService( 3451): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3451): Permission Denial: getCurrentUser() from pid=11819, uid=10643 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3451): Failed getting userId using ActivityManagerNative
W/WifiService( 3451): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11819, uid=10643 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3451): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3451): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3451): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3451): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3451): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3451): name = wifi_on
,I/WifiService( 3451): disconnect: pid=11819, uid=10643
I/wpa_supplicant( 3826): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log(11819): Radios toggled
I/jxcore-log(11819): 
I/jxcore-log(11819): My device name is: samsung-SM-N910C
I/jxcore-log(11819): 
I/wpa_supplicant( 3826): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3826): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3826): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3451): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3826): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3826): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3826): Disconnected - do not scan
I/wpa_supplicant( 3826): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3451): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3451): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3451): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3451): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine( 3451): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3451): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3451): do suspend true
D/WifiP2pService( 3451): InactiveState{ what=143375 }
D/WifiP2pService( 3451): P2pEnabledState{ what=143375 }
D/CommandListener( 2846): Clearing all IP addresses on wlan0
E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/WifiStateMachine( 3451): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3451): updateNetworkInfo()
D/ConnectivityService( 3451): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3451): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3451): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3451): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3451): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
I/wpa_supplicant( 3826): wlan0: Setting scan request: 0 sec 0 usec
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
I/wpa_supplicant( 3826): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3826): wlan0: State: DISCONNECTED -> SCANNING
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3826): First Scan Start
I/wpa_supplicant( 3826): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3451): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3451): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3451): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3451): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
E/native  ( 3451): do suspend true
,D/WifiP2pService( 3451): InactiveState{ what=143375 }
,D/WifiP2pService( 3451): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 4086): Starting #8
,I/Hs20UtilService( 4086): Message received 5007
,D/NearbySettings( 8699): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8699): MountReceiver.onReceive - Start HandlerThread
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/NearbySettings( 8699): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 8699): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8699): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3451): New client listening to asynchronous messages
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8699): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8699): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(10840): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3451): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3451): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3451): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3451): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3451): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 3981): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3451): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3451): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine( 3451): updateConfiguredNetworkExpiration - currTime: 1455019960385
D/WifiStateMachine( 3451): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3451): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine( 3451): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 4762): CM callback handler got msg 524292
,E/WifiStateMachine( 3451): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3451): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/WifiTrafficPoller( 3451): evaluateTrafficStatsPolling
E/WifiStateMachine( 3451): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3451): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3451): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3451): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3451): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3451): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3451): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3451): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3451): mCursor = null
,D/EntConnectivity( 3451): Not allowed due to - mEnabled false
,D/Tethering( 3451): MasterInitialState.processMessage what=3
D/SmartBondingService( 3451): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/ConnectivityService( 3451): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService( 3451): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
V/NetworkStats( 3451): updateIfacesLocked()
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
V/NetworkStats( 3451): performPollLocked(flags=0x1)
,D/SmartBondingService( 3451): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3451): UpdateStatsForKnox
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
V/NetworkStats( 3451): performPollLocked() took 8ms
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
,D/SmartBondingService( 3451): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
V/NetworkStats( 3451): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
,D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
,I/Hs20UtilService( 4086): Starting #9
,I/Hs20UtilService( 4086): Message received 5007
D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3451): mCursor = null
,D/NearbySettings( 8699): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8699): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8699): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8699): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(10840): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3981): FileWriteThread : threadType = 3
,D/ConnectivityService( 3451): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3451): updateDataUsageMap
I/ApplicationPolicy( 3451): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3451): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3451): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
,D/SmartBondingService( 3451): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3451): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/SLocation( 3451): No Active Data Connection
,I/DBG_DM  ( 6307): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6307): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11931): MountEmulatedStorage()
E/Zygote  (11931): v2
I/libpersona(11931): KNOX_SDCARD checking this for 1000
I/libpersona(11931): KNOX_SDCARD not a persona
,I/SELinux (11931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11931): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11931 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8718(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 574us total 11.645ms
,D/TimaKeyStoreProvider(11931): TimaSignature is unavailable
,D/ActivityThread(11931): Added TimaKeyStore provider
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 392us total 8.198ms
,D/ResourcesManager(11931): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 261us total 8.635ms
,I/PCWCLIENTTRACE_LOG(11931): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11931): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11931): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11931): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11931): sales region : global
I/PCWCLIENTTRACE_PushUtil(11931): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11931): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11931): noConnectivity : true
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11947): MountEmulatedStorage()
I/libpersona(11947): KNOX_SDCARD checking this for 10135
E/Zygote  (11947): v2
I/libpersona(11947): KNOX_SDCARD not a persona
,I/SELinux (11947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11947): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11947 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3451): Killing 11096:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11947): TimaSignature is unavailable
,D/ActivityThread(11947): Added TimaKeyStore provider
,D/ResourcesManager(11947): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11947): Database version: 104
,D/ResourcesManager(11947): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11947): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11947): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11947): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11947): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11947): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a98036d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11947): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11947): GMSCore installation verified
,I/ConfigStore(11947): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11947): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11947): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11947): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3451): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3451): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3451): getStreamVolume 3 index 0
,I/MediaRouter(11947): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11972): MountEmulatedStorage()
E/Zygote  (11972): v2
I/libpersona(11972): KNOX_SDCARD checking this for 10002
I/libpersona(11972): KNOX_SDCARD not a persona
,I/SELinux (11972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11972 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3451): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11947): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11972): TimaSignature is unavailable
,D/ActivityThread(11972): Added TimaKeyStore provider
,I/ActivityManager( 3451): Killing 11121:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ResourcesManager(11972): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3451): Killing 10160:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11991): MountEmulatedStorage()
E/Zygote  (11991): v2
I/libpersona(11991): KNOX_SDCARD checking this for 1000
I/libpersona(11991): KNOX_SDCARD not a persona
,I/SELinux (11991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11991 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11991): TimaSignature is unavailable
,D/ActivityThread(11991): Added TimaKeyStore provider
,D/ResourcesManager(11991): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11991): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11991): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11991): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11991): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11991): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 3826): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 3826): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3826): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3826): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3451): [1,455,019,961,417 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3451): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1c543231 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3451): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3451): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3451): setDetailed state send new extra info
,D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3451): mCursor = null
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12007): MountEmulatedStorage()
I/libpersona(12007): KNOX_SDCARD checking this for 10012
E/Zygote  (12007): v2
I/libpersona(12007): KNOX_SDCARD not a persona
I/SELinux (12007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12007): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12007 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12007): TimaSignature is unavailable
,D/ActivityThread(12007): Added TimaKeyStore provider
,D/ResourcesManager(12007): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 3826): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/ActivityManager( 3451): Killing 9484:com.android.mms/u0a52 (adj 13): bgCount ##31
,E/WifiStateMachine( 3451): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3451): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3451): setDetailed state send new extra info"NG700"
,I/wpa_supplicant( 3826): Associated with C0.AA.48
,D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3451): mCursor = null
,I/FOTA_Client(12007): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12007): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 3826): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3451): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3451): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/FOTA_Client(12007): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3451): mCursor = null
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3826): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3826): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3826): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3826): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3826): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3826): Blacklist: Clear (temp) 
I/wpa_supplicant( 3826): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  (12023): MountEmulatedStorage()
I/libpersona(12023): KNOX_SDCARD checking this for 10021
E/Zygote  (12023): v2
I/libpersona(12023): KNOX_SDCARD not a persona
,I/SELinux (12023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12023 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3451): Killing 11160:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,E/WifiStateMachine( 3451): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3451): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3451): Network connection established
,D/WifiNative-HAL( 3451): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3451): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3451): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3451): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3451): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3451): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3451): updateNetworkInfo()
E/WifiStateMachine( 3451): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3451): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3451): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,D/TimaKeyStoreProvider(12023): TimaSignature is unavailable
,D/ActivityThread(12023): Added TimaKeyStore provider
,D/CountryDetector( 3451): No listener is left
,E/WifiStateMachine( 3451): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3451): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3451): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3451): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2846): Setting iface cfg
,E/WifiStateMachine( 3451): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3451): mCursor = null
,D/ResourcesManager(12023): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
E/WifiStateMachine( 3451): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3451): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/KLMS-2.4.521: (12023): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 13:12:41 GMT+01:00 2016
,I/KLMS-2.4.521: (12023): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12023): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12023): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12023): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12023): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12023): StateImplV2(): networkChangeListener().END
,E/Zygote  (12040): MountEmulatedStorage()
I/libpersona(12040): KNOX_SDCARD checking this for 10038
E/Zygote  (12040): v2
I/libpersona(12040): KNOX_SDCARD not a persona
,I/SELinux (12040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12040 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3451): Killing 11176:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12040): TimaSignature is unavailable
,D/ActivityThread(12040): Added TimaKeyStore provider
,D/ResourcesManager(12040): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12040): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12055): MountEmulatedStorage()
I/libpersona(12055): KNOX_SDCARD checking this for 1000
E/Zygote  (12055): v2
I/libpersona(12055): KNOX_SDCARD not a persona
,I/SELinux (12055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/WifiStateMachine( 3451): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3451): do suspend false
I/SELinux (12055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12055): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3451): Killing 11194:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/SecContentProvider2( 3451): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3451): InactiveState{ what=143375 }
,D/SecContentProvider2( 3451): mCursor = null
D/WifiP2pService( 3451): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider(12055): TimaSignature is unavailable
,D/ActivityThread(12055): Added TimaKeyStore provider
,D/ResourcesManager(12055): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12075): MountEmulatedStorage()
I/libpersona(12075): KNOX_SDCARD checking this for 10039
E/Zygote  (12075): v2
I/libpersona(12075): KNOX_SDCARD not a persona
,I/SELinux (12075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12075): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12075 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3451): Killing 11210:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12075): TimaSignature is unavailable
,D/ActivityThread(12075): Added TimaKeyStore provider
,D/ResourcesManager(12075): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12075): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12075): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12075): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12075): PushLog.txt file is not deleted.
D/SPPClientService(12075): PushLog.txt file is not deleted.
D/SPPClientService(12075): ============PushLog. stop!
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12092): MountEmulatedStorage()
I/libpersona(12092): KNOX_SDCARD checking this for 10045
E/Zygote  (12092): v2
I/libpersona(12092): KNOX_SDCARD not a persona
I/SELinux (12092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12092): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12092 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SPPClientService(12075): [[SystemStateMonitorService]] No Active Internet
,I/ActivityManager( 3451): Killing 11255:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12092): TimaSignature is unavailable
,D/ActivityThread(12092): Added TimaKeyStore provider
,D/ResourcesManager(12092): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12092): [SSP] onCreated
,I/SA      (12092): [TPM] There is no property file
,I/SA      (12092): [SCU] isHaveSA() - false
,I/SA      (12092): [TPM] getModelProperty : null
I/SA      (12092): [TPM] getCSCProperty : null
,I/SA      (12092): [DM] init START
,I/SA      (12092): [DM] This device is not a Vodafone
,I/SA      (12092): checkReactivationActive for LOLLIPOP
I/SA      (12092): checkReactivationActive for reactiveActive
I/SA      (12092): setSupportRL : true
,I/SA      (12092): [SCU] isHaveSA() - false
I/SA      (12092): support phone number id : false
,I/SA      (12092): [DM] init END
I/SA      (12092): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12092): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12092): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12092): [SLFUCHKMGR] constructor called
,I/SA      (12092): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12092): [OR] == isSIMCardReady false ==
,I/SA      (12092): [SCU] == networkStateCheck == false
I/SA      (12092): [OR] onReceive END
,E/dhcpcd  (12112): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12112): version 5.5.6 starting
,I/ActivityManager( 3451): Killing 11237:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,E/dhcpcd  (12112): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,V/DownloadManager( 5709): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12118): MountEmulatedStorage()
I/libpersona(12118): KNOX_SDCARD checking this for 10067
E/Zygote  (12118): v2
I/libpersona(12118): KNOX_SDCARD not a persona
I/SELinux (12118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12118): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12118 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/dhcpcd  (12112): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12112): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12112): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12112): bssid match
I/dhcpcd  (12112): wlan0: rebinding lease of 192.168.1.124
,D/TimaKeyStoreProvider(12118): TimaSignature is unavailable
,D/ActivityThread(12118): Added TimaKeyStore provider
,D/ResourcesManager(12118): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12118): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12118): Other Intent
,I/ActivityManager( 3451): Killing 11302:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/accuweather( 5185): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5185): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5185): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5185): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5185): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5185): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5185): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12136): MountEmulatedStorage()
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD checking this for 1000
I/libpersona(12136): KNOX_SDCARD not a persona
,I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3451): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12136 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 302us total 10.322ms
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 248us total 7.974ms
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ActivityThread(12136): Added TimaKeyStore provider
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 443us total 8.443ms
,D/ResourcesManager(12136): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12136): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12136): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12136): premStatus:2
,I/KnoxUsageLogPro(12136): isEulaShown : false
I/KnoxUsageLogPro(12136): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12151): MountEmulatedStorage()
I/libpersona(12151): KNOX_SDCARD checking this for 10090
E/Zygote  (12151): v2
I/libpersona(12151): KNOX_SDCARD not a persona
,I/SELinux (12151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3451): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12151 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12151): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Killing 11321:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12151): TimaSignature is unavailable
,D/ActivityThread(12151): Added TimaKeyStore provider
,D/ResourcesManager(12151): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12167): MountEmulatedStorage()
I/libpersona(12167): KNOX_SDCARD checking this for 10127
E/Zygote  (12167): v2
I/libpersona(12167): KNOX_SDCARD not a persona
,I/SELinux (12167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12167 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3451): Killing 11287:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12167): TimaSignature is unavailable
,D/ActivityThread(12167): Added TimaKeyStore provider
,D/ResourcesManager(12167): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12167): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12167): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12167): stopCheckCategoryVersion
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12183): MountEmulatedStorage()
I/libpersona(12183): KNOX_SDCARD checking this for 10136
E/Zygote  (12183): v2
I/libpersona(12183): KNOX_SDCARD not a persona
I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12183): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12183 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3451): Killing 11338:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
,D/ActivityThread(12183): Added TimaKeyStore provider
,D/ResourcesManager(12183): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,I/WebViewFactory(12183): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12183): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12183): Loading: webviewchromium
,I/LibraryLoader(12183): Time to load native libraries: 3 ms (timestamps 9363-9366)
I/LibraryLoader(12183): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12183): Binding Chromium to main looper Looper (main, tid 1) {1ebe6969}
,I/LibraryLoader(12183): Expected native library version number "",actual native library version number ""
,I/chromium(12183): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12183): Initializing chromium process, renderers=0
,W/art     (12183): Attempt to remove local handle scope entry from IRT, ignoring
,I/dhcpcd  (12112): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,W/chromium(12183): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12183): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12183): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12183): Requires BLUETOOTH permission
,I/dhcpcd  (12112): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3451): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3451): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/NSApplication(12183): Starting up...
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12262): MountEmulatedStorage()
I/libpersona(12262): KNOX_SDCARD checking this for 10150
E/Zygote  (12262): v2
I/libpersona(12262): KNOX_SDCARD not a persona
I/SELinux (12262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12262 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3451): Killing 11353:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12262): TimaSignature is unavailable
,D/ActivityThread(12262): Added TimaKeyStore provider
,D/ResourcesManager(12262): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12262): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12262): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12262): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12262): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12262): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12288): MountEmulatedStorage()
I/libpersona(12288): KNOX_SDCARD checking this for 10178
E/Zygote  (12288): v2
I/libpersona(12288): KNOX_SDCARD not a persona
,I/SELinux (12288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12288 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3451): Killing 11439:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12288): TimaSignature is unavailable
,D/ActivityThread(12288): Added TimaKeyStore provider
,D/ResourcesManager(12288): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12288): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12288): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12288): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,E/Zygote  (12311): MountEmulatedStorage()
I/libpersona(12311): KNOX_SDCARD checking this for 10082
E/Zygote  (12311): v2
I/libpersona(12311): KNOX_SDCARD not a persona
,I/SELinux (12311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12311): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12311 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12327): MountEmulatedStorage()
I/libpersona(12327): KNOX_SDCARD checking this for 1000
E/Zygote  (12327): v2
I/libpersona(12327): KNOX_SDCARD not a persona
I/SELinux (12327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(12311): TimaSignature is unavailable
,D/ActivityThread(12311): Added TimaKeyStore provider
I/SELinux (12327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3451): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12327 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12327): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Killing 11456:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/ActivityManager( 3451): Killing 11472:com.facebook.system/u0a10 (adj 13): bgCount ##31
,E/WifiStateMachine( 3451): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3451): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3451): do suspend true
,D/TimaKeyStoreProvider(12327): TimaSignature is unavailable
,D/ActivityThread(12327): Added TimaKeyStore provider
,D/WifiP2pService( 3451): InactiveState{ what=143375 }
D/WifiP2pService( 3451): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3451): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3451): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3451): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3451): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3451): Not connected state, yet.
E/WifiStateMachine( 3451): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,I/art     ( 3451): Explicit concurrent mark sweep GC freed 74008(4MB) AllocSpace objects, 37(592KB) LOS objects, 24% free, 49MB/65MB, paused 1.280ms total 83.285ms
,D/WifiStateMachine( 3451): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3451): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3451): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3451): callSECApiInt - ID [210]
,E/WifiStateMachine( 3451): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/ResourcesManager(12327): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
E/ConnectivityService( 3451): updateNetworkInfo()
,D/ResourcesManager(12311): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ConnectivityService( 3451): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3451): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3451): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3451): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3451): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3451): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/BadgeProvider(12311): onCreate
D/BadgeProvider(12311): DatabaseHelper
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3451): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
,W/ActivityManager( 3451): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 3451): Killing 11498:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
D/BadgeProvider(12311): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
E/WifiStateMachine( 3451): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3451): Now, connected state.
E/WifiStateMachine( 3451): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3451): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller( 3451): evaluateTrafficStatsPolling
D/ConnectivityService( 3451): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/ConnectivityService( 3451): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 3695): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 3451): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3451): Unexpected mtu value: 0, wlan0
V/        ( 2846): QcRouteController
I/WifiTrafficPoller( 3451): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3451): callSECApiVoid - ID [212]
E/WifiStateMachine( 3451): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/        ( 2846): QcRouteController
,E/WifiStateMachine( 3451): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/BadgeProvider(12311): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12311): sendNotify, [notify] : null
D/BadgeProvider(12311): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12311): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12311): update, [UpdateCount] : 1
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
I/WifiStateMachine( 3451): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/Launcher.Model( 4000): reloadBadges entered.
V/        ( 2846): QcRouteController
V/        ( 2846): QcRouteController
I/iu.Environment( 4762): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 4762): num queued entries: 0
I/iu.UploadsManager( 4762): num updated entries: 0
I/iu.SyncManager( 4762): NEXT; no task
V/        ( 2846): QcRouteController
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,V/        ( 2846): QcRouteController
V/        ( 2846): QcRouteController
E/Zygote  (12360): MountEmulatedStorage()
E/Zygote  (12360): v2
I/libpersona(12360): KNOX_SDCARD checking this for 10013
I/libpersona(12360): KNOX_SDCARD not a persona
I/SELinux (12360): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12360): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12360): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12360 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/        ( 2846): QcRouteController
D/ConnectivityService( 3451): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3451): LTETest block dns file not exists
D/TimaKeyStoreProvider(12360): TimaSignature is unavailable
D/ActivityThread(12360): Added TimaKeyStore provider
D/ConnectivityService( 3451): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3451): updateNetworkInfo()
D/ConnectivityService( 3451): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3451): updateNetworkInfo()
D/ConnectivityService( 3451): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3451): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3451):    accepting network in place of null
D/TelephonyNetworkFactory( 3981): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 3451): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3451): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3451): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/System.out( 3451): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3451): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity( 3451): Not allowed due to - mEnabled false
D/ConnectivityService( 3451): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 3451): MasterInitialState.processMessage what=3
D/SmartBondingService( 3451): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3451): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityManager.CallbackHandler( 4762): CM callback handler got msg 524290
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
D/SmartBondingService( 3451): getSBEnabled() enabled =false
,V/NetworkStats( 3451): updateIfacesLocked()
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
V/NetworkStats( 3451): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3451): UpdateStatsForKnox
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
V/NetworkStats( 3451): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
V/NetworkStats( 3451): performPollLocked() took 7ms
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3695): applyOpen
D/StatusBar.NetworkController( 3695): refreshSignalCluster - setNWBoosterIndicators(false)
D/SmartBondingService( 3451): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3695): applyOpen
D/ResourcesManager(12360): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
D/NtpTrustedTime( 3451): currentTimeMillis() cache hit
,D/WaitQueueForNetworkActivate(12360): notifyNetworkActivated
,W/ContextImpl(12360): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3451): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 3451): KnoxVpnUidStorageknoxVpnSupported API value returned is false
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
,I/ActivityManager( 3451): Killing 11530:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4086): Starting #10
,I/Hs20UtilService( 4086): Message received 5007
,D/NearbySettings( 8699): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8699): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:12:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455019962991], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455019962970]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3451): Validated
D/ConnectivityService( 3451): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3451): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3451): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3451): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
D/ConnectivityService( 3451): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/NearbySettings( 8699): MountReceiver.onReceive - Keep current state
,D/ConnectivityManager.CallbackHandler( 4762): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3695): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3695): updateDataNetType()
D/StatusBar.NetworkController( 3695): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3695): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3695): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3695): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3695): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3695): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/SignOutReceiver(10840): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4086): Starting #11
,I/Hs20UtilService( 4086): Message received 5007
,D/NearbySettings( 8699): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8699): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(10840): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4086): Starting #12
,D/NearbySettings( 8699): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8699): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/Hs20UtilService( 4086): Message received 5007
,I/NearbySettings( 8699): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8699): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8699): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(10840): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4086): Starting #13
,I/Hs20UtilService( 4086): Message received 5007
,D/NearbySettings( 8699): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8699): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3451): callSECApi what=220
D/WifiStateMachine( 3451): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(10840): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2851): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3451): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3451
,D/mali_winsys( 3695): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11819): 
,D/ConnectivityService( 3451): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3451): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3451): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3451): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3451): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3451): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3451): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6307): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor(11947): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 6307): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5329): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5329): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11931): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11931): sales region : global
I/PCWCLIENTTRACE_PushUtil(11931): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11931): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3451): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3451): mCursor = null
,I/DIAGMON_AGENT(11991): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11991): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12007): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12007): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12007): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12023): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 13:12:43 GMT+01:00 2016
,I/KLMS-2.4.521: (12023): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12023): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12023): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12023): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(12040): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12023): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12023): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12023): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12023): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12023): StateImplV2(): networkChangeListener().END
,E/SPPClientService(12075): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onDestroy()
,I/SA      (12092): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12092): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12092): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12092): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12092): [OR] == isSIMCardReady false ==
,I/SA      (12092): [SCU] == networkStateCheck == true
I/SA      (12092): [DM] getCountryCodeFromCSC : PL
I/SA      (12092): isChinaCountryCode : false
I/SA      (12092): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12092): [OR] == networkStateCheck true ==
I/SA      (12092): [OR] GetMyCountryZoneTask
,I/SA      (12092): [OR] onReceive END
,I/SA      (12092): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5709): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12092): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12092): [SSP] query invoked
,I/SA      (12092): [TPMU] GetMccFromDB : null
,I/SA      (12092): [SCU] getMccFromPreferece mcc = 260
I/SA      (12092): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12118): Other Intent
,D/accuweather( 5185): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5185): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5185): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5185): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5185): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5185): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5185): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12136): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12136): premStatus:2
,I/KnoxUsageLogPro(12136): isEulaShown : false
I/KnoxUsageLogPro(12136): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12167): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12167): cancelUpdateCategory
,D/KeyguardWallpaperUpdator(12167): stopCheckCategoryVersion
,D/QuickConnect(12262): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12262): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12262): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,D/RCPManagerService( 3451): exchangeData() failure , invalid userId
,I/iu.Environment( 4762): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4762): num queued entries: 0
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11819): 
,I/iu.UploadsManager( 4762): num updated entries: 0
,I/iu.SyncManager( 4762): NEXT; no task
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10014
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
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11819): 
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11819): 
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11819): 
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11819): 
,I/SA      (12092): [RC New] Execute method=[GET] start
,I/SA      (12092): [RC New] Security=[true]
,I/System.out(12092): Thread-1705(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12092): Thread-1705(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12092): Thread-1705(ApacheHTTPLog):isShipBuild true
I/System.out(12092): Thread-1705(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3451): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/GCM     ( 4762): Message from null null
E/GCM     ( 4762): Dropping message from null
,I/SA      (12092): [RC New] [v2liruge] api execute + 622
I/SA      (12092): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12092): AsyncTask #1 calls detatch()
,I/SA      (12092): [TPMU] getNetworkMcc : 
,I/SA      (12092): [SCU] saveMccToPreferece Start
I/SA      (12092): [SCU] RegionMCC : 260
I/SA      (12092): [SSP] query invoked
,I/SA      (12092): [TPMU] GetMccFromDB : null
I/SA      (12092): [SCU] getMccFromPreferece mcc = 260
I/SA      (12092): [SCU] saveMccToPreferece End
,I/SA      (12092): [RC New] executeRequest [v2liruge] end. 641
I/SA      (12092): [RC New] Execute end
I/SA      (12092): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12092): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 3451): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3451): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3451): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
D/SmartBondingService( 3451): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3451): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
D/SmartBondingService( 3451): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3451): route cmd failed: 
W/NetworkManagementService( 3451): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3451): '
W/NetworkManagementService( 3451): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3451): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3451): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3451): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3451): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3451): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3451): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3451): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3451): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3451): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3451): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3451): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4762): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3695): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 4762): CM callback handler got msg 524295
,E/Watchdog( 3451): !@Sync 7
,I/dhcpcd  (12112): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine( 3451): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3451): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 4610): callingUid 10014, callindPid: 4610
,D/ResourcesManager(11947): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11947): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11947): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11947): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11947): Conditions not met for autocaching.
I/MusicLeanback(11947): Stop autocaching.
,D/WearableClient(11947): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11947): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11947): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11947): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11947): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils(11947): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11947): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2cfb0ce5 that was originally bound here
E/ActivityThread(11947): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2cfb0ce5 that was originally bound here
E/ActivityThread(11947): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11947): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11947): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11947): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11947): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11947): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11947): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11947): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11947): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11947): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11947): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11947): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11947): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11947): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11947): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11947): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11947): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11947): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11947): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11947): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11947): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11947): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11947): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11819): 
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11819): 
,I/jxcore-log(11819): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11819): 
,I/SurfaceFlinger( 2851): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2851): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3451): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3451) eventTime = 223591
D/PowerManagerService( 3451): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3451 (0x0)
D/PowerManagerService( 3451): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3451, ws=WorkSource{10060}) (elapsedTime=3479)
,I/jxcore-log(11819): Test app app.js loaded
I/jxcore-log(11819): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11819): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31469bbb added. We now have 1 listener(s)
,I/jxcore-log(11819): BLE advertisement is supported
I/jxcore-log(11819): 
,I/chromium(11819): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11819): --= Surplus to requirements =--
I/jxcore-log(11819): 
I/jxcore-log(11819): ****TEST TOOK:  ms ****
I/jxcore-log(11819): 
I/jxcore-log(11819): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11819): 
,I/GAV4    (12183): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12420): 
D/AndroidRuntime(12420): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12420): CheckJNI is OFF
,D/AndroidRuntime(12420): readGMSProperty: start
D/AndroidRuntime(12420): readGMSProperty: already setted!!
,D/AndroidRuntime(12420): readGMSProperty: end
D/AndroidRuntime(12420): addProductProperty: start
,E/AffinityControl(12420): AffinityControl: registerfunction enter
,D/AndroidRuntime(12420): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3451): START PACKAGE DELETE: observer{414940306}
D/PackageManager( 3451): pkg{<packageName>}
D/PackageManager( 3451): user{0}
D/PackageManager( 3451): caller{2000}
D/PackageManager( 3451): flags{3}
D/PersonaManagerService( 3451): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3451): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3451): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3451): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3451): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3451): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3451): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3451): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3451): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3451): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3451): !@killApplicatoin: 10643, uninstall pkg
I/ActivityManager( 3451): Force stopping com.test.thalitest appid=10643 user=-1: uninstall pkg
,I/ActivityManager( 3451): Killing 11819:com.test.thalitest/u0a643 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3451):   Force finishing activity ActivityRecord{137b69ae u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2851): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2851): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3451): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3451): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3451): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3451): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3451): Skipping PackageSetting{1a3dda65 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3451): Force stopping com.test.thalitest appid=10643 user=0: pkg removed
,D/ResourcesManager( 3451): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/WifiService( 3451): Client connection lost with reason: 4
,I/art     (10840): Explicit concurrent mark sweep GC freed 1105(69KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 1.491ms total 28.719ms
,I/InputReader( 3451): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/GeofencerStateMachine( 4610): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4463): mOCRHelper is null
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,I/art     ( 8783): Explicit concurrent mark sweep GC freed 29263(1641KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 3.011ms total 62.148ms
,D/LWLocationManager(11513): getDeviceLocationId :  id = -100
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/LocationWidgetApplication(11513): getLastUiLocationId() : mLastUiLocationId = -100
,E/Zygote  (12433): MountEmulatedStorage()
I/libpersona(12433): KNOX_SDCARD checking this for 10063
E/Zygote  (12433): v2
I/libpersona(12433): KNOX_SDCARD not a persona
I/SELinux (12433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3451): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12433 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SSRM:n  ( 3451): SIOP:: AP = 290, PST = 259, CUR = 45
,I/art     ( 3451): Explicit concurrent mark sweep GC freed 45261(3MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 49MB/65MB, paused 1.928ms total 119.147ms
,W/ResourceType( 5329): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5329): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/TimaKeyStoreProvider(12433): TimaSignature is unavailable
,D/ActivityThread(12433): Added TimaKeyStore provider
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(12433): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12433): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12433): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12433): packagename:com.test.thalitest
,D/SecContentProvider2( 3451): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3451): mCursor = null
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/KLMS-2.4.521: (12023): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 09 13:12:47 GMT+01:00 2016
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/RegisteredServicesCache( 3961): empty dynamic service
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/KLMS-2.4.521: (12023): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3451): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3451): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Books/Books.apk
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12023): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/KLMS-2.4.521: (12023): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.521: (12023): KLMSIntentService(): PACKAGE_REMOVED
E/Zygote  (12453): MountEmulatedStorage()
I/libpersona(12453): KNOX_SDCARD checking this for 10106
E/Zygote  (12453): v2
I/libpersona(12453): KNOX_SDCARD not a persona
,I/SELinux (12453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
I/KLMS-2.4.521: (12023): KLMSIntentService(): listeningToPackageRemoved().START
I/SELinux (12453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3451): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12453 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/PackageManager( 3451): delete codoeFile: 
,I/KLMS-2.4.521: (12023): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/AASAUninstall( 3451):  com.test.thalitest not target!
D/PackageManager( 3451): result of delete: 1{414940306}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/AndroidRuntime(12420): Shutting down VM
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/EnterpriseDeviceManagerService( 3451): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3451): Admin package name: com.google.android.gms
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11513): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/TimaKeyStoreProvider(12453): TimaSignature is unavailable
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityThread(12453): Added TimaKeyStore provider
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,D/RCPManager(12136):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3451):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3451): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (12468): MountEmulatedStorage()
E/Zygote  (12468): v2
I/libpersona(12468): KNOX_SDCARD checking this for 10050
I/libpersona(12468): KNOX_SDCARD not a persona
,I/SELinux (12468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3451): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12468 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (12468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11513): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11513): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11513): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 914us total 29.596ms
,D/TimaKeyStoreProvider(12468): TimaSignature is unavailable
,D/ActivityThread(12468): Added TimaKeyStore provider
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.521: (12023): KLMSIntentService(): listeningToPackageRemoved().END
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 392us total 16.046ms
,I/art     ( 2884): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 385us total 11.128ms
,E/Zygote  (12483): MountEmulatedStorage()
I/libpersona(12483): KNOX_SDCARD checking this for 10101
E/Zygote  (12483): v2
I/libpersona(12483): KNOX_SDCARD not a persona
,I/SELinux (12483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12483): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12483 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourceType( 3451): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider(12483): TimaSignature is unavailable
,I/KLMS-2.4.521: (12023): KLMSIntentService(): onDestroy()
D/ActivityThread(12483): Added TimaKeyStore provider
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(11513): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager(12483): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12453): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/ResourcesManager( 3451): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12468): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3451): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,W/ResourcesManager(12468): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/RCPManagerService( 3451): PackageReceiver onReceive()
I/HarmonyEASService( 3451): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ResourcesManager(12468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12468): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12468): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12468): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12468): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12468): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(11513): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/KnoxMUMContainerPolicy( 3451): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3451): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/JobSchedulerService( 3451): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 3451): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3451): uID is 10643
V/EnterpriseBillingPolicy( 3451): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3451): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3451): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3451): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3451): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3451): getBillingProfileForVpnEngine - start - com.test.thalitest
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 3451): getBillingProfileForVpnEngine - end - null
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3451): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/elm:14491(12453): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12453): ELMEngine.ELMEngine( context ).
D/elm:14491(12453): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3451): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (12499): MountEmulatedStorage()
E/Zygote  (12499): v2
I/libpersona(12499): KNOX_SDCARD checking this for 10183
I/libpersona(12499): KNOX_SDCARD not a persona
,I/SELinux (12499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3451): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12499 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/SELinux (12499): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Killing 11545:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/UsbSettingsManager( 3451): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3451): onPackageRemoved : com.test.thalitest
,D/elm:14491(12453): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/TaskPersister( 3451): removeObsoleteFile: deleting file=25_task.xml
,D/elm:14491(12453): ElmAgentService : onCreate()
,D/DocsApplication(12483): Installing DEX configuration.
,D/elm:14491(12453): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/elm:14491(12453): MainReceiver.listeningToPackageRemoved()
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/elm:14491(12453): MDMBridge.getInstance()
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/elm:14491(12453): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12453): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/TimaKeyStoreProvider(12499): TimaSignature is unavailable
,D/ActivityThread(12499): Added TimaKeyStore provider
,E/Zygote  (12517): MountEmulatedStorage()
,E/Zygote  (12517): v2
I/libpersona(12517): KNOX_SDCARD checking this for 10019
I/libpersona(12517): KNOX_SDCARD not a persona
,I/SELinux (12517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/BatteryService( 3451): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3451): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3451): online:4, current avg:-222, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-354
D/BatteryService( 3451): stay LED for fully charged
,I/ActivityManager( 3451): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12517 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/SELinux (12517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14491(12453): ElmAgentService : onDestroy().
,D/DexInstaller(12483): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12483): Provided clientMode=RELEASE, packageInfo=PackageInfo{3b7a156 com.google.android.apps.docs}
,D/TAG     (12483): onCreate()
,D/CrossAppStateProvider(12483): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager(11513): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,I/ActivityManager( 3451): Killing 11513:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12517): TimaSignature is unavailable
,D/ActivityThread(12517): Added TimaKeyStore provider
,D/ResourcesManager(12499): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(12517): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/SQLiteLog(12499): (284) automatic index on shooting_modes(title_id)
,D/BatteryService( 3451): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3451): Plugged
I/MotionRecognitionService( 3451): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,D/PackageManager( 3451): findPreferredActivity: No PreferredActivities set
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5617): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5617): Disconnected process message: 10
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12517): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12517): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12517): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3451): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/AndroidRuntime( 3451): *** FATAL EXCEPTION IN SYSTEM PROCESS: PackageManager
E/AndroidRuntime( 3451): java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
E/AndroidRuntime( 3451): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1463)
E/AndroidRuntime( 3451): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1610)
E/AndroidRuntime( 3451): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:1157)
E/AndroidRuntime( 3451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3451): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 3451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3451): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/Zygote  (12537): MountEmulatedStorage()
E/Zygote  (12537): v2
I/libpersona(12537): KNOX_SDCARD checking this for 10190
I/libpersona(12537): KNOX_SDCARD not a persona
,I/ActivityManager( 3451): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12537 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,I/SELinux (12537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  (12552): MountEmulatedStorage()
,E/Zygote  (12552): v2
I/libpersona(12552): KNOX_SDCARD checking this for 10022
I/libpersona(12552): KNOX_SDCARD not a persona
,I/SELinux (12552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3451): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12552 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3451): Killing 10941:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,E/SELinux (12552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Killing 11587:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12537): TimaSignature is unavailable
,D/ActivityThread(12537): Added TimaKeyStore provider
,D/UsbHostManager( 3451): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3451): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3451): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3451): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3451): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3451): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3451): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3451): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3451): usbDeviceRemoved : /dev/bus/usb/001/003
,E/UsbHostManager( 3451): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3451): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/UsbHostManager( 3451): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3451): displayNotification : [09h,00h,00h]
D/TimaKeyStoreProvider(12552): TimaSignature is unavailable
,D/NearbySource(12468): Nearby Source Create!
D/ActivityThread(12552): Added TimaKeyStore provider
D/NearbyContext(12468): Nearby Context Create!
,D/ResourcesManager(12537): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12468): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12468): Samsung link source created
,D/ResourcesManager(12552): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12552): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12537): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12537): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,E/SQLiteLog(12468): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12468): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12468): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12468): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12468): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12468): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12468): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12468): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12468): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12468): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12468): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12468): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12468): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12468): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12468): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12468): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12468): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12468): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12468): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12468): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12468): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12468): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12468): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12468): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12468): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12468): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12468): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12468): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12468): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12468): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12468): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12468): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12468): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12468): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12468): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12468): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12468): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12468): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12468): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12468): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12468): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12468): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12468): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/TapandpayWidget:Utils(12537): Clear T&P info.
W/SQLiteOpenHelper(12468): Opened local.db in read-only mode
,D/WifiDisplayAdapter( 3451): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12537): Widget is not attached.
,D/ContactProvider(12468): getAllContactInfoList Start
D/UsbHostManager( 3451): usbDeviceRemoved : /dev/bus/usb/001/001
,E/UsbHostManager( 3451): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/ActivityManager( 3451): Killing 10302:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/LocationWidgetApplication(12552): onCreate() : start
,D/LocationWidgetApplication(12552): countryCode = POLAND
,D/WifiDisplayAdapter( 3451): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/EventHub( 3451): Removing device '/dev/input/event10' due to inotify event
,D/PackageBroadcastService( 4762): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4762): Clearing selected account for com.test.thalitest
,I/EventHub( 3451): Removing device '/dev/input/event7' due to inotify event
I/PCWCLIENTTRACE_SYSTEMReceiver(11931): mConnectivityHandler : connected
,D/LocationManagerService( 3451): getProviders()=[]
D/LocationManagerService( 3451): getProviders()=[passive]
D/LocationManagerService( 3451): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12552): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12552): getLastUiLocationId() : mLastUiLocationId = -100
,E/SQLiteLog(12552): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12552): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12552): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12552): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12552): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12552): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12552): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12552): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12552): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12552): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12552): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12552): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12552): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12552): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12552): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12552): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12552): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12552): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12552): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12552): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(12552): Shutting down VM
,E/AndroidRuntime(12552): FATAL EXCEPTION: main
E/AndroidRuntime(12552): Process: com.sec.android.widgetapp.locationwidget, PID: 12552
E/AndroidRuntime(12552): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12552): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12552): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12552): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12552): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12552): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12552): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12552): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12552): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12552): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12552): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12552): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12552): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12552): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12552): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12552): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12552): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12552): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12552): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12552): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12552): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12552): 	... 9 more
,D/MtpClient(12468): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12468): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,W/PCWCLIENTTRACE_AccountUtil(11931): [hasSamungAccount] - No Samsung Account
,I/EventHub( 3451): Removing device '/dev/input/event8' due to inotify event
,E/SharedPreferencesImpl(12468): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,V/ApplicationPolicy( 3451): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,E/SQLiteLog( 4762): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4762): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 4762): disk I/O error (code 3850)
E/DriveAsyncService( 4762): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4762): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4762): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4762): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4762): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4762): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4762): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4762): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4762): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4762): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4762): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4762): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4762): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4762): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4762): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4762): 	at java.lang.Thread.run(Thread.java:818)
,I/EventHub( 3451): Removing device '/dev/input/event9' due to inotify event
,I/LocationSettingsChecker( 4762): Removing dialog suppression flag for package com.test.thalitest
,I/CSTORAGE(11931): ================================================
I/CSTORAGE(11931):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11931): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11931): [GetString-S]
E/art     (11931): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11931): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11931): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11931): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11931): sales region : global
I/PCWCLIENTTRACE_PushUtil(11931): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11931): [ensureRegistration] - No Samsung account
,I/PCWCLIENTTRACE_PushUtil(11931): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11931): sales region : global
I/PCWCLIENTTRACE_PushUtil(11931): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11931): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/SQLiteLog( 4762): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/DropBoxManagerService( 3451): Can't write: system_app_crash
E/DropBoxManagerService( 3451): java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3451): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3451): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3451): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3451): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3451): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3451): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3451): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3451): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3451): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3451): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3451): 	... 5 more
,E/SQLiteDatabase( 4762): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4762): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4762): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4762): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4762): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4762): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4762): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4762): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4762): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4762): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4762): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4762): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4762): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4762): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4762): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4762): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4762): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4762): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4762): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4762): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4762): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4762): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4762): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 4762): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 4762): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 4762): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4762): Process: com.google.android.gms, PID: 4762
E/AndroidRuntime( 4762): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4762): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4762): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4762): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4762): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4762): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4762): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4762): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4762): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4762): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3451): Removing device '/dev/input/event11' due to inotify event
,I/Process (12552): Sending signal. PID: 12552 SIG: 9
,E/SQLiteLog( 4762): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 4762): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 4762): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4762): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4762): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4762): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4762): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4762): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4762): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4762): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4762): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 4762): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 4762): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
,E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 4762): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 4762): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4762): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 4762): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 4762): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4762): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4762): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4762): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 4762): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 4762): Runtime exception while performing operation
E/ClearPendingStateOp( 4762): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4762): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4762): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
,E/ClearPendingStateOp( 4762): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4762): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 4762): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4762): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4762): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 4762): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4762): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4762): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4762): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4762): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4762): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4762): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 4762): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4762): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4762): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4762): 	,at java.lang.Thread.run(Thread.java:818)
I/EventHub( 3451): Removing device '/dev/input/event12' due to inotify event
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4762): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4762): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 4762): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 4762): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,I/EventHub( 3451): Removing device '/dev/input/event13' due to inotify event
,E/Zygote  (12587): MountEmulatedStorage()
E/Zygote  (12587): v2
I/libpersona(12587): KNOX_SDCARD checking this for 10052
I/libpersona(12587): KNOX_SDCARD not a persona
,I/SELinux (12587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12587): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3451): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12587 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/EventHub( 3451): Removing device '/dev/input/event14' due to inotify event
,I/ActivityManager( 3451): Process com.sec.android.widgetapp.locationwidget (pid 12552)(adj 9) has died(275,1162)
V/ApplicationPolicy( 3451): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 4762): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4762): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/Process ( 4762): Sending signal. PID: 4762 SIG: 9
,E/JavaBinder( 3451): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3451): Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
W/BroadcastQueue( 3451): android.os.TransactionTooLargeException
W/BroadcastQueue( 3451): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3451): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3451): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3451): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3451): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3451): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3451): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3451): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3451): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager( 3451): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager( 3451): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
,W/ActivityManager( 3451): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
W/ActivityManager( 3451): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20999ms
,W/ActivityManager( 3451): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30998ms
W/ActivityManager( 3451): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 40997ms
,E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3451): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12587): TimaSignature is unavailable
,D/ActivityThread(12587): Added TimaKeyStore provider
,E/SQLiteLog(12483): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)

```
