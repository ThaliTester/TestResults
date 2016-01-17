#### Test 561510933390750_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 272, CUR = 40
D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/BatteryService( 3523): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5628): Disconnected process message: 10
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11791): 
D/AndroidRuntime(11791): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11791): CheckJNI is OFF
D/AndroidRuntime(11791): readGMSProperty: start
D/AndroidRuntime(11791): readGMSProperty: already setted!!
D/AndroidRuntime(11791): readGMSProperty: end
D/AndroidRuntime(11791): addProductProperty: start
E/AffinityControl(11791): AffinityControl: registerfunction enter
D/AndroidRuntime(11791): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11809): MountEmulatedStorage()
I/libpersona(11809): KNOX_SDCARD checking this for 10578
E/Zygote  (11809): v2
I/libpersona(11809): KNOX_SDCARD not a persona
I/SELinux (11809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11809 uid=10578 gids={50578, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11809): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11791): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11809): TimaSignature is unavailable
D/ActivityThread(11809): Added TimaKeyStore provider
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3523): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3523): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(11809): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{a48e1f7 token=android.os.BinderProxy@288f056 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
,I/WebViewFactory(11809): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11809): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11809): Loading: webviewchromium
,I/LibraryLoader(11809): Time to load native libraries: 7 ms (timestamps 5594-5601)
,I/LibraryLoader(11809): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11809): Binding Chromium to main looper Looper (main, tid 1) {3b4d845a}
,I/LibraryLoader(11809): Expected native library version number "",actual native library version number ""
,I/chromium(11809): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11809): Initializing chromium process, renderers=0
,W/art     (11809): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11809): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11809): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11809): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11809): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11809): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11809): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11809): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11809): CordovaWebView is running on device made by: samsung
,W/art     (11809): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11809): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11809): performCreate Call secproduct feature valuefalse
D/Activity(11809): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11809): Render dirty regions requested: true
,W/ActivityManager( 3523): Activity pause timeout for ActivityRecord{2ad489bf u0 com.test.thalitest/.MainActivity t25}
,D/ActivityManager( 3523): post active user change for 0
,D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11809): Initialized EGL, version 1.4
,I/OpenGLRenderer(11809): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278648048 
,D/OpenGLRenderer(11809): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11809): Enabling debug mode 0
,D/mali_winsys(11809): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11809): updateVisibility : ActivityRecord{2fbfb80a token=android.os.BinderProxy@1f7be449 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{2ad489bf u0 com.test.thalitest/.MainActivity t25} time:136013
,W/IInputConnectionWrapper(11809): showStatusIcon on inactive InputConnection
,I/Timeline(11809): Timeline: Activity_idle id: android.os.BinderProxy@1f7be449 time:136018
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/JsMessageQueue(11809): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11809): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11809): 
,D/jxcore_app_log(11809): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361664256
D/JX-Cordova(11809): jxcore cordova android initializing
,W/jxcore-log(11809): Initializing JXcore engine
W/jxcore-log(11809): JXcore engine is ready
W/jxcore-log(11809): Starting JXcore engine
E/auditd  ( 4616): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
W/jxcore-log(11809): Platform android
W/jxcore-log(11809): 
W/jxcore-log(11809): Process ARCH arm
W/jxcore-log(11809): 
,I/jxcore-log(11809): JXcore Cordova bridge is ready!
I/jxcore-log(11809): 
W/jxcore-log(11809): JXcore engine is started
,I/jxcore-log(11809): Toggling radios to true
I/jxcore-log(11809): 
,D/BluetoothAdapter(11809): enable()
,D/BluetoothAdapter(11809): enable(): BT is already enabled..!
,D/WifiService( 3523): New client listening to asynchronous messages
,I/WifiManager(11809): packageName : com.test.thalitest
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: true pid=11809, uid=10578
E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=11809, uid=10578 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): Failed getting userId using ActivityManagerNative
W/WifiService( 3523): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11809, uid=10578 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3523): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3523): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3523): name = wifi_on
I/WifiService( 3523): disconnect: pid=11809, uid=10578
I/wpa_supplicant( 3822): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11809): Radios toggled
I/jxcore-log(11809): 
,I/jxcore-log(11809): My device name is: samsung-SM-N910C
I/jxcore-log(11809): 
,I/wpa_supplicant( 3822): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3822): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3822): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3822): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3822): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3822): Disconnected - do not scan
I/wpa_supplicant( 3822): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/Hs20UtilService( 4070): Starting #8
,E/WifiStateMachine( 3523): Start Disconnecting Watchdog 1
I/Hs20UtilService( 4070): Message received 5007
I/wpa_supplicant( 3822): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3822): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3822): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3822): First Scan Start
,E/WifiStateMachine( 3523): ConnectModeState: Network connection lost 
I/wpa_supplicant( 3822): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/NearbySettings( 8839): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8839): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8839): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,V/NearbySettings( 8839): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8839): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8839): MountReceiver.mPrefHandler - 7002
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 3982): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SignOutReceiver( 9387): NETWORK_STATE_CHANGED_ACTION
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - currTime: 1453032878301
D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering( 3523): MasterInitialState.processMessage what=3
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
V/NetworkStats( 3523): performPollLocked() took 5ms
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/Hs20UtilService( 4070): Starting #9
,I/Hs20UtilService( 4070): Message received 5007
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NearbySettings( 8839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8839): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8839): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8839): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver( 9387): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3982): FileWriteThread : threadType = 3
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3523): updateDataUsageMap
,I/ApplicationPolicy( 3523): updateDataUsageMap  idList is null 
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3523): No Active Data Connection
,I/DBG_DM  ( 6311): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6311): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11914): MountEmulatedStorage()
E/Zygote  (11914): v2
I/libpersona(11914): KNOX_SDCARD checking this for 1000
I/libpersona(11914): KNOX_SDCARD not a persona
,I/SELinux (11914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11914): TimaSignature is unavailable
,D/ActivityThread(11914): Added TimaKeyStore provider
,D/ResourcesManager(11914): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11914): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11914): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11914): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11914): noConnectivity : true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11930): MountEmulatedStorage()
E/Zygote  (11930): v2
I/libpersona(11930): KNOX_SDCARD checking this for 10135
I/libpersona(11930): KNOX_SDCARD not a persona
,I/SELinux (11930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11930): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11930 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11930): TimaSignature is unavailable
,D/ActivityThread(11930): Added TimaKeyStore provider
,D/ResourcesManager(11930): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11930): Database version: 104
,D/ResourcesManager(11930): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11930): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11930): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11930): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34234c0e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11930): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11930): GMSCore installation verified
,I/ConfigStore(11930): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11930): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3523): getStreamVolume 3 index 0
,I/MediaRouter(11930): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11955): MountEmulatedStorage()
I/libpersona(11955): KNOX_SDCARD checking this for 10002
E/Zygote  (11955): v2
I/libpersona(11955): KNOX_SDCARD not a persona
,I/SELinux (11955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11955 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11930): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 3523): Killing 11014:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11955): TimaSignature is unavailable
,D/ActivityThread(11955): Added TimaKeyStore provider
,D/ResourcesManager(11955): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3523): Killing 11032:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11974): MountEmulatedStorage()
I/libpersona(11974): KNOX_SDCARD checking this for 1000
E/Zygote  (11974): v2
I/libpersona(11974): KNOX_SDCARD not a persona
,I/SELinux (11974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11974): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11974 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11974): TimaSignature is unavailable
,D/ActivityThread(11974): Added TimaKeyStore provider
,D/ResourcesManager(11974): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11974): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11974): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11974): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11990): MountEmulatedStorage()
E/Zygote  (11990): v2
I/libpersona(11990): KNOX_SDCARD checking this for 10012
I/libpersona(11990): KNOX_SDCARD not a persona
,I/SELinux (11990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11990): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11990 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 8757(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 715us total 10.160ms
,I/wpa_supplicant( 3822): nl80211: Received scan results (5 BSSes)
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 390us total 8.281ms
,I/wpa_supplicant( 3822): wlan0: Setting scan request: 8 sec 0 usec
,D/TimaKeyStoreProvider(11990): TimaSignature is unavailable
E/WifiStateMachine( 3523): [1,453,032,879,363 ms] noteScanEnd no scan source
D/ActivityThread(11990): Added TimaKeyStore provider
,I/wpa_supplicant( 3822): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3822): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.002ms total 9.227ms
,E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@8a58ec2 sup_state=SCANNING debouncing=false
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/ResourcesManager(11990): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3523): Killing 11057:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11990): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12006): MountEmulatedStorage()
E/Zygote  (12006): v2
I/libpersona(12006): KNOX_SDCARD checking this for 10021
I/libpersona(12006): KNOX_SDCARD not a persona
,I/SELinux (12006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12006): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12006 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10306:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12006): TimaSignature is unavailable
,D/ActivityThread(12006): Added TimaKeyStore provider
,I/wpa_supplicant( 3822): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3822): Associated with C0.AA.48
,D/ResourcesManager(12006): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:14:39 GMT+01:00 2016
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12006): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/wpa_supplicant( 3822): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/KLMS-2.4.521: (12006): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/wpa_supplicant( 3822): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3822): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3822): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3822): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/KLMS-2.4.521: (12006): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/wpa_supplicant( 3822): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3822): Blacklist: Clear (temp) 
I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/KLMS-2.4.521: (12006): StateImplV2(): networkChangeListener().END
,E/Zygote  (12023): MountEmulatedStorage()
I/libpersona(12023): KNOX_SDCARD checking this for 10038
E/Zygote  (12023): v2
I/libpersona(12023): KNOX_SDCARD not a persona
I/SELinux (12023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12023 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onDestroy()
,E/WifiStateMachine( 3523): Network connection established
I/ActivityManager( 3523): Killing 9489:com.android.mms/u0a52 (adj 13): bgCount ##31
D/WifiNative-HAL( 3523): callSECApiVoid - ID [50]
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,D/TimaKeyStoreProvider(12023): TimaSignature is unavailable
,E/WifiStateMachine( 3523): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/ActivityThread(12023): Added TimaKeyStore provider
,D/ConnectivityService( 3523): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 3523): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3523): updateNetworkInfo()
E/WifiStateMachine( 3523): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3523): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3523): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ResourcesManager(12023): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3523): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SO_AGENT(12023): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/CountryDetector( 3523): No listener is left
,E/Zygote  (12040): MountEmulatedStorage()
I/libpersona(12040): KNOX_SDCARD checking this for 1000
E/Zygote  (12040): v2
I/libpersona(12040): KNOX_SDCARD not a persona
I/SELinux (12040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12040): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12040 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11105:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12040): TimaSignature is unavailable
,D/ActivityThread(12040): Added TimaKeyStore provider
,D/ResourcesManager(12040): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 3523): mCursor = null
,E/Zygote  (12060): MountEmulatedStorage()
I/libpersona(12060): KNOX_SDCARD checking this for 10039
E/Zygote  (12060): v2
I/libpersona(12060): KNOX_SDCARD not a persona
,I/SELinux (12060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12060): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12060 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11125:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12060): TimaSignature is unavailable
,D/ActivityThread(12060): Added TimaKeyStore provider
,D/ResourcesManager(12060): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12060): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12060): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(12060): PushLog.txt file is not deleted.
D/SPPClientService(12060): PushLog.txt file is not deleted.
D/SPPClientService(12060): ============PushLog. stop!
,E/SPPClientService(12060): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12077): MountEmulatedStorage()
I/libpersona(12077): KNOX_SDCARD checking this for 10045
E/Zygote  (12077): v2
I/libpersona(12077): KNOX_SDCARD not a persona
I/SELinux (12077): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12077): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12077): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12077 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11143:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,E/SPPClientService(12060): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider(12077): TimaSignature is unavailable
D/ActivityThread(12077): Added TimaKeyStore provider
,D/ResourcesManager(12077): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12077): [SSP] onCreated
,I/SA      (12077): [TPM] There is no property file
,I/SA      (12077): [SCU] isHaveSA() - false
,I/SA      (12077): [TPM] getModelProperty : null
I/SA      (12077): [TPM] getCSCProperty : null
,I/SA      (12077): [DM] init START
,I/SA      (12077): [DM] This device is not a Vodafone
,I/SA      (12077): checkReactivationActive for LOLLIPOP
,I/SA      (12077): checkReactivationActive for reactiveActive
I/SA      (12077): setSupportRL : true
,I/SA      (12077): [SCU] isHaveSA() - false
I/SA      (12077): support phone number id : false
,I/SA      (12077): [DM] init END
I/SA      (12077): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12077): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12077): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12077): [SLFUCHKMGR] constructor called
,I/SA      (12077): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12077): [OR] == isSIMCardReady false ==
,I/SA      (12077): [SCU] == networkStateCheck == false
I/SA      (12077): [OR] onReceive END
,I/ActivityManager( 3523): Killing 11159:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12098): MountEmulatedStorage()
I/libpersona(12098): KNOX_SDCARD checking this for 10067
E/Zygote  (12098): v2
I/libpersona(12098): KNOX_SDCARD not a persona
,I/SELinux (12098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12098): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12098 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12098): TimaSignature is unavailable
,D/ActivityThread(12098): Added TimaKeyStore provider
,D/ResourcesManager(12098): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,E/dhcpcd  (12113): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12113): version 5.5.6 starting
,E/dhcpcd  (12113): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/sCloudBackupApp(12098): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12098): Other Intent
,I/ActivityManager( 3523): Killing 11204:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/accuweather( 5228): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/dhcpcd  (12113): wlan0: sending IPv6 Router Solicitation
D/accuweather( 5228): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5228): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5228): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
E/dhcpcd  (12113): wlan0: sendmsg: Cannot assign requested address
D/accuweather( 5228): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
I/dhcpcd  (12113): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12113): bssid match
I/dhcpcd  (12113): wlan0: rebinding lease of 192.168.1.124
,D/accuweather( 5228): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12121): MountEmulatedStorage()
E/Zygote  (12121): v2
I/libpersona(12121): KNOX_SDCARD checking this for 1000
I/libpersona(12121): KNOX_SDCARD not a persona
,I/SELinux (12121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12121 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12121): TimaSignature is unavailable
,D/ActivityThread(12121): Added TimaKeyStore provider
,D/ResourcesManager(12121): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12121): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12121): premStatus:2
,I/KnoxUsageLogPro(12121): isEulaShown : false
I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12136): MountEmulatedStorage()
I/libpersona(12136): KNOX_SDCARD checking this for 10090
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD not a persona
I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12136 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11182:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ActivityThread(12136): Added TimaKeyStore provider
,D/ResourcesManager(12136): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12152): MountEmulatedStorage()
E/Zygote  (12152): v2
I/libpersona(12152): KNOX_SDCARD checking this for 10127
I/libpersona(12152): KNOX_SDCARD not a persona
,I/SELinux (12152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12152 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11252:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12152): TimaSignature is unavailable
,D/ActivityThread(12152): Added TimaKeyStore provider
,D/ResourcesManager(12152): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12152): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12152): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12152): stopCheckCategoryVersion
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12169): MountEmulatedStorage()
,E/Zygote  (12169): v2
I/libpersona(12169): KNOX_SDCARD checking this for 10136
I/libpersona(12169): KNOX_SDCARD not a persona
I/SELinux (12169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12169 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12169): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Killing 11269:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12169): TimaSignature is unavailable
,D/ActivityThread(12169): Added TimaKeyStore provider
I/jxcore-log(11809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11809): 
,I/jxcore-log(11809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11809): 
,D/ResourcesManager(12169): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/jxcore-log(11809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11809): 
,I/jxcore-log(11809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11809): 
,I/dhcpcd  (12113): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/jxcore-log(11809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11809): 
,I/jxcore-log(11809): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11809): 
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12169): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/dhcpcd  (12113): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/WebViewFactory(12169): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12169): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12169): Loading: webviewchromium
,I/LibraryLoader(12169): Time to load native libraries: 3 ms (timestamps 9591-9594)
I/LibraryLoader(12169): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12169): Binding Chromium to main looper Looper (main, tid 1) {1bcc1b1a}
,I/LibraryLoader(12169): Expected native library version number "",actual native library version number ""
,I/chromium(12169): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12169): Initializing chromium process, renderers=0
,W/art     (12169): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12169): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12169): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12169): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12169): Requires BLUETOOTH permission
,I/NSApplication(12169): Starting up...
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12258): MountEmulatedStorage()
E/Zygote  (12258): v2
I/libpersona(12258): KNOX_SDCARD checking this for 10150
I/libpersona(12258): KNOX_SDCARD not a persona
,I/SELinux (12258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12258 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11237:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 529us total 10.129ms
,D/TimaKeyStoreProvider(12258): TimaSignature is unavailable
,D/ActivityThread(12258): Added TimaKeyStore provider
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 268us total 8.533ms
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 450us total 8.957ms
,D/ResourcesManager(12258): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12258): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12258): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12258): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12258): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12258): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12273): MountEmulatedStorage()
E/Zygote  (12273): v2
I/libpersona(12273): KNOX_SDCARD checking this for 10178
I/libpersona(12273): KNOX_SDCARD not a persona
,I/SELinux (12273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12273 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux (12273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11286:com.samsung.helphub/1000 (adj 13): bgCount ##31
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3523): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3523): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3523): Not connected state, yet.
E/WifiStateMachine( 3523): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3523): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/TimaKeyStoreProvider(12273): TimaSignature is unavailable
D/WifiStateMachine( 3523): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3523): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3523): callSECApiInt - ID [210]
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/ActivityThread(12273): Added TimaKeyStore provider
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3523): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3523): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3523): Now, connected state.
E/WifiStateMachine( 3523): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3523): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService( 3523): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/ConnectivityService( 3523): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ResourcesManager(12273): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ConnectivityService( 3523): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3523): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,W/ResourcesManager(12273): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12273): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12273): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12273): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(12273): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3523): callSECApiVoid - ID [212]
E/WifiStateMachine( 3523): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/jxcore-log(11809): Test app app.js loaded
I/jxcore-log(11809): 
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,I/chromium(11809): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,V/        ( 2845): QcRouteController
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/ConnectivityService( 3523): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3523): LTETest block dns file not exists
,E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3523):    accepting network in place of null
,E/CSLegacyTypeTracker( 3523): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3523): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/TelephonyNetworkFactory( 3982): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3523): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3523): MasterInitialState.processMessage what=3
,D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
I/chromium(11809): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524290
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/NetworkStats( 3523): updateIfacesLocked()
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked(flags=0x1)
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
V/NetworkStats( 3523): performPollLocked() took 7ms
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/libpersona(12315): KNOX_SDCARD checking this for 10082
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
I/libpersona(12315): KNOX_SDCARD not a persona
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
E/Zygote  (12315): MountEmulatedStorage()
E/Zygote  (12315): v2
I/SELinux (12315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12315): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12315 uid=10082 gids={50082, 9997} abi=armeabi-v7a
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/RCPManagerService( 3523): exchangeData() failure , invalid userId
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12315): TimaSignature is unavailable
D/ActivityThread(12315): Added TimaKeyStore provider
E/Zygote  (12330): MountEmulatedStorage()
I/libpersona(12330): KNOX_SDCARD checking this for 1000
E/Zygote  (12330): v2
I/libpersona(12330): KNOX_SDCARD not a persona
I/SELinux (12330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12330 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11301:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
I/ActivityManager( 3523): Killing 11386:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/ResourcesManager(12315): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12315): onCreate
D/BadgeProvider(12315): DatabaseHelper
,D/TimaKeyStoreProvider(12330): TimaSignature is unavailable
D/ActivityThread(12330): Added TimaKeyStore provider
,I/System.out( 3523): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 12:14:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453032880696], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453032880676]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Don't send network conditions - lacking user consent.
D/ConnectivityService( 3523): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 85034(4MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 1.197ms total 82.482ms
,D/ResourcesManager(12330): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12315): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12315): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12315): sendNotify, [notify] : null
D/BadgeProvider(12315): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12315): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12315): update, [UpdateCount] : 1
I/ActivityManager( 3523): Killing 11403:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/Launcher.Model( 4000): reloadBadges entered.
,D/WaitQueueForNetworkActivate(11525): notifyNetworkActivated
,W/ContextImpl(11525): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (11525): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11525): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11525): exit::IDLE
D/InitializeManagerStateMachine(11525): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11525): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11525): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11525): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11525): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11525): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11525): entry::SUCCESS
D/hcjo    (11525): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11525): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11525): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/Hs20UtilService( 4070): Starting #10
D/InitializeManagerStateMachine(11525): exit::SUCCESS
D/InitializeManagerStateMachine(11525): entry::IDLE
,I/Hs20UtilService( 4070): Message received 5007
,D/NearbySettings( 8839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8839): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8839): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver( 9387): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4070): Starting #11
,I/Hs20UtilService( 4070): Message received 5007
,D/NearbySettings( 8839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8839): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver( 9387): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4070): Starting #12
,I/Hs20UtilService( 4070): Message received 5007
,D/NearbySettings( 8839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8839): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8839): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8839): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver( 9387): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4070): Starting #13
,I/Hs20UtilService( 4070): Message received 5007
,D/NearbySettings( 8839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8839): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3523): callSECApi what=220
D/WifiStateMachine( 3523): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver( 9387): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3523): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3523): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6311): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6311): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5343): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5343): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor(11930): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11974): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11990): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11990): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:14:41 GMT+01:00 2016
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12006): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12006): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(12023): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12006): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12006): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12006): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12006): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12006): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onDestroy()
,E/SPPClientService(12060): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12077): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12077): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12077): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12077): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12077): [OR] == isSIMCardReady false ==
,I/SA      (12077): [SCU] == networkStateCheck == true
,I/SA      (12077): [DM] getCountryCodeFromCSC : PL
I/SA      (12077): isChinaCountryCode : false
I/SA      (12077): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12077): [OR] == networkStateCheck true ==
,I/SA      (12077): [OR] GetMyCountryZoneTask
,I/SA      (12077): [OR] onReceive END
,I/SA      (12077): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12077): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12077): [SSP] query invoked
,I/SCloudBackupReceiver(12098): Other Intent
,I/SA      (12077): [TPMU] GetMccFromDB : null
,D/accuweather( 5228): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      (12077): [SCU] getMccFromPreferece mcc = 260
,I/SA      (12077): [TPM] isNoProxy(default) : true
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5228): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5228): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5228): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5228): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12121): premStatus:2
,I/KnoxUsageLogPro(12121): isEulaShown : false
I/KnoxUsageLogPro(12121): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12152): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12152): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12152): stopCheckCategoryVersion
,D/QuickConnect(12258): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12258): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12258): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/hcjo    (11525): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(11525): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(11525): exit::IDLE
D/InitializeManagerStateMachine(11525): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(11525): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(11525): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(11525): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11525): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(11525): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(11525): entry::SUCCESS
D/hcjo    (11525): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (11525): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (11525): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(11525): exit::SUCCESS
D/InitializeManagerStateMachine(11525): entry::IDLE
,D/ConnectivityService( 3523): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (12077): [RC New] Execute method=[GET] start
,I/SA      (12077): [RC New] Security=[true]
,I/System.out(12077): Thread-1685(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12077): Thread-1685(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12077): Thread-1685(ApacheHTTPLog):isShipBuild true
I/System.out(12077): Thread-1685(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/SA      (12077): [RC New] [v2liruge] api execute + 699
,I/SA      (12077): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12077): AsyncTask #1 calls detatch()
,I/SA      (12077): [TPMU] getNetworkMcc : 
,I/SA      (12077): [SCU] saveMccToPreferece Start
,I/SA      (12077): [SCU] RegionMCC : 260
,I/SA      (12077): [SSP] query invoked
,I/SA      (12077): [TPMU] GetMccFromDB : null
,I/SA      (12077): [SCU] getMccFromPreferece mcc = 260
,I/SA      (12077): [SCU] saveMccToPreferece End
,I/SA      (12077): [RC New] executeRequest [v2liruge] end. 759
,I/SA      (12077): [RC New] Execute end
,I/SA      (12077): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (12077): [OR] GetMyCountryZoneTask Success
,I/ActivityManager( 3523): Killing 11420:com.facebook.system/u0a10 (adj 13): bgCount ##31
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON,
,E/WifiStateMachine( 3523): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  (12113): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12113): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 4637): callingUid 10014, callindPid: 4637
,D/ResourcesManager(11930): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11930): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11930): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11930): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11930): Conditions not met for autocaching.
I/MusicLeanback(11930): Stop autocaching.
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11930): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11930): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11930): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11930): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3332ece8 that was originally bound here
E/ActivityThread(11930): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3332ece8 that was originally bound here
E/ActivityThread(11930): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11930): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11930): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11930): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11930): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11930): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11930): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11930): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11930): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11930): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11930): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11930): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11930): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11930): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11930): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11930): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11930): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11930): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11930): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11930): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3523): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3523) eventTime = 143726
,D/PowerManagerService( 3523): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523 (0x0)
D/PowerManagerService( 3523): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3523, ws=WorkSource{10060}) (elapsedTime=3490)
,D/SSRM:n  ( 3523): SIOP:: AP = 280, PST = 271, CUR = 60
,I/PowerManagerService( 3523): [PWL] Off : 50s ago
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2845): QcRouteController
,E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getSBEnabled() enabled =false
,V/        ( 2845): QcRouteController
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
,D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524295
,D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-86, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:83
D/BatteryService( 3523): stay LED for fully charged
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/ConnectivityManager.CallbackHandler( 6800): CM callback handler got msg 524295
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GAV4    (12169): Thread[GAThread,5,main]: No campaign data found.
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11914): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11914): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11914): ================================================
I/CSTORAGE(11914):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11914): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11914): [GetString-S]
E/art     (11914): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11914): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11914): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11914): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12113): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3523): Skipping unknown process pid 12465
,D/PreloadUpdateManagerStateMachine(11525): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11525): exit::IDLE
,D/PreloadUpdateManagerStateMachine(11525): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11525): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (11525): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine(11525): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11525): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(11525): entry::IDLE
,D/PreloadUpdateManagerStateMachine(11525): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(11525): exit::IDLE
,D/PreloadUpdateManagerStateMachine(11525): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (11525): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(11525): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(11525): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(11525): entry::IDLE
,I/dhcpcd  (12113): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12113): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 267, CUR = -86
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:73
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3523): Waited long enough for: ServiceRecord{62ae86b u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,V/AlarmManager( 3523): waitForAlarm result :8
,E/Watchdog( 3523): !@Sync 5
,D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 265, CUR = 12
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 75s ago
,I/art     ( 4637): Explicit concurrent mark sweep GC freed 74731(4MB) AllocSpace objects, 36(1559KB) LOS objects, 34% free, 30MB/46MB, paused 1.912ms total 63.082ms
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 264, CUR = 45
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:66
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4637): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 261, CUR = 50
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 6
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 259, CUR = 52
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3523): [PWL] Off : 105s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 250, PST = 257, CUR = 51
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 256, CUR = 49,
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3523): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3523): !@Sync 7
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 255, CUR = 45
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/BatteryService( 3523): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 254, CUR = 44
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 252, CUR = 41
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3523): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
,I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3523): !@Sync 8
,D/SSRM:n  ( 3523): SIOP:: AP = 240, PST = 251, CUR = 40
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged,
I/MotionRecognitionService( 3523): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5628): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11809): --= Surplus to requirements =--
I/jxcore-log(11809): 
I/jxcore-log(11809): ****TEST TOOK:  ms ****
I/jxcore-log(11809): 
I/jxcore-log(11809): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11809): 
,I/MMD     ( 2874): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AndroidRuntime(12624): 
D/AndroidRuntime(12624): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12624): CheckJNI is OFF
,D/AndroidRuntime(12624): readGMSProperty: start
D/AndroidRuntime(12624): readGMSProperty: already setted!!
,D/AndroidRuntime(12624): readGMSProperty: end
D/AndroidRuntime(12624): addProductProperty: start
,E/AffinityControl(12624): AffinityControl: registerfunction enter
,D/AndroidRuntime(12624): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3523): START PACKAGE DELETE: observer{173067815}
D/PackageManager( 3523): pkg{<packageName>}
D/PackageManager( 3523): user{0}
D/PackageManager( 3523): caller{2000}
D/PackageManager( 3523): flags{3}
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3523): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3523): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3523): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3523): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3523): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3523): !@killApplicatoin: 10578, uninstall pkg
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10578 user=-1: uninstall pkg
,I/ActivityManager( 3523): Killing 11809:com.test.thalitest/u0a578 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{2ad489bf u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3523): Skipping PackageSetting{34070926 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10578 user=0: pkg removed
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 9387): Explicit concurrent mark sweep GC freed 1603(93KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 1.041ms total 34.353ms
,D/WifiService( 3523): Client connection lost with reason: 4
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 9082): Explicit concurrent mark sweep GC freed 24484(1438KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 4.587ms total 63.543ms
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 2387(106KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.712ms total 55.873ms
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4504): mOCRHelper is null
,W/GeofencerStateMachine( 4637): Ignoring removeGeofence because network location is disabled.
,I/art     ( 6800): Explicit concurrent mark sweep GC freed 7757(329KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.635ms total 86.661ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/LWLocationManager(11542): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(11542): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (12642): MountEmulatedStorage()
E/Zygote  (12642): v2
I/libpersona(12642): KNOX_SDCARD checking this for 10063
I/libpersona(12642): KNOX_SDCARD not a persona
,I/SELinux (12642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12642 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12642): TimaSignature is unavailable
,D/ActivityThread(12642): Added TimaKeyStore provider
W/ResourceType( 5343): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5343): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(12642): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12642): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12642): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12642): packagename:com.test.thalitest
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 48224(3MB) AllocSpace objects, 43(688KB) LOS objects, 24% free, 49MB/65MB, paused 2.491ms total 196.673ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3523): WaitForGcToComplete blocked for 193.562ms for cause Explicit
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:16:37 GMT+01:00 2016
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (12006): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onCreate()
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12006): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,I/KLMS-2.4.521: (12006): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/Zygote  (12660): MountEmulatedStorage()
E/Zygote  (12660): v2
I/libpersona(12660): KNOX_SDCARD checking this for 10106
I/libpersona(12660): KNOX_SDCARD not a persona
,I/SELinux (12660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12660 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12006): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12006): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12006): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12006): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/RCPManager(12121):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3523):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,E/Zygote  (12675): MountEmulatedStorage()
E/Zygote  (12675): v2
I/libpersona(12675): KNOX_SDCARD checking this for 10050
I/libpersona(12675): KNOX_SDCARD not a persona
,I/SELinux (12675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(11542): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SELinux (12675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12675 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12660): TimaSignature is unavailable
,D/ActivityThread(12660): Added TimaKeyStore provider
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  (12691): MountEmulatedStorage()
,E/Zygote  (12691): v2
I/libpersona(12691): KNOX_SDCARD checking this for 10101
D/ResourcesManager(11542): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/libpersona(12691): KNOX_SDCARD not a persona
,I/SELinux (12691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TimaKeyStoreProvider(12675): TimaSignature is unavailable
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ActivityThread(12675): Added TimaKeyStore provider
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux (12691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12691): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12691 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11542): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11542): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11542): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11542): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 10124(635KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.608ms total 175.873ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/RegisteredServicesCache( 3966): empty dynamic service
,I/KLMS-2.4.521: (12006): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12691): TimaSignature is unavailable
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread(12691): Added TimaKeyStore provider
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12660): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/Zygote  (12706): MountEmulatedStorage()
I/libpersona(12706): KNOX_SDCARD checking this for 10183
E/Zygote  (12706): v2
I/libpersona(12706): KNOX_SDCARD not a persona
I/SELinux (12706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux (12706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12706 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager(12675): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ResourcesManager(12675): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12675): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12675): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12675): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12675): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12675): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12675): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12675): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PackageManager( 3523): delete codoeFile: 
,D/ResourcesManager(11542): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/TimaKeyStoreProvider(12706): TimaSignature is unavailable
I/KLMS-2.4.521: (12006): KLMSIntentService(): onDestroy()
D/ActivityThread(12706): Added TimaKeyStore provider
,I/AASAUninstall( 3523):  com.test.thalitest not target!
D/PackageManager( 3523): result of delete: 1{173067815}
,D/elm:14491(12660): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12660): ELMEngine.ELMEngine( context ).
,I/ActivityManager( 3523): Killing 11561:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/AndroidRuntime(12624): Shutting down VM
,D/elm:14491(12660): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(12691): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/elm:14491(12660): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/elm:14491(12660): ElmAgentService : onCreate()
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12660): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12660): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12660): MDMBridge.getInstance()
D/elm:14491(12660): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/elm:14491(12660): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(12706): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/Zygote  (12724): MountEmulatedStorage()
E/Zygote  (12724): v2
I/libpersona(12724): KNOX_SDCARD checking this for 10019
I/libpersona(12724): KNOX_SDCARD not a persona
,I/SELinux (12724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SELinux (12724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12724 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (12724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(12660): ElmAgentService : onDestroy().
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/ActivityManager( 3523): Killing 11582:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
E/SQLiteLog(12706): (284) automatic index on shooting_modes(title_id)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/DocsApplication(12691): Installing DEX configuration.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DexInstaller(12691): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/PackageInfoHelper(12691): Provided clientMode=RELEASE, packageInfo=PackageInfo{22e09813 com.google.android.apps.docs}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/TAG     (12691): onCreate()
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/CrossAppStateProvider(12691): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(12724): TimaSignature is unavailable
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ActivityThread(12724): Added TimaKeyStore provider
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,E/Zygote  (12742): MountEmulatedStorage()
E/Zygote  (12742): v2
I/libpersona(12742): KNOX_SDCARD checking this for 10190
I/libpersona(12742): KNOX_SDCARD not a persona
,D/RCPManagerService( 3523): PackageReceiver onReceive()
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux (12742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10578
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.test.thalitest
I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12742 uid=10190 gids={50190, 9997} abi=armeabi-v7a
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(11542): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(11542): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=25_task.xml
I/CrashAnrDetector( 3523): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3523): clearDefaults: com.test.thalitest
,I/ActivityManager( 3523): Killing 11542:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,D/ResourcesManager(12724): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/TimaKeyStoreProvider(12742): TimaSignature is unavailable
,D/ActivityThread(12742): Added TimaKeyStore provider
,D/PackageManager( 3523): findPreferredActivity: No PreferredActivities set
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12724): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12724): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12724): onReceive() : package name is not s health. Return !!!
,I/ActivityManager( 3523): Killing 10883:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/ResourcesManager(12742): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12742): onReceive()
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12742): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(12742): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12742): Widget is not attached.
,I/ActivityManager( 3523): Killing 11471:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/NearbySource(12675): Nearby Source Create!
D/NearbyContext(12675): Nearby Context Create!
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12675): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12675): Samsung link source created
,I/PCWCLIENTTRACE_PushUtil(11914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11914): sales region : global
I/PCWCLIENTTRACE_PushUtil(11914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11914): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/PackageBroadcastService( 6800): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6800): Clearing selected account for com.test.thalitest
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Zygote  (12761): MountEmulatedStorage()
E/Zygote  (12761): v2
I/libpersona(12761): KNOX_SDCARD checking this for 10035
I/libpersona(12761): KNOX_SDCARD not a persona
,I/SELinux (12761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12761): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12761 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12761): TimaSignature is unavailable
,D/ActivityThread(12761): Added TimaKeyStore provider
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.284ms total 31.970ms
,I/LocationSettingsChecker( 6800): Removing dialog suppression flag for package com.test.thalitest
,I/art     ( 2891): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 527us total 12.709ms
,E/SQLiteLog( 6800): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6800): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6800): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6800): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6800): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6800): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6800): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6800): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6800): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6800): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6800): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6800): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6800): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6800): Opened metrics.db in read-only mode
I/art     ( 2891): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 326us total 9.814ms
,D/gH_CompatibleDatabase( 6800): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6800): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6800): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6800): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 6800): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6800): Process: com.google.android.gms, PID: 6800
E/AndroidRuntime( 6800): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6800): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6800): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6800): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6800): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6800): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6800): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6800): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6800): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ChimeraCfgMgr( 6800): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6800): Module APK com.google.android.play.games already loaded
,D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SharedPreferencesImpl(12675): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/SQLiteLog( 6800): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6800): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6800): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6800): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 6800): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6800): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6800): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6800): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6800): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6800): 	at com.google.android.,gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6800): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6800): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6800): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ContactProvider(12675): getAllContactInfoList Start
E/SQLiteLog( 4637): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4637): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 4637): Shutting down VM
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6800): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6800): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 4637): FATAL EXCEPTION: main
E/AndroidRuntime( 4637): Process: com.google.android.gms.persistent, PID: 4637
E/AndroidRuntime( 4637): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4637): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4637): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4637): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4637): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4637): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4637): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4637): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4637): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4637): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4637): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4637): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4637): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4637): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4637): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4637): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4637): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4637): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4637): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4637): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4637): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4637): 	... 9 more
D/ChimeraCfgMgr( 6800): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6800): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 6800): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6800): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop191.tmp: open failed: EROFS (Read-only file system)
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
E/ClearPendingStateOp( 6800): Runtime exception while performing operation
E/ClearPendingStateOp( 6800): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6800): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6800): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6800): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6800): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6800): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 6800): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6800): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6800): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6800): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6800): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6800): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6800): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6800): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6800): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6800): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6800): 	at java.lang.Thread.run(Thread.java:818)
E/Zygote  (12784): MountEmulatedStorage()
E/Zygote  (12784): v2
I/libpersona(12784): KNOX_SDCARD checking this for 10052
I/libpersona(12784): KNOX_SDCARD not a persona
E/GMPM-SVC( 6800): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
E/SQLiteLog( 6800): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6800): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
I/Process ( 6800): Sending signal. PID: 6800 SIG: 9
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
I/ActivityManager( 3523): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12784 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
I/SELinux (12784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
E/SELinux (12784): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/JavaBinder( 3523): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
I/FeatureConfig(12761): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
D/MtpClient(12675): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12675): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/DropBoxManagerService( 3523): Can't write: system_app_wtf
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
,W/ActivityManager( 3523): Process com.google.android.gms has crashed too many times: killing!
,D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
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
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
W/ResourcesManager(12761): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(12761): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 3523): Killing 4637:com.google.android.gms.persistent/u0a14 (adj 0): crash
W/ResourcesManager(12761): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12761): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12761): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,V/BackupManagerService( 3523): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
,V/BackupManagerService( 3523): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,D/TimaKeyStoreProvider(12784): TimaSignature is unavailable
,D/ActivityThread(12784): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 12315:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
,D/ConnectivityService( 3523): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1108b18f)
,D/ConnectivityService( 3523): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService( 3523): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager( 3523): Process com.google.android.gms (pid 6800)(adj 0) has died(341,1159)
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10846ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10845ms
D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20844ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20842ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30840ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30839ms
,E/SQLiteLog(12691): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
,W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteDatabase(12691): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12691): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12691): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12691): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12691): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12691): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12691): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12691): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12691): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12691): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12691): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12691): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12691): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12691): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12691): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12691): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12691): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12691): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12691): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12691): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12691): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12691): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12691): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12691): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12691): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12691): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12691): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12691): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at aEV.a(Gelly,InjectorStore.java:130)
E/SQLiteOpenHelper(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12691): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12691): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12691): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12691): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12691): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12691): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12691): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12691): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12691): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12691): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12691): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12691): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12691): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12691): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12691): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12691): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12691): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ResourcesManager(12761): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/SQLiteOpenHelper(12691): Opened ClientFlag.db in read-only mode
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager(12761): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/ResourcesManager(12784): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager(12761): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12761): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/ResourcesManager(12784): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12784): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Zygote  (12816): MountEmulatedStorage()
E/Zygote  (12816): v2
I/libpersona(12816): KNOX_SDCARD checking this for 10036
I/libpersona(12816): KNOX_SDCARD not a persona
I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
I/SELinux (12816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/SQLiteLog(12691): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12691): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12691): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12691): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12691): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12691): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12691): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(12691): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12691): Process: com.google.android.apps.docs, PID: 12691
E/AndroidRuntime(12691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12691): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12691): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12691): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12691): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12691): 	at aFp.run(AbstractDatabaseInstance.java:471)
I/SELinux (12816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourcesManager(12784): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12784): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12784): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12784): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SELinux (12816): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=12816 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/GpsStatusListenerHelper( 3523): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@a675c1c
D/LocationManagerService( 3523): Location listener died
I/LocationManagerService( 3523): remove 1e2b36b by com.google.android.gms
D/LocationManagerService( 3523): Location listener died
D/WifiService( 3523): Client connection lost with reason: 4
D/LocationManagerService( 3523): provider request: passive ProviderRequest[ON interval=0]
I/LocationManagerService( 3523): remove d924daa by com.google.android.gms
D/LocationManagerService( 3523): provider request: passive ProviderRequest[ON interval=0]
E/ActivityThread(11443): Failed to find provider info for com.facebook.appmanager.installrecord
V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
D/ResourcesManager(12761): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
W/ResourcesManager(12761): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
E/SQLiteLog(12691): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(12691): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12691): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12691): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12691): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12691): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12691): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12691): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12691): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12691): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12691): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(12691): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12691): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12691): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12691): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12691): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12691): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12691): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12691): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12691): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12691): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper(12691): Opened ClientFlag.db in read-only mode
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/DropBoxManagerService( 3523): Can't write: system_app_crash
E/DropBoxManagerService( 3523): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
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
,I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
,D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(12816): TimaSignature is unavailable
,D/ActivityThread(12816): Added TimaKeyStore provider
,W/ResourcesManager(12761): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  (12834): MountEmulatedStorage()
E/Zygote  (12834): v2
I/libpersona(12834): KNOX_SDCARD checking this for 10031
I/libpersona(12834): KNOX_SDCARD not a persona
,I/SELinux (12834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12834): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12834 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 8839:com.android.settings/1000 (adj 13): bgCount ##31
,D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,W/ResourcesManager(12761): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/BroadcastQueue( 3523): Skipping deliver [background] BroadcastRecord{3d0537c6 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{761b5fa 12691 com.google.android.apps.docs/10101/u0 remote:5baf025}: process crashing
,D/Mms/MmsApp(12784): [start]    onCreate() consume time = 0.0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12761): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/TimaKeyStoreProvider(12834): TimaSignature is unavailable
,D/ActivityThread(12834): Added TimaKeyStore provider
,D/Mms/ArtClassLoader(12784): init before art
D/ResourcesManager(12816): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ResourcesManager(12761): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/Mms/ArtClassLoader(12784): init [DONE] art
,E/Zygote  (12851): MountEmulatedStorage()
E/Zygote  (12851): v2
I/libpersona(12851): KNOX_SDCARD checking this for 1000
I/libpersona(12851): KNOX_SDCARD not a persona
,I/SELinux (12851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/WifiService( 3523): Client connection lost with reason: 4
,I/SELinux (12851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12851): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(12761): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(12761): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12761): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3523): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12851 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a

```
