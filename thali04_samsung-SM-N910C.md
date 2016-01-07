#### Test 55311151a2306df_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3527): !@Sync 4
,--------- beginning of main
D/AndroidRuntime(11657): 
D/AndroidRuntime(11657): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11657): CheckJNI is OFF
D/AndroidRuntime(11657): readGMSProperty: start
D/AndroidRuntime(11657): readGMSProperty: already setted!!
D/AndroidRuntime(11657): readGMSProperty: end
D/AndroidRuntime(11657): addProductProperty: start
D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 250, CUR = 42
E/AffinityControl(11657): AffinityControl: registerfunction enter
D/AndroidRuntime(11657): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3527): inState():  stateMachine is null !!
I/PersonaManagerService( 3527): PersonaId don't exist
I/ActivityManager( 3527): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3527): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3527): mDVFSHelper.acquire()
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/Zygote  (11675): MountEmulatedStorage()
E/Zygote  (11675): v2
I/libpersona(11675): KNOX_SDCARD checking this for 10539
I/libpersona(11675): KNOX_SDCARD not a persona
I/SELinux (11675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11675 uid=10539 gids={50539, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11675): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11657): Shutting down VM
D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11675): TimaSignature is unavailable
D/ActivityThread(11675): Added TimaKeyStore provider
I/SurfaceFlinger( 2854): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2854): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6243): updateVisibility : ActivityRecord{21e75144 token=android.os.BinderProxy@abb8c71 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ResourcesManager(11675): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/WebViewFactory(11675): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11675): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11675): Loading: webviewchromium
I/LibraryLoader(11675): Time to load native libraries: 4 ms (timestamps 4424-4428)
I/LibraryLoader(11675): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11675): Binding Chromium to main looper Looper (main, tid 1) {16fdce27}
,I/LibraryLoader(11675): Expected native library version number "",actual native library version number ""
I/chromium(11675): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11675): Initializing chromium process, renderers=0
,W/art     (11675): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11675): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11675): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11675): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11675): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11675): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11675): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11675): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11675): CordovaWebView is running on device made by: samsung
,W/art     (11675): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11675): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11675): performCreate Call secproduct feature valuefalse
D/Activity(11675): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11675): Render dirty regions requested: true
,D/ActivityManager( 3527): post active user change for 0
D/KnoxTimeoutHandler( 3527): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3527): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2854): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11675): Initialized EGL, version 1.4
,I/OpenGLRenderer(11675): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278639856 
,D/OpenGLRenderer(11675): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11675): Enabling debug mode 0
,D/mali_winsys(11675): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11675): updateVisibility : ActivityRecord{e08f17 token=android.os.BinderProxy@3986751a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3527): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3527): mDVFSHelper.release()
I/Timeline( 3527): Timeline: Activity_windows_visible id: ActivityRecord{79558f4 u0 com.test.thalitest/.MainActivity t26} time:134774
,W/IInputConnectionWrapper(11675): showStatusIcon on inactive InputConnection
,I/Timeline(11675): Timeline: Activity_idle id: android.os.BinderProxy@3986751a time:134784
,D/JsMessageQueue(11675): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11675): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11675): 
,D/jxcore_app_log(11675): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11675): jxcore cordova android initializing
,W/jxcore-log(11675): Initializing JXcore engine
W/jxcore-log(11675): JXcore engine is ready
,W/jxcore-log(11675): Starting JXcore engine
,E/auditd  ( 4617): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3527): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3527): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11675): Platform android
W/jxcore-log(11675): 
W/jxcore-log(11675): Process ARCH arm
W/jxcore-log(11675): 
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11675): JXcore Cordova bridge is ready!
I/jxcore-log(11675): 
W/jxcore-log(11675): JXcore engine is started
,I/jxcore-log(11675): Toggling radios to true
I/jxcore-log(11675): 
,D/BluetoothAdapter(11675): enable()
,D/BluetoothAdapter(11675): enable(): BT is already enabled..!
,D/WifiService( 3527): New client listening to asynchronous messages
,I/WifiManager(11675): packageName : com.test.thalitest
,D/SecContentProvider( 3527): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3527): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3527): mCursor = null
,D/WifiService( 3527): setWifiEnabled: true pid=11675, uid=10539
E/WifiService( 3527): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3527): Permission Denial: getCurrentUser() from pid=11675, uid=10539 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3527): Failed getting userId using ActivityManagerNative
W/WifiService( 3527): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11675, uid=10539 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3527): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3527): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3527): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3527): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3527): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3527): name = wifi_on
,I/WifiService( 3527): disconnect: pid=11675, uid=10539
,I/wpa_supplicant( 3836): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11675): Radios toggled
I/jxcore-log(11675): 
,I/wpa_supplicant( 3836): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log(11675): Received device characteristics:
I/jxcore-log(11675): Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11675): Bluetooth name: Note4-1
I/jxcore-log(11675): Device name: samsung-SM-N910C
I/jxcore-log(11675): 
I/wpa_supplicant( 3836): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3527): WifiStateMachine: Leaving Connected state
I/jxcore-log(11675): Perf Test app loaded loaded
I/jxcore-log(11675): 
I/wpa_supplicant( 3836): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3836): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3836): Disconnected - do not scan
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3527): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3527): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3527): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3527): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11675): check test folder
I/jxcore-log(11675): 
,I/jxcore-log(11675): found test : ./testFindPeers.js
I/jxcore-log(11675): 
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3527): do suspend true
,D/WifiP2pService( 3527): InactiveState{ what=143375 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=143375 }
,D/CommandListener( 2847): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,V/NativeCrypto( 4621): Read error: ssl=0x9c111e00: I/O error during system call, Connection timed out
,I/jxcore-log(11675): found test : ./testSendData.js
I/jxcore-log(11675): 
,E/WifiStateMachine( 3527): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
V/NativeCrypto( 4621): SSL shutdown failed: ssl=0x9c111e00: I/O error during system call, Broken pipe
,E/ConnectivityService( 3527): updateNetworkInfo()
E/WifiConfigStore( 3527): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3527): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3527): updateNetworkInfo()
,D/ConnectivityService( 3527): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/ConnectivityService( 3527): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): ValidatedState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): DefaultState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine( 3527): Start Disconnecting Watchdog 1
I/System.out( 3527): (HTTPLog)-Static: isSBSettingEnabled false
I/wpa_supplicant( 3836): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3836): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3836): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3836): First Scan Start
E/WifiStateMachine( 3527): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3527): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/wpa_supplicant( 3836): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3527): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3527): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3527): do suspend true
D/WifiP2pService( 3527): InactiveState{ what=143375 }
D/WifiP2pService( 3527): P2pEnabledState{ what=143375 }
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
,I/Hs20UtilService( 4112): Starting #8
,I/Hs20UtilService( 4112): Message received 5007
D/NearbySettings( 8615): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8615): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8615): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8615): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8615): DMSUtil.isNetworkConnected - flag-null, state-null
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3527): New client listening to asynchronous messages
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8615): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8615): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11332): NETWORK_STATE_CHANGED_ACTION
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/CommandListener( 2847): Clearing all IP addresses on wlan0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 3527): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3527): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Validated
D/ConnectivityService( 3527): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
E/WifiStateMachine( 3527): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker( 3527): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3527): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine( 3527): updateConfiguredNetworkExpiration - currTime: 1452155967244
D/WifiStateMachine( 3527): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/TelephonyNetworkFactory( 3984): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 4777): CM callback handler got msg 524292
E/WifiStateMachine( 3527): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
E/WifiStateMachine( 3527): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3527): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3527): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3527): NetworkAgent: NetworkAgent channel lost
I/Choreographer(11675): Skipped 48 frames!  The application may be doing too much work on its main thread.
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine( 3527): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3527): MasterInitialState.processMessage what=3
D/EntConnectivity( 3527): Not allowed due to - mEnabled false
,D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3527): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
V/NetworkStats( 3527): updateIfacesLocked()
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
V/NetworkStats( 3527): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3527): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/ConnectivityService( 3527): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/chromium(11675): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
V/NetworkStats( 3527): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/Hs20UtilService( 4112): Starting #9
,D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
V/NetworkStats( 3527): performPollLocked() took 6ms
I/Hs20UtilService( 4112): Message received 5007
,I/chromium(11675): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,D/NearbySettings( 8615): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8615): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8615): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8615): MountReceiver.mPrefHandler - 7002
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,I/SignOutReceiver(11332): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3527): updateDataUsageMap
,I/ApplicationPolicy( 3527): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3527): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3527): getSBEnabled() enabled =false
,D/SmartBondingService( 3527): getSBEnabled() enabled =false
,D/SmartBondingService( 3527): getSBEnabled() enabled =false
,D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3527): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/SLocation( 3527): No Active Data Connection
,E/Zygote  (11774): MountEmulatedStorage()
,E/Zygote  (11774): v2
I/libpersona(11774): KNOX_SDCARD checking this for 10110
I/libpersona(11774): KNOX_SDCARD not a persona
,I/ActivityManager( 3527): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11774 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11774): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider(11774): TimaSignature is unavailable
,D/ActivityThread(11774): Added TimaKeyStore provider
,D/ResourcesManager(11774): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11774): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11774): not using cross-dex optimization: ART in use
,I/art     (11774): Thread[1,tid=11774,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11774): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11774): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(11774): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11774): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
,D/DexLibLoader(11774): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11774): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11774): loading pre-built fallback odex files
V/MultiDexClassLoader(11774): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11774): released odex store lock
,D/DexLibLoader(11774): DexLibLoader.loadAll took 36 ms
,W/ca      (11774): Verify
,W/LightSharedPreferencesImpl(11774): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11774): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11774): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11774): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11774): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11774): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11774): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11774): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11774): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11774): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11774): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11774): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11774): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11774): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11774): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11774): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11774): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11774): 	... 10 more
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11806): MountEmulatedStorage()
E/Zygote  (11806): v2
I/libpersona(11806): KNOX_SDCARD checking this for 1000
I/libpersona(11806): KNOX_SDCARD not a persona
,I/SELinux (11806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (11806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/wpa_supplicant( 3836): nl80211: Received scan results (10 BSSes)
I/ActivityManager( 3527): Killing 9754:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
E/SELinux (11806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 3836): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3836): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3836): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3527): [1,452,155,968,271 ms] noteScanEnd no scan source
,W/appmanager(:<default>):b(11774): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/WifiStateMachine( 3527): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@64877fc sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3527): setDetailed state send new extra info
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,W/appmanager(:<default>):b(11774): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11806): TimaSignature is unavailable
,D/ActivityThread(11806): Added TimaKeyStore provider
,D/ResourcesManager(11806): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11774): Exposure of experiment com.facebook.common.network.l@393eeb8c occurred when no user was logged in
I/wpa_supplicant( 3836): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3836): Associated with C0.AA.48
E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3527): setDetailed state send new extra info"NG700"
,I/PCWCLIENTTRACE_LOG(11806): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11806): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11806): new DMDBOpenHelper instance
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,I/wpa_supplicant( 3836): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3527): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,I/PCWCLIENTTRACE_PushUtil(11806): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11806): sales region : global
I/PCWCLIENTTRACE_PushUtil(11806): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11806): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11806): noConnectivity : true
,I/wpa_supplicant( 3836): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{27975b6d u0 ReceiverList{33e0c784 11774 com.facebook.appmanager/10110/u0 remote:31b08997}}
,W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{27975b6d u0 ReceiverList{33e0c784 11774 com.facebook.appmanager/10110/u0 remote:31b08997}}
I/wpa_supplicant( 3836): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3527): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/wpa_supplicant( 3836): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3836): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3836): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3836): Blacklist: Clear (temp) 
I/wpa_supplicant( 3836): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3527): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3527): Network connection established
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/WifiNative-HAL( 3527): callSECApiVoid - ID [50]
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3527): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/Zygote  (11829): MountEmulatedStorage()
E/Zygote  (11829): v2
I/libpersona(11829): KNOX_SDCARD checking this for 10135
I/libpersona(11829): KNOX_SDCARD not a persona
,I/SELinux (11829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11829 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11829): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 10933:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/WifiStateMachine( 3527): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3527): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3527): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3527): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiStateMachine( 3527): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3527): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3527): updateNetworkInfo()
D/ConnectivityService( 3527): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiStateMachine( 3527): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3527): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3527): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3527): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/TimaKeyStoreProvider(11829): TimaSignature is unavailable
,D/ActivityThread(11829): Added TimaKeyStore provider
,D/CommandListener( 2847): Setting iface cfg
,E/WifiStateMachine( 3527): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager(11829): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3527): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1daa3f7f u0 ReceiverList{2db3489e 11774 com.facebook.appmanager/10110/u0 remote:360a56d9}}
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3527): do suspend false
,D/SecContentProvider2( 3527): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3527): mCursor = null
D/WifiP2pService( 3527): InactiveState{ what=143375 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=143375 }
,I/MusicStore(11829): Database version: 104
,D/ResourcesManager(11829): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11829): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11829): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11829): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2416680b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11829): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11829): GMSCore installation verified
,I/ConfigStore(11829): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11829): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/dhcpcd  (11863): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11863): version 5.5.6 starting
,E/dhcpcd  (11863): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11829): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11829): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/dhcpcd  (11863): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11863): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  (11863): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11863): bssid match
I/dhcpcd  (11863): wlan0: rebinding lease of 192.168.1.124
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3527): getStreamVolume 3 index 0
,I/MediaRouter(11829): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 69688(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 6.506ms total 212.708ms
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11878): MountEmulatedStorage()
E/Zygote  (11878): v2
I/libpersona(11878): KNOX_SDCARD checking this for 10002
I/libpersona(11878): KNOX_SDCARD not a persona
,I/SELinux (11878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11878 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11774): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11774): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/NetworkMonitor(11829): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11878): TimaSignature is unavailable
,D/ActivityThread(11878): Added TimaKeyStore provider
,D/ResourcesManager(11878): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3527): Killing 10950:com.policydm/1000 (adj 15): bgCount ##31
,W/appmanager(:<default>):QuickExperimentControllerImpl(11774): Exposure of experiment com.facebook.imagepipeline.a.g@d78f86a occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11774): Exposure of experiment com.facebook.imagepipeline.a.d@12059837 occurred when no user was logged in
,I/ActivityManager( 3527): Killing 10814:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,I/art     (11774): Explicit concurrent mark sweep GC freed 46062(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.631ms total 49.513ms
,W/appmanager(:<default>):m(11774): No feature status reporters found; is this dead code?
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11904): MountEmulatedStorage()
E/Zygote  (11904): v2
I/libpersona(11904): KNOX_SDCARD checking this for 1000
I/libpersona(11904): KNOX_SDCARD not a persona
,I/SELinux (11904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11904): TimaSignature is unavailable
,D/ActivityThread(11904): Added TimaKeyStore provider
,D/ResourcesManager(11904): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11904): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11904): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11904): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11922): MountEmulatedStorage()
I/libpersona(11922): KNOX_SDCARD checking this for 10012
E/Zygote  (11922): v2
I/libpersona(11922): KNOX_SDCARD not a persona
,I/SELinux (11922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11922 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (11922): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11922): TimaSignature is unavailable
,D/ActivityThread(11922): Added TimaKeyStore provider
,D/ResourcesManager(11922): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3527): Killing 10968:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,I/FOTA_Client(11922): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11922): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11922): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11938): MountEmulatedStorage()
E/Zygote  (11938): v2
I/libpersona(11938): KNOX_SDCARD checking this for 10021
I/libpersona(11938): KNOX_SDCARD not a persona
,I/SELinux (11938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11938 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/SELinux (11938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11029:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 884us total 23.435ms
,D/TimaKeyStoreProvider(11938): TimaSignature is unavailable
,D/ActivityThread(11938): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 893us total 18.629ms
,D/ResourcesManager(11938): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11938): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 07 09:39:29 GMT+01:00 2016
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.168ms total 21.087ms
,I/KLMS-2.4.521: (11938): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11938): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11938): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11938): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11938): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11938): StateImplV2(): networkChangeListener().END
,E/Zygote  (11954): MountEmulatedStorage()
E/Zygote  (11954): v2
I/libpersona(11954): KNOX_SDCARD checking this for 10038
I/libpersona(11954): KNOX_SDCARD not a persona
,I/SELinux (11954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11954 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3527): Killing 11013:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11013/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11954): TimaSignature is unavailable
,D/ActivityThread(11954): Added TimaKeyStore provider
,D/ResourcesManager(11954): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11954): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11969): MountEmulatedStorage()
E/Zygote  (11969): v2
I/libpersona(11969): KNOX_SDCARD checking this for 1000
I/libpersona(11969): KNOX_SDCARD not a persona
,I/SELinux (11969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11097:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11969): TimaSignature is unavailable
,D/ActivityThread(11969): Added TimaKeyStore provider
,D/ResourcesManager(11969): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11989): MountEmulatedStorage()
E/Zygote  (11989): v2
I/libpersona(11989): KNOX_SDCARD checking this for 10039
I/libpersona(11989): KNOX_SDCARD not a persona
,I/SELinux (11989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11989): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11989 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11067:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11989): TimaSignature is unavailable
,D/ActivityThread(11989): Added TimaKeyStore provider
,D/ResourcesManager(11989): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/dhcpcd  (11863): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,E/SPPClientService(11989): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11989): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11989): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(11989): PushLog.txt file is not deleted.
D/SPPClientService(11989): PushLog.txt file is not deleted.
D/SPPClientService(11989): ============PushLog. stop!
,I/SA      (11160): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11160): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11160): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11160): [SLFUCHKMGR] constructor called
,E/SPPClientService(11989): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11160): [OR] == isSIMCardReady false ==
,I/SA      (11160): [SCU] == networkStateCheck == false
I/SA      (11160): [OR] onReceive END
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/dhcpcd  (11863): wlan0: leased 192.168.1.124 for 86400 seconds
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Zygote  (12011): MountEmulatedStorage()
E/Zygote  (12011): v2
I/libpersona(12011): KNOX_SDCARD checking this for 10067
I/libpersona(12011): KNOX_SDCARD not a persona
,I/SELinux (12011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12011 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (12011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11047:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12011): TimaSignature is unavailable
D/ActivityThread(12011): Added TimaKeyStore provider
,D/ResourcesManager(12011): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12011): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12011): Other Intent
,I/ActivityManager( 3527): Killing 10991:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/accuweather( 5228): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5228): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5228): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5228): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5228): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12043): MountEmulatedStorage()
E/Zygote  (12043): v2
I/libpersona(12043): KNOX_SDCARD checking this for 1000
I/libpersona(12043): KNOX_SDCARD not a persona
,I/SELinux (12043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12043): TimaSignature is unavailable
,D/ActivityThread(12043): Added TimaKeyStore provider
,D/ResourcesManager(12043): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12043): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3527): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3527): do suspend true
,I/KnoxUsageLogPro(12043): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12043): premStatus:2
,D/WifiP2pService( 3527): InactiveState{ what=143375 }
D/WifiP2pService( 3527): P2pEnabledState{ what=143375 }
,I/KnoxUsageLogPro(12043): isEulaShown : false
I/KnoxUsageLogPro(12043): KnoxUsageReceiver onReceive : not Processible, just return
,E/WifiStateMachine( 3527): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3527): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine( 3527): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12061): MountEmulatedStorage()
E/Zygote  (12061): v2
I/libpersona(12061): KNOX_SDCARD checking this for 10090
I/libpersona(12061): KNOX_SDCARD not a persona
,I/SELinux (12061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12061 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12061): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11082:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,E/WifiStateMachine( 3527): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3527): Not connected state, yet.
E/WifiStateMachine( 3527): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3527): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3527): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3527): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3527): callSECApiInt - ID [210]
,E/WifiStateMachine( 3527): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3527): updateNetworkInfo()
,D/ConnectivityService( 3527): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3527): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3527): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3527): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3527): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3527): Now, connected state.
E/WifiStateMachine( 3527): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3527): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider(12061): TimaSignature is unavailable
D/ConnectivityService( 3527): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ActivityThread(12061): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3527): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine( 3527): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 3527): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService( 3527): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3527): Unexpected mtu value: 0, wlan0
,V/        ( 2847): QcRouteController
,I/WifiTrafficPoller( 3527): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3527): callSECApiVoid - ID [212]
,I/WifiStateMachine( 3527): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        ( 2847): QcRouteController
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,W/NetworkManagementService( 3527): route cmd failed: 
W/NetworkManagementService( 3527): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '71 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 71 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3527): '
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3527): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3527): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6313)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService.access$2700(ConnectivityService.java:231)
W/NetworkManagementService( 3527): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2449)
W/NetworkManagementService( 3527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3527): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3527): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ResourcesManager(12061): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,V/        ( 2847): QcRouteController
,E/Zygote  (12096): MountEmulatedStorage()
,E/Zygote  (12096): v2
I/libpersona(12096): KNOX_SDCARD checking this for 10127
I/libpersona(12096): KNOX_SDCARD not a persona
,I/SELinux (12096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ConnectivityService( 3527): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3527): LTETest block dns file not exists
I/ActivityManager( 3527): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12096 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11141:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,I/SELinux (12096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ConnectivityService( 3527): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3527): updateNetworkInfo()
E/ConnectivityService( 3527): updateNetworkInfo()
,D/ConnectivityService( 3527): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/SELinux (12096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 3527): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3527): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3527): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3527):    accepting network in place of null
,D/TelephonyNetworkFactory( 3984): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3527): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3527): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3527): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3527): MasterInitialState.processMessage what=3
D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3527): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
,V/NetworkStats( 3527): updateIfacesLocked()
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
V/NetworkStats( 3527): performPollLocked(flags=0x1)
,D/ConnectivityService( 3527): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/NetworkStatsFactory( 3527): UpdateStatsForKnox
,D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 4777): CM callback handler got msg 524290
,D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,V/NetworkStats( 3527): performPollLocked() took 9ms
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
V/NetworkStats( 3527): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
D/NtpTrustedTime( 3527): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider(12096): TimaSignature is unavailable
D/ActivityThread(12096): Added TimaKeyStore provider
D/ResourcesManager(12096): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12096): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12096): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12096): stopCheckCategoryVersion
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/System.out( 3527): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Zygote  (12114): MountEmulatedStorage()
,E/Zygote  (12114): v2
I/libpersona(12114): KNOX_SDCARD checking this for 10136
I/libpersona(12114): KNOX_SDCARD not a persona
,I/SELinux (12114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12114 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12114): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Killing 11173:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12114): TimaSignature is unavailable
,D/ActivityThread(12114): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jan 2016 08:39:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452155970938], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452155970915]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3527): Validated
,D/ConnectivityService( 3527): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3527): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3527): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3527): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524290
D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 4777): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,D/ResourcesManager(12114): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12114): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12114): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12114): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12114): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12114): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12114): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/ConnectivityService( 3527): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3527): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3527): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3527): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3527): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
D/SmartBondingService( 3527): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3527): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/LibraryLoader(12114): Loading: webviewchromium
,D/SmartBondingService( 3527): getNetworkEnabled : wifi : true mobile : false
,I/LibraryLoader(12114): Time to load native libraries: 19 ms (timestamps 1191-1210)
I/LibraryLoader(12114): Expected native library version number "",actual native library version number ""
,I/DBG_DM  ( 6243): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6243): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11829): type=WIFI subType= reason=null isConnected=true
,V/WebViewChromiumFactoryProvider(12114): Binding Chromium to main looper Looper (main, tid 1) {33ba0c3d}
,I/LibraryLoader(12114): Expected native library version number "",actual native library version number ""
,I/chromium(12114): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ResourceType( 5368): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5368): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/BrowserStartupController(12114): Initializing chromium process, renderers=0
,W/art     (12114): Attempt to remove local handle scope entry from IRT, ignoring
,D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3527): mCursor = null
,W/chromium(12114): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12114): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12114): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12114): Requires BLUETOOTH permission
,I/NSApplication(12114): Starting up...
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12191): MountEmulatedStorage()
I/libpersona(12191): KNOX_SDCARD checking this for 10150
E/Zygote  (12191): v2
I/libpersona(12191): KNOX_SDCARD not a persona
,I/SELinux (12191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12191 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11197:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12191): TimaSignature is unavailable
,D/ActivityThread(12191): Added TimaKeyStore provider
,D/ResourcesManager(12191): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12191): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12191): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12191): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12191): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12191): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12191): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12206): MountEmulatedStorage()
E/Zygote  (12206): v2
I/libpersona(12206): KNOX_SDCARD checking this for 10178
I/libpersona(12206): KNOX_SDCARD not a persona
,I/SELinux (12206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12206): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12206 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3527): Killing 11215:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12206): TimaSignature is unavailable
,D/ActivityThread(12206): Added TimaKeyStore provider
,D/ResourcesManager(12206): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12206): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12206): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12206): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12206): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12206): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12206): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/ConnectivityService( 3527): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,E/Zygote  (12229): MountEmulatedStorage()
E/Zygote  (12229): v2
I/libpersona(12229): KNOX_SDCARD checking this for 10082
I/libpersona(12229): KNOX_SDCARD not a persona
,I/SELinux (12229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12229 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,I/SELinux (12229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/SELinux (12229): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.208ms total 29.947ms
,D/TimaKeyStoreProvider(12229): TimaSignature is unavailable
,D/ActivityThread(12229): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 783us total 19.230ms
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 442us total 16.570ms
,E/Zygote  (12245): MountEmulatedStorage()
I/libpersona(12245): KNOX_SDCARD checking this for 1000
E/Zygote  (12245): v2
I/libpersona(12245): KNOX_SDCARD not a persona
,I/SELinux (12245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11352:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 11246:com.samsung.helphub/1000 (adj 15): bgCount ##32
,D/TimaKeyStoreProvider(12245): TimaSignature is unavailable
,D/ActivityThread(12245): Added TimaKeyStore provider
,D/ResourcesManager(12229): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,W/ActivityManager( 3527): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager(12245): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12229): onCreate
D/BadgeProvider(12229): DatabaseHelper
,I/ActivityManager( 3527): Killing 11369:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12229): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 4000): reloadBadges entered.
D/BadgeProvider(12229): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12229): sendNotify, [notify] : null
D/BadgeProvider(12229): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12229): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12229): update, [UpdateCount] : 1
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12262): MountEmulatedStorage()
E/Zygote  (12262): v2
I/libpersona(12262): KNOX_SDCARD checking this for 10013
I/libpersona(12262): KNOX_SDCARD not a persona
,I/SELinux (12262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12262 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (12262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12262): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setDiscoveryMode: Mode set to BLE
,I/jxcore-log(11675): BLE is supported
I/jxcore-log(11675): 
,D/TimaKeyStoreProvider(12262): TimaSignature is unavailable
,D/ActivityThread(12262): Added TimaKeyStore provider
,D/ResourcesManager(12262): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12262): notifyNetworkActivated
,W/ContextImpl(12262): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3527): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12262): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12262): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12262): exit::IDLE
D/InitializeManagerStateMachine(12262): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12262): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12262): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12262): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12262): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12262): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12262): entry::SUCCESS
D/hcjo    (12262): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12262): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12262): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 4112): Starting #10
D/InitializeManagerStateMachine(12262): exit::SUCCESS
D/InitializeManagerStateMachine(12262): entry::IDLE
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8615): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8615): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8615): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 3527): Killing 11386:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SignOutReceiver(11332): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #11
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8615): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8615): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11332): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #12
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8615): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8615): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8615): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8615): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8615): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11332): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4112): Starting #13
,I/Hs20UtilService( 4112): Message received 5007
,D/NearbySettings( 8615): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8615): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3527): callSECApi what=220
D/WifiStateMachine( 3527): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11332): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11806): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11806): sales region : global
I/PCWCLIENTTRACE_PushUtil(11806): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11806): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2854): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11904): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 3527): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3527
,D/mali_winsys( 3691): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(11922): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11922): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11922): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11938): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 07 09:39:32 GMT+01:00 2016
,I/KLMS-2.4.521: (11938): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11938): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11938): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11938): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11938): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11938): StateImplV2(): networkChangeListener().START
,I/SO_AGENT(11954): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11938): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11938): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11938): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onDestroy()
,E/SPPClientService(11989): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11160): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11160): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11160): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11160): [OR] == isSIMCardReady false ==
,I/SA      (11160): [SCU] == networkStateCheck == true
I/SA      (11160): [DM] getCountryCodeFromCSC : PL
I/SA      (11160): isChinaCountryCode : false
,I/SA      (11160): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11160): [OR] == networkStateCheck true ==
I/SA      (11160): [OR] GetMyCountryZoneTask
,I/SA      (11160): [OR] onReceive END
,I/SA      (11160): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11160): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11160): [SSP] query invoked
,I/SCloudBackupReceiver(12011): Other Intent
,I/SA      (11160): [TPMU] GetMccFromDB : null
I/SA      (11160): [SCU] getMccFromPreferece mcc = 260
I/SA      (11160): [TPM] isNoProxy(default) : true
,D/accuweather( 5228): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5228): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5228): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5228): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5228): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5228): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12043): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12043): premStatus:2
,I/KnoxUsageLogPro(12043): isEulaShown : false
I/KnoxUsageLogPro(12043): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12096): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12096): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12096): stopCheckCategoryVersion
,D/QuickConnect(12191): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12191): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12191): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/RCPManagerService( 3527): exchangeData() failure , invalid userId
,D/hcjo    (12262): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12262): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12262): exit::IDLE
D/InitializeManagerStateMachine(12262): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12262): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12262): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12262): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12262): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12262): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12262): entry::SUCCESS
D/hcjo    (12262): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12262): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12262): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12262): exit::SUCCESS
D/InitializeManagerStateMachine(12262): entry::IDLE
,I/dhcpcd  (11863): wlan0: sending IPv6 Router Solicitation
,I/SA      (11160): [RC New] Execute method=[GET] start
,I/SA      (11160): [RC New] Security=[true]
,I/System.out(11160): Thread-1540(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11160): Thread-1540(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11160): Thread-1540(ApacheHTTPLog):isShipBuild true
,I/System.out(11160): Thread-1540(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10045
,I/SA      (11160): [RC New] [v2liruge] api execute + 772
,I/SA      (11160): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11160): AsyncTask #1 calls detatch()
,I/SA      (11160): [TPMU] getNetworkMcc : 
,I/SA      (11160): [SCU] saveMccToPreferece Start
I/SA      (11160): [SCU] RegionMCC : 260
I/SA      (11160): [SSP] query invoked
,I/WifiStateMachine( 3527): REQUEST_POWER_SAVE_ON
,D/WearableService( 4621): callingUid 10014, callindPid: 4621
,E/WifiStateMachine( 3527): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 44329(2MB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 2.299ms total 167.428ms
I/art     ( 3527): WaitForGcToComplete blocked for 30.527ms for cause HeapTrim
,I/MusicLeanback(11829): Conditions not met for autocaching.
I/MusicLeanback(11829): Stop autocaching.
,D/ResourcesManager(11829): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/SSRM:n  ( 3527): SIOP:: AP = 250, PST = 247, CUR = 57
,I/SA      (11160): [TPMU] GetMccFromDB : null
I/SA      (11160): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11160): [SCU] saveMccToPreferece End
,I/SA      (11160): [RC New] executeRequest [v2liruge] end. 1061
I/SA      (11160): [RC New] Execute end
,W/ResourcesManager(11829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(11829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SA      (11160): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11160): [OR] GetMyCountryZoneTask Success
,I/GHttpClientFactory(11829): Using the GMSCore's GoogleHttpClient
,D/WearableClient(11829): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11829): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11829): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11829): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11829): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11829): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11829): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@39f4bdfd that was originally bound here
E/ActivityThread(11829): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@39f4bdfd that was originally bound here
E/ActivityThread(11829): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11829): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11829): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11829): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11829): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11829): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11829): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11829): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11829): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11829): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11829): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11829): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11829): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11829): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11829): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11829): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11829): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11829): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11829): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11829): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11829): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11829): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11829): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11829): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/PackageManager( 3527): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PowerManagerService( 3527): [PWL] Off : 50s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SurfaceFlinger( 2854): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2854): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3527): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3527) eventTime = 145912
,D/PowerManagerService( 3527): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3527 (0x0)
,D/PowerManagerService( 3527): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3527, ws=WorkSource{10060}) (elapsedTime=3475)
,I/GAV4    (12114): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (11863): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver(11806): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11806): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11806): ================================================
I/CSTORAGE(11806):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11806): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11806): [GetString-S]
E/art     (11806): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11806): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11806): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11806): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11806): sales region : global
I/PCWCLIENTTRACE_PushUtil(11806): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11806): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11863): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11863): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12262): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12262): exit::IDLE
D/PreloadUpdateManagerStateMachine(12262): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12262): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12262): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12262): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12262): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12262): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12262): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12262): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12262): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12262): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12262): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12262): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12262): entry::IDLE
,D/SSRM:n  ( 3527): SIOP:: AP = 240, PST = 246, CUR = 24
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3527): Waited long enough for: ServiceRecord{4312772 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3527): !@Sync 5
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 244, CUR = 45
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 227, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3527): [PWL] Off : 75s ago
,V/AlarmManager( 3527): waitForAlarm result :8
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 243, CUR = 49
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4621): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3527): SIOP:: AP = 230, PST = 242, CUR = 47
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3527): !@Sync 6
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 237, CUR = 45
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3527): [PWL] Off : 105s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 233, CUR = 41
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 230, CUR = 39
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3527): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3691): handleTimeUpdate
,D/KeyguardEffectViewController( 3691): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3691): *** don't update sliding image ***
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3691): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3527): !@Sync 7
,W/ProcessCpuTracker( 3527): Skipping unknown process pid 12483
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 229, CUR = 39
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3527): waitForAlarm result :8
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 227, CUR = 37
,I/PowerManagerService( 3527): [PWL] Off : 140s ago
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30,
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 225, CUR = 35
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3527): !@Sync 8
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 223, CUR = 32,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 222, CUR = 32
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3527): [PWL] Off : 180s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 221, CUR = 31
,I/jxcore-log(11675): Connected to the server!
I/jxcore-log(11675): 
,I/chromium(11675): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 9
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 221, CUR = 29
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 28
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 28
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3527): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3527): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3527): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3527): initializing...
,I/TLC_TIMA_PKM_initialize( 3527): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3527): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3527): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3527): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3527): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3527): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3527): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3527): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3527): device_id = 0x0
I/TZ: mc_tlc_communication( 3527): tlc_open() was called
,I/TZ: mc_tlc_communication( 3527): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3527): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3527): Opening the session
,I/TZ: mc_tlc_communication( 3527): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3527): Trustlet response is completed
,E/Watchdog( 3527): !@Sync 10
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 220, CUR = 27
,W/ProcessCpuTracker( 3527): Skipping unknown process pid 12562
,I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 3527): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3527): [PWL] Off : 225s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 219, CUR = 27
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 218, CUR = 28
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 11
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 218, CUR = 26
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 217, CUR = 25
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 216, CUR = 26
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3527): [PWL] Off : 275s ago
,E/Watchdog( 3527): !@Sync 12
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 216, CUR = 25
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 215, CUR = 25,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 214, CUR = 24
,I/jxcore-log(11675): --- start :testFindPeers.js---
I/jxcore-log(11675): 
,I/jxcore-log(11675): testFindPeers created [object Object]
I/jxcore-log(11675): 
,I/jxcore-log(11675): serverPort is 8876
I/jxcore-log(11675): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11675): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11675): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/BluetoothSocket(11675): bindListen(), new LocalSocket 
D/BluetoothSocket(11675): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11675): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1972abce
D/BluetoothSocket(11675): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): start: OK
I/io.jxcore.node.ConnectionHelper(11675): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11675): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11675): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): start: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11675): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3527): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 3527): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setState: RUNNING
D/WifiP2pService( 3527): P2pEnabledState add service
I/io.jxcore.node.ConnectionHelper(11675): start: OK
,I/jxcore-log(11675): StartBroadcasting started ok
I/jxcore-log(11675): 
D/WifiP2pService( 3527): add a new client
,I/io.jxcore.node.ConnectionHelper(11675): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper(11675): onDiscoveryManagerStateChanged: RUNNING
,I/chromium(11675): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 3527): InactiveState{ what=139265 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3527): callSECApi what=74
D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11675): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery started successfully
,D/WifiP2pService( 3527): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 2 device(s) discovered
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3527): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139301 }
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 2 device(s) discovered
D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 3527): P2pEnabledState add service request
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 3527): !@Sync 13
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 214, CUR = 23
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3527): waitForAlarm result :8
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 213, CUR = 23
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3527): [PWL] Off : 330s ago
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 213, CUR = 23
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: RESTARTING,
,D/WifiP2pService( 3527): InactiveState{ what=139268 }
,I/wpa_supplicant( 3836): P2P-FIND-STOPPED ,
,D/WifiP2pService( 3527): InactiveState{ what=147493 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3527): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/Watchdog( 3527): !@Sync 14
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): Start timer timeout, starting now...
,D/WifiP2pService( 3527): InactiveState{ what=139265 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139265 }
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: STARTED
,D/WifiP2pService( 3527): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 212, CUR = 23
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3836): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 212, CUR = 22,
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log(11675): 
,I/jxcore-log(11675): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(11675): 
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 211, CUR = 23,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,E/Watchdog( 3527): !@Sync 15
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 211, CUR = 22
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log(11675): 
,I/jxcore-log(11675): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 },
D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log(11675): 
I/jxcore-log(11675): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log(11675): 
,I/jxcore-log(11675): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
,I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"XT1072","peerAvailable":true}]
I/jxcore-log(11675): 
I/jxcore-log(11675): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(11675): 
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 21
,I/wpa_supplicant( 3836): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log(11675): 
,I/jxcore-log(11675): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log(11675): 
,I/jxcore-log(11675): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(11675): 
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
D/WifiP2pService( 3527): InactiveState{ what=139307 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3527): P2pEnabledState clear service request
D/WifiP2pService( 3527): InactiveState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState receive service response
D/WifiP2pService( 3527): InactiveState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
D/WifiP2pManager(11675): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,I/PowerManagerService( 3527): [PWL] Off : 390s ago
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 22
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState receive service response
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
I/jxcore-log(11675): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log(11675): 
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
I/jxcore-log(11675): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(11675): 
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3527): !@Sync 16
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 21
,I/jxcore-log(11675): timeout now
I/jxcore-log(11675): 
,I/jxcore-log(11675): weAreDoneNow
I/jxcore-log(11675): 
,I/jxcore-log(11675): done, now sending data to server
I/jxcore-log(11675): 
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 21
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 21
,I/jxcore-log(11675): teardown
I/jxcore-log(11675): 
,I/jxcore-log(11675): testFindPeers stopped
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): shutdown
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@3511b6da, channel: 6, state: LISTENING
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@3511b6da, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1972abce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4dd770bmSocket: android.net.LocalSocket@2a1339e8 impl:android.net.LocalSocketImpl@37448801 fd:FileDescriptor[115]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@2a1339e8 impl:android.net.LocalSocketImpl@37448801 fd:FileDescriptor[115]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): stop: Stopping services
,D/WifiP2pService( 3527): InactiveState{ what=139298 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3527): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3527): InactiveState{ what=139268 }
,I/wpa_supplicant( 3836): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11675): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setState: NOT_STARTED
,D/WifiP2pService( 3527): InactiveState{ what=147493 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3527): discovery change broadcast false
,I/jxcore-log(11675): StopBroadcasting went ok
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): remove channel information from framework
,I/jxcore-log(11675): --- start :testSendData.js---
I/jxcore-log(11675): 
,I/jxcore-log(11675): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log(11675): 
,I/jxcore-log(11675): daya100000
I/jxcore-log(11675): 
,I/jxcore-log(11675): check server
I/jxcore-log(11675): 
I/jxcore-log(11675): serverPort is 44381
I/jxcore-log(11675): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11675): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11675): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket(11675): bindListen(), new LocalSocket 
D/BluetoothSocket(11675): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11675): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b6a78e7
D/BluetoothSocket(11675): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): start: OK
I/io.jxcore.node.ConnectionHelper(11675): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11675): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11675): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): start: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11675): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3527): InactiveState{ what=139292 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3527): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setState: RUNNING
I/io.jxcore.node.ConnectionHelper(11675): start: OK
D/WifiP2pService( 3527): add a new client
,I/jxcore-log(11675): StartBroadcasting started ok
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=139265 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139265 }
D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3527): callSECApi what=74
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 3527): discovery change broadcast true
,I/jxcore-log(11675): [ { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log(11675):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log(11675):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log(11675):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log(11675):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log(11675):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log(11675):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log(11675):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log(11675):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log(11675):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log(11675):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log(11675):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 } ]
I/jxcore-log(11675): 
,I/jxcore-log(11675): startWithNextDevice
I/jxcore-log(11675): 
I/jxcore-log(11675): do fake peer & start
I/jxcore-log(11675): 
I/jxcore-log(11675): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:45:45.576Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:45:45.577Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log(11675): 
I/jxcore-log(11675): 2016-01-07T08:45:45.577Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1644)
,I/jxcore-log(11675): 2016-01-07T08:45:45.583Z SendDataTCPServer.js: TCP/IP server is bound to port: 44381
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11675): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper(11675): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper(11675): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onWifiStateChanged: State changed to 2
,I/io.jxcore.node.ConnectionHelper(11675): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11675): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery started successfully
D/WifiP2pService( 3527): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3836): P2P-FIND-STOPPED 
,I/chromium(11675): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery stopped successfully
I/chromium(11675): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 3527): InactiveState{ what=147493 },
D/WifiP2pService( 3527): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3527): discovery change broadcast false
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: RESTARTING
W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/WifiP2pService( 3527): InactiveState{ what=139268 }
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 5608): db_query_execute: result 1
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 5608): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccbe44 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,I/BluetoothBondStateMachine( 5608): Entering PendingCommandState State
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12832): MountEmulatedStorage()
I/libpersona(12832): KNOX_SDCARD checking this for 10102
E/Zygote  (12832): v2
I/libpersona(12832): KNOX_SDCARD not a persona
I/SELinux (12832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3527): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.common.receiver.AutoLaunchReceiver: pid=12832 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/SELinux (12832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12832): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 5608): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,D/HidService( 5608): getHidService(): returning com.android.bluetooth.hid.HidService@8996101
,D/SettingsProvider( 3527): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/TimaKeyStoreProvider(12832): TimaSignature is unavailable
D/HidService( 5608): Saved priority 58:3F:54:73:64:C0 = -1
,D/SettingsProvider( 3527): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
D/ActivityThread(12832): Added TimaKeyStore provider
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/SettingsProvider( 3527): name = bluetooth_headset_priority_58:3F:54:73:64:C0
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,I/BluetoothBondStateMachine( 5608): StableState(): Entering Off State
,D/ResourcesManager(12832): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager(12832): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode](12832): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager(12832): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(12832): mContext is not null
,I/VlingoAndroidCore(12832): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12859): MountEmulatedStorage()
E/Zygote  (12859): v2
I/libpersona(12859): KNOX_SDCARD checking this for 10034
I/libpersona(12859): KNOX_SDCARD not a persona
,I/SELinux (12859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=12859 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux (12859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12859): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12859): TimaSignature is unavailable
,D/ActivityThread(12859): Added TimaKeyStore provider
,W/bt-btif ( 5608): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5608): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onSocketConnected: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1644)
,D/ResourcesManager(12859): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Entering thread (ID: 1645)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): onBytesWritten: 66 bytes successfully written (thread ID: 1645)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Outgoing connection initialized (*handshake* thread ID: 1645)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1644)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): onBytesRead: Read 63 bytes successfully (thread ID: 1645)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Handshake succeeded with [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onHandshakeSucceeded: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Exiting thread (ID: 1645)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnected: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper(11675): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 G3-1]
D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper(11675): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11675): Entering thread (ID: 1646)
,D/io.jxcore.node.OutgoingSocketThread(11675): Server socket local port: 48867
I/io.jxcore.node.OutgoingSocketThread(11675): Now accepting connections...
,I/System.out(12859): Inside WakeupProvider
,E/DatabaseUtils(12859): Writing exception to parcel
E/DatabaseUtils(12859): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12859): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12859): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12859): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12859): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12859): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12859): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12859): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12859): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12859): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12859): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(12832): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(12832): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12832): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12832): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12832): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12832): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12832): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12832): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12832): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12832): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(12832): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(12832): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(12832): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(12832): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(12832): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(12832): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12832): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12832): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12832): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12832): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12832): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12832): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12832): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12832): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12832): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12832): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils(12859): Writing exception to parcel
E/DatabaseUtils(12859): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12859): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12859): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12859): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12859): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12859): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12859): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12859): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12859): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12859): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12859): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(12832): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(12832): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12832): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12832): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12832): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12832): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12832): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12832): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12832): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12832): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(12832): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(12832): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(12832): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(12832): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12832): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12832): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12832): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12832): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12832): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12832): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12832): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12832): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12832): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12832): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode](12832): [DLApplication]-Init Called!:false
W/[CarMode](12832): [CommonUtil]-=========================================
W/[CarMode](12832): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](12832): [CommonUtil]-=========================================
E/[CarMode](12832): [DLApplication]-Init Started!:true
I/[CarModeFW](12832): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](12832): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](12832): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](12832): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](12832): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](12832): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](12832): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](12832): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](12832): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](12832): ### android.os.Looper::loop(145)
I/[CarModeFW](12832): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](12832): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](12832): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](12832): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication(12859): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
,I/MessageDataHandler(12832): initialize
D/[CarModeFW](12832): CDH-initiazlieCaches : before sync
D/[CarModeFW](12832): CDH-initiazlieCaches : after sync
I/VlingoAndroidCore(12859): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
D/[CarModeFW](12832): CDH-buildContactCacheWireFrame : cur len =0
D/[CarModeFW](12832): CDH-ContactDataHandler initiazlieCaches time : 20
D/[CarModeFW](12832): CDH-initiazlieCaches : end sync
D/[CarModeFW](12832): DrivingManager-initialize...
I/SensorService( 3527): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3527): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3527): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3527): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3527): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,D/VlingoApplication(12859): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication(12859): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(12859): initQueue()
,I/MediaPlayer(12832): Need to enable context aware info
V/MediaPlayer-JNI(12832): native_setup
V/MediaPlayer(12832): constructor
,V/MediaPlayer(12832): setListener
,D/[CarModeFW](12832): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW](12832): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode](12832): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1452156349931
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1452156349931
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1452156349936
,D/[CarModeFW](12832): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 8
D/[CarMode](12832): [DLServiceManager]-updateLocationList
D/[CarMode](12832): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1452156349939
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1452156349940
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1452156349941
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/[CarModeFW](12832): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1452156349949
,D/[CarModeFW](12832): ContactDataHandler-getFavoriteContactList : cur len = 0
,F/DLApplication(12832): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 11
,I/[CarMode](12832): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW](12832): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 11
,E/Zygote  (12893): MountEmulatedStorage()
E/Zygote  (12893): v2
I/libpersona(12893): KNOX_SDCARD checking this for 10047
I/libpersona(12893): KNOX_SDCARD not a persona
,I/SELinux (12893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=12893 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12893): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/[CarMode](12832): [DLApplication]-Init End!:true
D/[CarModeFW](12832): CalllogDataHandler-getCalllogList : cur len = 0
,D/[CarMode](12832): [TAG]-phone sound mode is: 0
V/[CarMode](12832): [DLApplication]-savePreviousGpsState
,D/TP/SmsProvider( 3984): query,matched:2, calling pid = 12832
,D/TP/SmsProvider( 3984): query,matched:2, calling pid = 12832
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 42
D/TP/SmsProvider( 3984): match 2:Elapsed time : 0.737 ms
,D/TP/SmsProvider( 3984): match 2:Elapsed time : 2.203 ms
,V/[CarMode](12832): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/MessageDataHandler(12832):  getInboxList smsCursor : 43
,D/TP/MmsProvider( 3984): Query uri=content://mms/inbox, match=2, calling pid = 12832
,D/TP/MmsProvider( 3984): Query uri=content://mms, match=0, calling pid = 12832
,D/MessageDataHandler(12832):  getInboxList mmsCursor : 11
,I/MessageDataHandler(12832): getUnreadMessageCount :0
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 55
,D/MessageDataHandler(12832):  getInboxList mms,sms cursor join : 6
,D/TP/MmsSmsProvider( 3984): query,matched:0, calling pid = 12832
V/TP/MmsSmsProvider( 3984): getSimpleConversations entered.
,D/[CarMode](12832): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](12832): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/TP/MmsSmsProvider( 3984): match 0:Elapsed time : 5.308 ms
,D/TimaKeyStoreProvider(12893): TimaSignature is unavailable
,D/ActivityThread(12893): Added TimaKeyStore provider
,I/[CarMode](12832): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
,E/[CarMode](12832): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TP/MmsSmsProvider( 3984): query,matched:13, calling pid = 12832
,D/TP/MmsSmsProvider( 3984): match 13:Elapsed time : 3.222 ms
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G3-1 state is 11
,D/DialogFlow(12832): initQueue()
,D/MessageDataHandler(12832):  getInboxList address cursor : 15
,D/TP/MmsSmsProvider( 3984): query,matched:0, calling pid = 12832
V/TP/MmsSmsProvider( 3984): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3984): match 0:Elapsed time : 1.591 ms
I/ActivityManager( 3527): Killing 11428:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/MessageDataHandler(12832):  getInboxList thread cursor : 7
,D/ResourcesManager(12893): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(12893): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MessageDataHandler(12832):  thread, addr result: 8
I/[CarModeFW](12832): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 109
,I/[CarModeFW](12832): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 3
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 113
,I/io.jxcore.node.ConnectionHelper(11675): onListeningForIncomingConnections: Outgoing connection is using port 48867 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log(11675): 2016-01-07T08:45:50.051Z SendDataConnector.js: CLIENT connected to 48867, error: null
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:45:50.051Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11675): 
,I/io.jxcore.node.OutgoingSocketThread(11675): Incoming data from address: /127.0.0.1, port: 48867
,D/io.jxcore.node.OutgoingSocketThread(11675): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1647, name: Sender)
,I/io.jxcore.node.OutgoingSocketThread(11675): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread(11675): Exiting thread (ID: 1646)
,I/jxcore-log(11675): 2016-01-07T08:45:50.065Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11675): 
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1648, name: Receiver)
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2(12893): CalendarProvider2.onCreate() called
,E/Zygote  (12910): MountEmulatedStorage()
E/Zygote  (12910): v2
I/libpersona(12910): KNOX_SDCARD checking this for 10121
I/libpersona(12910): KNOX_SDCARD not a persona
,I/SELinux (12910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12910): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=12910 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,I/ActivityManager( 3527): Killing 11409:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/ActivityManager( 3527): Killing 11444:com.android.calendar/u0a164 (adj 15): bgCount ##32
,D/TimaKeyStoreProvider(12910): TimaSignature is unavailable
,D/ActivityThread(12910): Added TimaKeyStore provider
,D/ResourcesManager(12910): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
,D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,W/BackupManagerService( 3527): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/GMFPReceiver(12910): ::::::::Wearable0002::false
,I/ActivityManager( 3527): Killing 10728:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/GMFPReceiver(12910): onServiceConnected() : 1
,D/GMFPReceiver(12910): mBluetoothHeadset = true
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G3-1 state is 10
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
,D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
,D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
I/System.out(12859): INFO:Resource not found:/Common.properties Using default values
,D/GMFPReceiver(12910): ::::::::Wearable0002::false
,D/GMFPReceiver(12910): onServiceConnected() : 1
D/GMFPReceiver(12910): mBluetoothHeadset = true
,D/[CarModeFW](12832): LocationDataHandler-No schedules found.
,D/[CarModeFW](12832): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12932): MountEmulatedStorage()
,E/Zygote  (12932): v2
I/libpersona(12932): KNOX_SDCARD checking this for 10003
I/libpersona(12932): KNOX_SDCARD not a persona
,I/SELinux (12932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=12932 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
I/SELinux (12932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12932): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BootupListener( 3984): ACTION_DRIVELINK
,D/SettingsProvider( 3527): name = drivelink_navigation
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1001
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/BootupListener( 3984): NAVI : com.here.app.maps
,D/SettingsProvider( 3527): name = internet_call_settings_visibility
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1001
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/BootupListener( 3984): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/TimaKeyStoreProvider(12932): TimaSignature is unavailable
,D/ActivityThread(12932): Added TimaKeyStore provider
,D/ResourcesManager(12932): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(12932): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager(12932): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(12932): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(12932): Create SecureDbHelper
,D/IntelligenceServiceApplication(12932): onCreate()
,D/[CarModeFW](12832): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](12832): MyPlaceProvider-=============
D/[CarModeFW](12832): MyPlaceProvider-=============
D/[CarModeFW](12832): MyPlaceProvider-=============
D/[CarModeFW](12832): MyPlaceProvider-=============
D/[CarModeFW](12832): MyPlaceProvider-=============
D/[CarModeFW](12832): MyPlaceProvider-=============
D/[CarModeFW](12832): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](12832): MyPlaceProvider-==============
D/[CarModeFW](12832): MyPlaceProvider-==============
D/[CarModeFW](12832): MyPlaceProvider-==============
D/[CarModeFW](12832): MyPlaceProvider-==============
D/[CarModeFW](12832): MyPlaceProvider-==============
,D/[CarModeFW](12832): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1452156350436 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](12832): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(12832): loadLocationDestinationList is null
D/[CarModeFW](12832): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 498
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): Start timer timeout, starting now...
,D/WifiP2pService( 3527): InactiveState{ what=139265 }
D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61130
,D/WifiP2pService( 3527): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3527): callSECApi what=74
D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 3527): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/CalendarProvider2(12893): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12956): MountEmulatedStorage()
E/Zygote  (12956): v2
I/libpersona(12956): KNOX_SDCARD checking this for 10022
I/libpersona(12956): KNOX_SDCARD not a persona
,I/SELinux (12956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12956 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/lowmemorykiller( 2828): Error writing /proc/11562/oom_score_adj; errno=22
I/ActivityManager( 3527): Killing 11562:com.android.vending/u0a31 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12956): TimaSignature is unavailable
,D/ActivityThread(12956): Added TimaKeyStore provider
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12956): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12956): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12956): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/LocationWidgetApplication(12956): onCreate() : start
,D/LocationWidgetApplication(12956): countryCode = POLAND
,D/LocationWidgetUtils(12956): getUpcommingInstances() start: 1452156351440, end: 1452725999999
,D/LocationWidgetUtils(12956): getUpcommingInstances() DB begin time >= start:1452156351440, DB begin time <= end:1452725999999
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12978): MountEmulatedStorage()
E/Zygote  (12978): v2
I/libpersona(12978): KNOX_SDCARD checking this for 10163
I/libpersona(12978): KNOX_SDCARD not a persona
,I/SELinux (12978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=12978 uid=10163 gids={50163, 9997} abi=armeabi-v7a
E/SELinux (12978): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 12229:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12978): TimaSignature is unavailable
,D/ActivityThread(12978): Added TimaKeyStore provider
,D/ResourcesManager(12978): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(12978): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12978): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12997): MountEmulatedStorage()
I/libpersona(12997): KNOX_SDCARD checking this for 10164
E/Zygote  (12997): v2
I/libpersona(12997): KNOX_SDCARD not a persona
,I/SELinux (12997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=12997 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (12997): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Killing 11332:com.samsung.android.snote/u0a160 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12997): TimaSignature is unavailable
,D/ActivityThread(12997): Added TimaKeyStore provider
,D/ResourcesManager(12997): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12997): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12997): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12997): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12997): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationManagerService( 3527): getProviders()=[]
D/LocationManagerService( 3527): getProviders()=[passive]
D/LocationManagerService( 3527): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12956): mPrivacy is null
,W/ContextImpl(12956): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3527): Killing 11806:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,D/ContextFramework:PrivacyManager(12956): Service for PrivacyManager is connected
,D/LWLocationManager(12956): Privacy service : STATUS_PLACE
D/LWLocationManager(12956): updateLocationStatus()
,I/LocationWidgetFuctionData(12956): readDB
,I/LocationWidgetFuctionData(12956): selectedAppSize: 3
I/LocationWidgetFuctionData(12956): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(12956): selectedAppSize: 3
,I/LocationWidgetFuctionData(12956): selectedAppSize: 3
,I/LocationWidgetFuctionData(12956): selectedAppSize: 3
,I/LocationWidgetFuctionData(12956): selectedAppSize: 3
,E/LWLocationManager(12956): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(12956): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
,D/LWLocationManager(12956): setShouldUpdateLocationId
,D/LWLocationManager(12956): setShouldUpdateLocationId return false
D/LWLocationManager(12956): setShouldUpdateLocationId
,D/LWLocationManager(12956): setShouldUpdateLocationId return false
D/LWLocationManager(12956): setShouldUpdateLocationId
,D/LWLocationManager(12956): setShouldUpdateLocationId return false
D/LWLocationManager(12956): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 3527): !@Sync 17
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3527): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3527): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3527): SIOP:: AP = 220, PST = 210, CUR = 20
,W/art     (12893): Suspending all threads took: 9.691ms
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1648, thread name: Receiver): bt socket closed, read return: -1
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag,
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/io.jxcore.node.OutgoingSocketThread(11675): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
,I/io.jxcore.node.OutgoingSocketThread(11675): close
D/io.jxcore.node.OutgoingSocketThread(11675): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1648
D/io.jxcore.node.OutgoingSocketThread(11675): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1647
,D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11675): closeBluetoothSocketAndStreams
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@32e04732, channel: 5, state: CONNECTED
W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1647, thread name: Sender): Connection reset by peer
D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@32e04732, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dbbc83, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e515e00mSocket: android.net.LocalSocket@17493639 impl:android.net.LocalSocketImpl@21c7a47e fd:FileDescriptor[117]
E/io.jxcore.node.OutgoingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Connection reset by peer
D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@17493639 impl:android.net.LocalSocketImpl@21c7a47e fd:FileDescriptor[117]
W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Connection reset by peer
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@32e04732, channel: 5, state: CLOSED
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@32e04732, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1648, name: Receiver)
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1647, name: Sender)
,I/jxcore-log(11675): 2016-01-07T08:45:55.286Z SendDataConnector.js: CLIENT got error : Error: read ECONNRESET
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:45:55.288Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11675): 
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
I/jxcore-log(11675): 2016-01-07T08:45:55.291Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log(11675): 
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
,E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,I/jxcore-log(11675): 2016-01-07T08:46:00.292Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:00.299Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 13
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0,
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection,
,I/jxcore-log(11675): 2016-01-07T08:46:05.326Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:05.331Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:05.332Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:05.333Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1649)
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 5608): db_query_execute: result 1
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_CONNECTED
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: G3-1
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
D/[CarModeFW](12832): ConnectivityManager-handleMessage CONNECTION_COMPLETE
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,W/bt-btif ( 5608): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 5608): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onSocketConnected: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1649)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): onBytesWritten: 66 bytes successfully written (thread ID: 1650)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Outgoing connection initialized (*handshake* thread ID: 1650)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1649)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Entering thread (ID: 1650)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): onBytesRead: Read 63 bytes successfully (thread ID: 1650)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Handshake succeeded with [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onHandshakeSucceeded: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Exiting thread (ID: 1650)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnected: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 G3-1]
D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper(11675): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11675): Entering thread (ID: 1651)
,D/io.jxcore.node.OutgoingSocketThread(11675): Server socket local port: 48215
,I/io.jxcore.node.OutgoingSocketThread(11675): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper(11675): onListeningForIncomingConnections: Outgoing connection is using port 48215 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log(11675): 2016-01-07T08:46:07.647Z SendDataConnector.js: CLIENT connected to 48215, error: null
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:07.651Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11675): 
,I/io.jxcore.node.OutgoingSocketThread(11675): Incoming data from address: /127.0.0.1, port: 48215
,D/io.jxcore.node.OutgoingSocketThread(11675): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread(11675): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread(11675): Exiting thread (ID: 1651)
,I/jxcore-log(11675): 2016-01-07T08:46:07.676Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11675): 
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1653, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1652, name: Sender)
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65634
,I/jxcore-log(11675): 2016-01-07T08:46:08.631Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:59410
,I/jxcore-log(11675): 2016-01-07T08:46:08.692Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52480
,I/jxcore-log(11675): 2016-01-07T08:46:08.782Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42580
,I/jxcore-log(11675): 2016-01-07T08:46:08.844Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:32680
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/jxcore-log(11675): 2016-01-07T08:46:09.007Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11675): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 3527): InactiveState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,I/WifiStateMachine( 3527): callSECApi what=74
D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22780
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
D/WifiP2pService( 3527): InactiveState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/jxcore-log(11675): 2016-01-07T08:46:13.581Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11675): 
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 19
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/bt-btif ( 5608): dm_pm_timer expires
,W/bt-btif ( 5608): dm_pm_timer expires 0,
,W/bt-btif ( 5608): proc dm_pm_timer expires
,I/PowerManagerService( 3527): [PWL] Off : 455s ago
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12880
,I/jxcore-log(11675): 2016-01-07T08:46:20.858Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2980
,I/jxcore-log(11675): 2016-01-07T08:46:21.388Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:21.631Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:21.977Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:21.982Z SendDataConnector.js: got all data for this round
I/jxcore-log(11675): 
,I/jxcore-log(11675): oneRoundDownNow
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:21.991Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:21.993Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11675): 
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
,I/io.jxcore.node.OutgoingSocketThread(11675): close
D/io.jxcore.node.OutgoingSocketThread(11675): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1653
D/io.jxcore.node.OutgoingSocketThread(11675): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1652
,D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1652, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread(11675): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11675): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@2d939ddf, channel: 5, state: CONNECTED
D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@2d939ddf, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b6e5a2c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@377dfcf5mSocket: android.net.LocalSocket@1e358a8a impl:android.net.LocalSocketImpl@1dbe38fb fd:FileDescriptor[117]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@1e358a8a impl:android.net.LocalSocketImpl@1dbe38fb fd:FileDescriptor[117]
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1653, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@2d939ddf, channel: 5, state: CLOSED
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@2d939ddf, channel: 5, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1652, name: Sender)
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1653, name: Receiver)
,I/jxcore-log(11675): 2016-01-07T08:46:22.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log(11675): 
,W/bt-btif ( 5608): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log(11675): ---- round done--------
I/jxcore-log(11675): 
,I/jxcore-log(11675): startWithNextDevice
I/jxcore-log(11675): 
,I/jxcore-log(11675): do fake peer & start
I/jxcore-log(11675): 
,I/jxcore-log(11675): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:22.033Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:22.034Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:22.034Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [90:E7:C4:F6:69:77 HTC One M8s]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to null in address 90:E7:C4:F6:69:77
,I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 1654)
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,E/Watchdog( 3527): !@Sync 18
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccbe44 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1],
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] already in the list, will not add again
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 19
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: G3-1
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/WifiP2pService( 3527): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 3527): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/WifiP2pService( 3527): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 3527): P2pEnabledState add service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
I/BluetoothBondStateMachine( 5608): Entering PendingCommandState State
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED HTC One M8s state is 11
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0002::false
D/GMFPReceiver(12910): onServiceConnected() : 1
D/GMFPReceiver(12910): mBluetoothHeadset = true
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services,
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 5608): Failed to remove device: 90:E7:C4:F6:69:77
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/HidService( 5608): getHidService(): returning com.android.bluetooth.hid.HidService@8996101
,D/SettingsProvider( 3527): name = bluetooth_input_device_priority_90:E7:C4:F6:69:77
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
,D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,D/HidService( 5608): Saved priority 90:E7:C4:F6:69:77 = -1
,D/SettingsProvider( 3527): name = bluetooth_a2dp_sink_priority_90:E7:C4:F6:69:77
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
,D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,D/SettingsProvider( 3527): name = bluetooth_headset_priority_90:E7:C4:F6:69:77
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
,D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,I/BluetoothBondStateMachine( 5608): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED HTC One M8s state is 10
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0002::false
,D/GMFPReceiver(12910): onServiceConnected() : 1
D/GMFPReceiver(12910): mBluetoothHeadset = true
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/bt-btif ( 5608): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5608): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 5608): bta_dm_pm_ssr:2, lat:1200,
,E/BluetoothRemoteDevices( 5608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onSocketConnected: [90:E7:C4:F6:69:77 HTC One M8s]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1654)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): onBytesWritten: 66 bytes successfully written (thread ID: 1655)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Outgoing connection initialized (*handshake* thread ID: 1655)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1654)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Entering thread (ID: 1655)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): onBytesRead: Read 70 bytes successfully (thread ID: 1655)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Handshake succeeded with [90:E7:C4:F6:69:77 HTC One M8s]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Exiting thread (ID: 1655)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnected: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC One M8s], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper(11675): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11675): Entering thread (ID: 1656)
,D/io.jxcore.node.OutgoingSocketThread(11675): Server socket local port: 42404
,I/io.jxcore.node.OutgoingSocketThread(11675): Now accepting connections...
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11675): onListeningForIncomingConnections: Outgoing connection is using port 42404 (peer ID: 90:E7:C4:F6:69:77)
,I/jxcore-log(11675): 2016-01-07T08:46:29.520Z SendDataConnector.js: CLIENT connected to 42404, error: null
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:29.522Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11675): 
,I/io.jxcore.node.OutgoingSocketThread(11675): Incoming data from address: /127.0.0.1, port: 42404
D/io.jxcore.node.OutgoingSocketThread(11675): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread(11675): startStreamCopyingThreads: OK
,I/jxcore-log(11675): 2016-01-07T08:46:29.544Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11675): 
D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1657, name: Sender)
D/io.jxcore.node.OutgoingSocketThread(11675): Exiting thread (ID: 1656)
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1658, name: Receiver)
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66624
,I/jxcore-log(11675): 2016-01-07T08:46:30.487Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58420
,I/jxcore-log(11675): 2016-01-07T08:46:30.624Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48520
,I/jxcore-log(11675): 2016-01-07T08:46:30.895Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38620
,I/jxcore-log(11675): 2016-01-07T08:46:31.022Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:26740
,I/jxcore-log(11675): 2016-01-07T08:46:31.284Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11675): 
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17830
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,I/jxcore-log(11675): 2016-01-07T08:46:31.458Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11675): 
V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5608): check_cod: remote_cod = 0x5a020c
V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
I/BluetoothBondStateMachine( 5608): Entering PendingCommandState State
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED A5-1 state is 11
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
,D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0002::false
D/GMFPReceiver(12910): onServiceConnected() : 1
,D/GMFPReceiver(12910): mBluetoothHeadset = true
,D/        ( 5608): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7930
,I/jxcore-log(11675): 2016-01-07T08:46:31.594Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11675): 
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 5608): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/HidService( 5608): getHidService(): returning com.android.bluetooth.hid.HidService@8996101
,W/bt-btif ( 5608): new conn_srvc id:26, app_id:255
,W/bt-btif ( 5608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 5608): bta_dm_pm_ssr:2, lat:1200
,D/SettingsProvider( 3527): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
,D/BluetoothSocket(11675): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2c7ced18
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
,E/BluetoothRemoteDevices( 5608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Incoming connection accepted
,D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,D/HidService( 5608): Saved priority 7C:F9:0E:37:96:AB = -1
,D/SettingsProvider( 3527): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/SettingsProvider( 3527): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
,D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,I/BluetoothBondStateMachine( 5608): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Incoming connection initialized (thread ID: 1659)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Entering thread (ID: 1659)
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): onBytesRead: Read 63 bytes successfully (thread ID: 1659)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Got valid identity from [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): onBytesWritten: 66 bytes successfully written (thread ID: 1659)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): removeThreadFromList: Removing thread with ID 1659
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Handshake thread disposed (thread ID: 1659)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Exiting thread (ID: 1659)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnected: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB A5-1]
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
,D/io.jxcore.node.ConnectionHelper(11675): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread(11675): Entering thread (ID: 1660)
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10539
,I/io.jxcore.node.IncomingSocketThread(11675): Local host address: localhost/127.0.0.1, port: 44381
D/io.jxcore.node.IncomingSocketThread(11675): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1661, name: Sender)
I/io.jxcore.node.IncomingSocketThread(11675): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread(11675): Exiting thread (ID: 1660)
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1662, name: Receiver)
D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log(11675): 2016-01-07T08:46:32.187Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11675): 
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED A5-1 state is 10
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,I/jxcore-log(11675): 2016-01-07T08:46:32.193Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11675): 
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0002::false
,D/GMFPReceiver(12910): onServiceConnected() : 1
D/GMFPReceiver(12910): mBluetoothHeadset = true
,I/jxcore-log(11675): 2016-01-07T08:46:33.369Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.373Z SendDataTCPServer.js: TCP/IP server has received 3036 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.387Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.398Z SendDataTCPServer.js: TCP/IP server has received 5060 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc004 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11675): 2016-01-07T08:46:33.417Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.426Z SendDataTCPServer.js: TCP/IP server has received 7084 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.433Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.450Z SendDataTCPServer.js: TCP/IP server has received 9108 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:33.938Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.467Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.612Z SendDataTCPServer.js: TCP/IP server has received 11132 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.635Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.673Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.675Z SendDataConnector.js: got all data for this round
I/jxcore-log(11675): 
,I/jxcore-log(11675): oneRoundDownNow
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.677Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.679Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11675): 
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
,I/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.IncomingSocketThread(11675): close
D/io.jxcore.node.IncomingSocketThread(11675): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1658
D/io.jxcore.node.IncomingSocketThread(11675): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1657
D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1657, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread(11675): closeBluetoothSocketAndStreams
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@39fe7371, channel: 6, state: CONNECTED
D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@39fe7371, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32e9c556, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e2d69d7mSocket: android.net.LocalSocket@22dfc2c4 impl:android.net.LocalSocketImpl@2e35d5ad fd:FileDescriptor[117]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@22dfc2c4 impl:android.net.LocalSocketImpl@2e35d5ad fd:FileDescriptor[117]
W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1658, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@39fe7371, channel: 6, state: CLOSED
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@39fe7371, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1658, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1657, name: Sender)
,I/jxcore-log(11675): 2016-01-07T08:46:34.705Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log(11675): 
,I/jxcore-log(11675): ---- round done--------
I/jxcore-log(11675): 
,I/jxcore-log(11675): startWithNextDevice
I/jxcore-log(11675): 
I/jxcore-log(11675): do fake peer & start
I/jxcore-log(11675): 
I/jxcore-log(11675): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.708Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
I/jxcore-log(11675): 2016-01-07T08:46:34.709Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:34.710Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper(11675): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: null 00:F4:6F:30:E0:6C
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 1663)
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 20
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc004 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc004 rs_disc_pending=0,
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
,W/bt-btif ( 5608): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] already in the list, will not add again
,I/jxcore-log(11675): 2016-01-07T08:46:37.047Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:37.051Z SendDataTCPServer.js: TCP/IP server has received 15180 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:37.071Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:37.085Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data
I/jxcore-log(11675): 
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11675): 2016-01-07T08:46:37.511Z SendDataTCPServer.js: TCP/IP server has received 19228 bytes of data
I/jxcore-log(11675): 
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 5608): aclStateChangeCallback: Device is NULL
,I/jxcore-log(11675): 2016-01-07T08:46:37.667Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:37.680Z SendDataTCPServer.js: TCP/IP server has received 21252 bytes of data
I/jxcore-log(11675): 
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,E/bt-btif ( 5608): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 5608): invalid rfc slot id: 10
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@4d4e0e2, channel: -1, state: INIT
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@4d4e0e2, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bf4cc73, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31784730mSocket: android.net.LocalSocket@35071fa9 impl:android.net.LocalSocketImpl@2564292e fd:FileDescriptor[117]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@35071fa9 impl:android.net.LocalSocketImpl@2564292e fd:FileDescriptor[117]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1663)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1663)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1663)
,I/jxcore-log(11675): 2016-01-07T08:46:38.141Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log(11675): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): shutdown (thread ID: 1663)
,I/jxcore-log(11675): 2016-01-07T08:46:38.155Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:38.156Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:38.158Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log(11675): 
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@4d4e0e2, channel: -1, state: CLOSED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log(11675): 2016-01-07T08:46:38.187Z SendDataTCPServer.js: TCP/IP server has received 25588 bytes of data
I/jxcore-log(11675): 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc004 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc384 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11675): 2016-01-07T08:46:38.885Z SendDataTCPServer.js: TCP/IP server has received 27612 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:38.904Z SendDataTCPServer.js: TCP/IP server has received 28624 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.390Z SendDataTCPServer.js: TCP/IP server has received 29636 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.425Z SendDataTCPServer.js: TCP/IP server has received 30648 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.437Z SendDataTCPServer.js: TCP/IP server has received 31660 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.471Z SendDataTCPServer.js: TCP/IP server has received 33684 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.474Z SendDataTCPServer.js: TCP/IP server has received 34696 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.477Z SendDataTCPServer.js: TCP/IP server has received 35708 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.483Z SendDataTCPServer.js: TCP/IP server has received 36720 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:39.490Z SendDataTCPServer.js: TCP/IP server has received 37732 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:40.006Z SendDataTCPServer.js: TCP/IP server has received 38744 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:40.014Z SendDataTCPServer.js: TCP/IP server has received 39756 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: HTC One M8s
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/jxcore-log(11675): 2016-01-07T08:46:41.237Z SendDataTCPServer.js: TCP/IP server has received 40768 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:41.256Z SendDataTCPServer.js: TCP/IP server has received 41780 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/WifiP2pService( 3527): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,I/jxcore-log(11675): 2016-01-07T08:46:43.161Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:43.166Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:24844,
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 5608): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,I/jxcore-log(11675): 2016-01-07T08:46:45.134Z SendDataTCPServer.js: TCP/IP server has received 42792 bytes of data
I/jxcore-log(11675): 
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
D/WifiP2pService( 3527): P2pEnabledState receive service response
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 20
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 XT1072] already in the list, will not add again
,I/jxcore-log(11675): 2016-01-07T08:46:45.436Z SendDataTCPServer.js: TCP/IP server has received 43804 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11675): 2016-01-07T08:46:46.794Z SendDataTCPServer.js: TCP/IP server has received 44816 bytes of data
I/jxcore-log(11675): ,
,I/jxcore-log(11675): 2016-01-07T08:46:46.821Z SendDataTCPServer.js: TCP/IP server has received 48864 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:46.895Z SendDataTCPServer.js: TCP/IP server has received 49876 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:46.898Z SendDataTCPServer.js: TCP/IP server has received 51900 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:46.930Z SendDataTCPServer.js: TCP/IP server has received 52912 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:47.417Z SendDataTCPServer.js: TCP/IP server has received 53924 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11675): 2016-01-07T08:46:48.044Z SendDataTCPServer.js: TCP/IP server has received 54936 bytes of data
I/jxcore-log(11675): 
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C,
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection,
,I/jxcore-log(11675): 2016-01-07T08:46:48.186Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:48.191Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:48.192Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:48.193Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,W/io.jxcore.node.ConnectionHelper(11675): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 1665)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils(11675): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11675): 2016-01-07T08:46:48.645Z SendDataTCPServer.js: TCP/IP server has received 55948 bytes of data
I/jxcore-log(11675): 
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5608): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
I/BluetoothBondStateMachine( 5608): Entering PendingCommandState State
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED S5-1 state is 11
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0002::false
,D/GMFPReceiver(12910): onServiceConnected() : 1
D/GMFPReceiver(12910): mBluetoothHeadset = true
,I/jxcore-log(11675): 2016-01-07T08:46:49.858Z SendDataTCPServer.js: TCP/IP server has received 57972 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:49.864Z SendDataTCPServer.js: TCP/IP server has received 58984 bytes of data
I/jxcore-log(11675): 
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5608): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 5608): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/SecContentProvider( 3527): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 5608): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/HidService( 5608): getHidService(): returning com.android.bluetooth.hid.HidService@8996101
,D/SettingsProvider( 3527): name = bluetooth_input_device_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 1002
,D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,D/HidService( 5608): Saved priority 7C:F9:0E:34:8A:A0 = -1
,D/SettingsProvider( 3527): name = bluetooth_a2dp_sink_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
,D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,D/SettingsProvider( 3527): name = bluetooth_headset_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
,D/SettingsProvider( 3527): selectionArgs: 1002
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
,I/BluetoothBondStateMachine( 5608): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,D/[CarMode](12832): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12832): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED S5-1 state is 10
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(12910): BTStateChangeCB is registed
,E/BluetoothHeadset(12910): BluetoothHeadset service is binded
D/GMFPReceiver(12910): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(12910): jangil::setProperties()
,D/GMFPReceiver(12910): jangil::printBTStatus()
,D/SettingsProvider( 3527): name = Wearable0001
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3527): ret = -1
,D/GMFPReceiver(12910): ::::::::Wearable0001::false
,D/SettingsProvider( 3527): name = Wearable0002
D/SettingsProvider( 3527): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3527): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3527): selectionArgs: false
D/SettingsProvider( 3527): selectionArgs: 10121
D/SecContentProvider( 3527): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3527): ret = -1
D/GMFPReceiver(12910): ::::::::Wearable0002::false
D/GMFPReceiver(12910): onServiceConnected() : 1
D/GMFPReceiver(12910): mBluetoothHeadset = true
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 5608): db_query_execute: result 1
E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=1
W/bt-btif ( 5608): bta_dm_check_av:0
W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,D/io.jxcore.node.ConnectionHelper(11675): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,E/Watchdog( 3527): !@Sync 19
,W/bt-btif ( 5608): new conn_srvc id:26, app_id:255
,W/bt-btif ( 5608): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 5608): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket(11675): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@37c5bccf
,E/BluetoothRemoteDevices( 5608): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Incoming connection initialized (thread ID: 1666)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Entering thread (ID: 1666)
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
,D/[CarModeFW](12832): ConnectivityManager-handleMessage CONNECTION_COMPLETE
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14),
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,E/bt-btif ( 5608): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 5608): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): onBytesRead: Read 63 bytes successfully (thread ID: 1666)
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@15d2a65c, channel: 1, state: INIT
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@15d2a65c, channel: 1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@890d65, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d8daa3amSocket: android.net.LocalSocket@20b56eb impl:android.net.LocalSocketImpl@3811cc48 fd:FileDescriptor[117]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@20b56eb impl:android.net.LocalSocketImpl@3811cc48 fd:FileDescriptor[117]
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@15d2a65c, channel: 1, state: CLOSED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): onBytesWritten: 66 bytes successfully written (thread ID: 1666)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): removeThreadFromList: Removing thread with ID 1666
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Handshake thread disposed (thread ID: 1666)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11675): Exiting thread (ID: 1666)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 S5-1]
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[118]}
,I/io.jxcore.node.ConnectionHelper(11675): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
,D/io.jxcore.node.ConnectionHelper(11675): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread(11675): Entering thread (ID: 1667)
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10539
,I/io.jxcore.node.IncomingSocketThread(11675): Local host address: localhost/127.0.0.1, port: 44381
,I/jxcore-log(11675): 2016-01-07T08:46:54.274Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11675): 
,D/io.jxcore.node.IncomingSocketThread(11675): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11675): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread(11675): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread(11675): Exiting thread (ID: 1667)
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1669, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11675): Entering thread (ID: 1668, name: Sender)
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,E/bt-btif ( 5608): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 5608): invalid rfc slot id: 13
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@13821ae1, channel: -1, state: INIT
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@13821ae1, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d9c3006, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1cc676c7mSocket: android.net.LocalSocket@1d9b64f4 impl:android.net.LocalSocketImpl@3ca4841d fd:FileDescriptor[118]
D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@1d9b64f4 impl:android.net.LocalSocketImpl@3ca4841d fd:FileDescriptor[118]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1665)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1665)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1665)
,I/jxcore-log(11675): 2016-01-07T08:46:54.312Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
I/jxcore-log(11675): 2016-01-07T08:46:54.313Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:54.313Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log(11675): 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): shutdown (thread ID: 1665)
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@13821ae1, channel: -1, state: CLOSED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 21
,I/jxcore-log(11675): 2016-01-07T08:46:55.619Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.721Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.731Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.755Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.773Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.781Z SendDataTCPServer.js: TCP/IP server has received 9204 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.792Z SendDataTCPServer.js: TCP/IP server has received 11228 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.820Z SendDataTCPServer.js: TCP/IP server has received 12240 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.859Z SendDataTCPServer.js: TCP/IP server has received 13252 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.870Z SendDataTCPServer.js: TCP/IP server has received 14264 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.910Z SendDataTCPServer.js: TCP/IP server has received 15276 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.917Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.921Z SendDataTCPServer.js: TCP/IP server has received 17396 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.924Z SendDataTCPServer.js: TCP/IP server has received 18408 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.949Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:55.965Z SendDataTCPServer.js: TCP/IP server has received 23468 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.000Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.016Z SendDataTCPServer.js: TCP/IP server has received 27612 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.105Z SendDataTCPServer.js: TCP/IP server has received 28624 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.111Z SendDataTCPServer.js: TCP/IP server has received 29636 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.307Z SendDataTCPServer.js: TCP/IP server has received 30648 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.321Z SendDataTCPServer.js: TCP/IP server has received 31660 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.357Z SendDataTCPServer.js: TCP/IP server has received 32672 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.480Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.509Z SendDataTCPServer.js: TCP/IP server has received 33780 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.549Z SendDataTCPServer.js: TCP/IP server has received 38840 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.585Z SendDataTCPServer.js: TCP/IP server has received 42984 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.641Z SendDataTCPServer.js: TCP/IP server has received 43996 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.678Z SendDataTCPServer.js: TCP/IP server has received 46020 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.704Z SendDataTCPServer.js: TCP/IP server has received 48044 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.730Z SendDataTCPServer.js: TCP/IP server has received 50068 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:56.792Z SendDataTCPServer.js: TCP/IP server has received 51080 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.012Z SendDataTCPServer.js: TCP/IP server has received 52092 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.141Z SendDataTCPServer.js: TCP/IP server has received 53104 bytes of data
I/jxcore-log(11675): 
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11675): 2016-01-07T08:46:57.203Z SendDataTCPServer.js: TCP/IP server has received 56140 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.304Z SendDataTCPServer.js: TCP/IP server has received 57152 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.313Z SendDataTCPServer.js: TCP/IP server has received 58164 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.342Z SendDataTCPServer.js: TCP/IP server has received 59176 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.489Z SendDataTCPServer.js: TCP/IP server has received 60188 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:57.643Z SendDataTCPServer.js: TCP/IP server has received 62212 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc384 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11675): 2016-01-07T08:46:57.978Z SendDataTCPServer.js: TCP/IP server has received 63224 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:58.085Z SendDataTCPServer.js: TCP/IP server has received 66260 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,I/jxcore-log(11675): 2016-01-07T08:46:58.351Z SendDataTCPServer.js: TCP/IP server has received 70308 bytes of data
I/jxcore-log(11675): 
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
,E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11675): 2016-01-07T08:46:59.315Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.343Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.346Z SendDataTCPServer.js: TCP/IP server has received 72332 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.381Z SendDataTCPServer.js: TCP/IP server has received 77392 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.384Z SendDataTCPServer.js: TCP/IP server has received 78404 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.431Z SendDataTCPServer.js: TCP/IP server has received 80428 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.445Z SendDataTCPServer.js: TCP/IP server has received 81440 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.481Z SendDataTCPServer.js: TCP/IP server has received 83464 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.500Z SendDataTCPServer.js: TCP/IP server has received 88524 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.548Z SendDataTCPServer.js: TCP/IP server has received 91560 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.562Z SendDataTCPServer.js: TCP/IP server has received 92572 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.595Z SendDataTCPServer.js: TCP/IP server has received 94596 bytes of data
I/jxcore-log(11675): 
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3527): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 3527): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,I/jxcore-log(11675): 2016-01-07T08:46:59.798Z SendDataTCPServer.js: TCP/IP server has received 95608 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.801Z SendDataTCPServer.js: TCP/IP server has received 96620 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.881Z SendDataTCPServer.js: TCP/IP server has received 98644 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.920Z SendDataTCPServer.js: TCP/IP server has received 99656 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:46:59.924Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,W/bt-btif ( 5608): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1669, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread(11675): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1667
,D/io.jxcore.node.IncomingSocketThread(11675): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1669
,D/io.jxcore.node.IncomingSocketThread(11675): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1668
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1668, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread(11675): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@3dbb4692, channel: 6, state: CONNECTED
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@3dbb4692, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f29b863, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a83dc60mSocket: android.net.LocalSocket@98a4519 impl:android.net.LocalSocketImpl@3b4339de fd:FileDescriptor[115]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@98a4519 impl:android.net.LocalSocketImpl@3b4339de fd:FileDescriptor[115]
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@3dbb4692, channel: 6, state: CLOSED
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@3dbb4692, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1668, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1669, name: Receiver),
,I/jxcore-log(11675): 2016-01-07T08:47:00.913Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc544 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,W/bt-rfcomm( 5608): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 5608): RFCOMM_DisconnectInd LCID:0x4b
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C,
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection,
,I/jxcore-log(11675): 2016-01-07T08:47:04.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:04.368Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:04.370Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:04.371Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper(11675): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 1671)
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 5608): db_query_execute: result 1
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 21
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5-1
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_CONNECTED
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
D/[CarModeFW](12832): ConnectivityManager-handleMessage CONNECTION_COMPLETE
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc384 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,E/bt-btif ( 5608): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@16f577bf, channel: -1, state: INIT
,W/bt-btif ( 5608): invalid rfc slot id: 14,
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@16f577bf, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dba5e8c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d7119d5mSocket: android.net.LocalSocket@1ec515ea impl:android.net.LocalSocketImpl@393d0db fd:FileDescriptor[117]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@1ec515ea impl:android.net.LocalSocketImpl@393d0db fd:FileDescriptor[117]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1671)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1671)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1671)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log(11675): 2016-01-07T08:47:06.167Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:06.168Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:06.170Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log(11675): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): shutdown (thread ID: 1671)
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@16f577bf, channel: -1, state: CLOSED
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,I/jxcore-log(11675): 2016-01-07T08:47:10.106Z SendDataTCPServer.js: TCP/IP server has received 59996 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:10.112Z SendDataTCPServer.js: TCP/IP server has received 61008 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:10.704Z SendDataTCPServer.js: TCP/IP server has received 62020 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:10.738Z SendDataTCPServer.js: TCP/IP server has received 64044 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:11.173Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:11.177Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:11.321Z SendDataTCPServer.js: TCP/IP server has received 67080 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:11.324Z SendDataTCPServer.js: TCP/IP server has received 68092 bytes of data
I/jxcore-log(11675): 
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log(11675): 2016-01-07T08:47:11.907Z SendDataTCPServer.js: TCP/IP server has received 69104 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:11.923Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:12.522Z SendDataTCPServer.js: TCP/IP server has received 71128 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:13.128Z SendDataTCPServer.js: TCP/IP server has received 72140 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:13.146Z SendDataTCPServer.js: TCP/IP server has received 74164 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:13.762Z SendDataTCPServer.js: TCP/IP server has received 75176 bytes of data
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:14.987Z SendDataTCPServer.js: TCP/IP server has received 76188 bytes of data
I/jxcore-log(11675): 
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 20
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C,
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log(11675): 2016-01-07T08:47:16.197Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:16.200Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:16.203Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:16.207Z SendDataConnector.js: do connect now
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper(11675): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper(11675): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper(11675): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 1673)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils(11675): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 5608): db_query_execute: result 1
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 228, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3527): stay LED for fully charged
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 00:f4:6f:30:e0:6c
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 6:16653,
D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1,
,W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_CONNECTED
,D/BluetoothNotiBroadcastReceiver( 8615): onReceive
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
D/[CarModeFW](12832): ConnectivityManager-handleMessage CONNECTION_COMPLETE
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,I/jxcore-log(11675): 2016-01-07T08:47:19.428Z SendDataTCPServer.js: TCP/IP server has received 77200 bytes of data
I/jxcore-log(11675): 
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc384 rs_disc_pending=1
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,D/TimaService( 3527): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3527): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3527): TimaServiceHandler.handleMessage what =1
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,E/bt-btif ( 5608): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 5608): invalid rfc slot id: 15
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@33f4d778, channel: 1, state: INIT
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@33f4d778, channel: 1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17b67e51, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36d6a6b6mSocket: android.net.LocalSocket@26f49fb7 impl:android.net.LocalSocketImpl@1d5bf324 fd:FileDescriptor[117]
D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@26f49fb7 impl:android.net.LocalSocketImpl@1d5bf324 fd:FileDescriptor[117]
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@33f4d778, channel: 1, state: CLOSED
,D/BluetoothUtils(11675): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter(11675): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5608): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11675): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,I/jxcore-log(11675): 2016-01-07T08:47:21.861Z SendDataTCPServer.js: TCP/IP server has received 78212 bytes of data
I/jxcore-log(11675): 
,W/bt-sdp  ( 5608): process_service_search_attr_rsp
,E/bt-btif ( 5608): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@3613ae8d, channel: -1, state: INIT
,W/bt-btif ( 5608): invalid rfc slot id: 16
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@3613ae8d, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@139e7842, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28298053mSocket: android.net.LocalSocket@11f71d90 impl:android.net.LocalSocketImpl@1e99a689 fd:FileDescriptor[117]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@11f71d90 impl:android.net.LocalSocketImpl@1e99a689 fd:FileDescriptor[117]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1673)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1673)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): Exiting thread (thread ID: 1673)
,I/jxcore-log(11675): 2016-01-07T08:47:22.127Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11675): shutdown (thread ID: 1673)
,I/jxcore-log(11675): 2016-01-07T08:47:22.133Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:22.135Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log(11675): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@3613ae8d, channel: -1, state: CLOSED
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 5608): db_query_execute: result 1,
,E/Watchdog( 3527): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3527): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3527): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *,
D/IOP_DB_BT( 5608): db_query_execute: result 1,
W/bt-btif ( 5608): info:x10
,D/        ( 5608): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5608): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc704 rs_disc_pending=0
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3527): P2pEnabledState clear service request
,D/WifiP2pService( 3527): InactiveState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,W/ProcessCpuTracker( 3527): Skipping unknown process pid 13519
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiP2pService( 3527): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 3527): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 3527): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 19
,D/WifiP2pService( 3527): InactiveState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
,D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,I/jxcore-log(11675): timeout now
I/jxcore-log(11675): 
,I/jxcore-log(11675): weAreDoneNow, resultArray.length: 2
I/jxcore-log(11675): 
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag,
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,I/jxcore-log(11675): sendReportNow
I/jxcore-log(11675): 
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
,D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,I/jxcore-log(11675): done, now sending data to server
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:25.666Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:25.668Z SendDataConnector.js: Stop retry timer
I/jxcore-log(11675): 
,D/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper(11675): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log(11675): 2016-01-07T08:47:25.673Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log(11675): 
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=0, deviceClass=0]
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothClassifier( 4037): Bluetooth Device Name: S5mini-1
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
,D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,W/bt-btif ( 5608): invalid rfc slot id: 5
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1662, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread(11675): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1660
,D/io.jxcore.node.IncomingSocketThread(11675): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1662
D/io.jxcore.node.IncomingSocketThread(11675): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11675): doStop: Thread ID: 1661
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11675): Either failed to read from the output stream or write to the input stream (thread ID: 1661, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread(11675): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11675): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread(11675): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread(11675): closeBluetoothSocketAndStreams
D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@2f1fd68e, channel: 6, state: CONNECTED
,D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@2f1fd68e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c1ceaf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30d882bcmSocket: android.net.LocalSocket@1d6d2245 impl:android.net.LocalSocketImpl@e46cd9a fd:FileDescriptor[120]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@1d6d2245 impl:android.net.LocalSocketImpl@e46cd9a fd:FileDescriptor[120]
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@2f1fd68e, channel: 6, state: CLOSED
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@2f1fd68e, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper(11675): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1661, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11675): Exiting thread (ID: 1662, name: Receiver)
,I/jxcore-log(11675): 2016-01-07T08:47:26.948Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11675): 
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: A5-1
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/btif_config_util( 5608): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/BatteryService( 3527): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/PowerManagerService( 3527): [PWL] Off : 525s ago
I/PowerManagerService( 3527): [PWL]   PowerManagerService.WakeLocks: ref count=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
,I/PowerManagerService( 3527): [PWL]     mWakeLockSummary : 0x1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/PowerManagerService( 3527): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5608, ws=null) (elapsedTime=67840)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1],
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 19
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 3527): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3527): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/WifiP2pService( 3527): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/WifiP2pService( 3527): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 3527): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3527): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3527): P2pEnabledState add service request
,D/WifiP2pManager(11675): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service request added successfully
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 3527): InactiveState{ what=139310 },
D/WifiP2pService( 3527): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3527): P2pEnabledState discover services
,D/WifiService( 3527): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3527): callSECApi what=74
D/WifiStateMachine( 3527): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3527): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3836): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service discovery started successfully
,I/ActivityManager( 3527): Killing 11878:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##31
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3527): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3527): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3527): stay LED for fully charged
,I/MotionRecognitionService( 3527): Plugged
,I/MotionRecognitionService( 3527): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5608): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5608): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3836): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=147477 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3527): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3527): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3527): Received list of peers.
D/WifiDisplayController( 3527):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3527):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInf,o : null
D/WifiP2pService( 3527): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3527): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3527): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 },
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 3527): InactiveState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3527): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11675): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper(11675): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/IOP_DB_BT( 5608): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5608): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5608): db_query_execute: result 1
,E/bt-btm  ( 5608): tBTM_SEC_DEV:0xb3ccc704 rs_disc_pending=1
,E/bt-btm  ( 5608): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5608): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 5608): bta_dm_check_av:0
,W/bt-btif ( 5608): btif_dm_cback : unhandled event (14)
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 3691): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8615): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8615): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3691): isGear1: device is not B1!
,D/BluetoothAdapterService( 5608): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16fdce27
D/BtConfig.SecureMode( 5608): isSecureModeOn:false
,D/SecContentProvider( 3527): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12832): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12832): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothPbapService( 5608): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12832): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12832): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4037): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4037): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/SSRM:n  ( 3527): SIOP:: AP = 210, PST = 210, CUR = 20
,I/jxcore-log(11675): teardown
I/jxcore-log(11675): 
,I/jxcore-log(11675): testSendData stopped
I/jxcore-log(11675): 
,I/io.jxcore.node.ConnectionHelper(11675): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): shutdown
,D/BluetoothSocket(11675): close() in, this: android.bluetooth.BluetoothSocket@5e6a6cb, channel: 6, state: LISTENING
D/BluetoothSocket(11675): close() this: android.bluetooth.BluetoothSocket@5e6a6cb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b6a78e7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16090ea8mSocket: android.net.LocalSocket@22429dc1 impl:android.net.LocalSocketImpl@26b42966 fd:FileDescriptor[116]
,D/BluetoothSocket(11675): Closing mSocket: android.net.LocalSocket@22429dc1 impl:android.net.LocalSocketImpl@26b42966 fd:FileDescriptor[116]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11675): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11675): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11675): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11675): stop: Stopping services
,D/WifiP2pService( 3527): InactiveState{ what=139298 }
,D/WifiP2pService( 3527): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3527): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3527): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): setState: NOT_INITIALIZED
,I/wpa_supplicant( 3836): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11675): release: No more listeners, de-initializing...
,D/WifiP2pService( 3527): InactiveState{ what=147493 }
D/WifiP2pService( 3527): P2pEnabledState{ what=147493 }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11675): release: No more listeners, de-initializing...
D/WifiP2pService( 3527): discovery change broadcast false
,D/WifiP2pService( 3527): InactiveState{ what=139307 }
D/WifiP2pService( 3527): P2pEnabledState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11675): setState: NOT_STARTED
D/WifiP2pService( 3527): P2pEnabledState clear service request
I/jxcore-log(11675): StopBroadcasting went ok
I/jxcore-log(11675): 
D/WifiP2pService( 3527): remove channel information from framework
,I/jxcore-log(11675): ****TEST TOOK:  ms ****
I/jxcore-log(11675): 
,I/jxcore-log(11675): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11675): 
,I/jxcore-log(11675): 2016-01-07T08:47:47.886Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log(11675): 
I/io.jxcore.node.ConnectionHelper(11675): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11675): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11675): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper(11675): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11675): Service requests cleared successfully
I/chromium(11675): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime(13606): 
D/AndroidRuntime(13606): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(13606): CheckJNI is OFF
,D/AndroidRuntime(13606): readGMSProperty: start
D/AndroidRuntime(13606): readGMSProperty: already setted!!
,D/AndroidRuntime(13606): readGMSProperty: end
D/AndroidRuntime(13606): addProductProperty: start
,E/AffinityControl(13606): AffinityControl: registerfunction enter
,D/AndroidRuntime(13606): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3527): START PACKAGE DELETE: observer{387017642}
D/PackageManager( 3527): pkg{<packageName>}
D/PackageManager( 3527): user{0}
D/PackageManager( 3527): caller{2000}
D/PackageManager( 3527): flags{3}
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3527): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3527): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3527): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3527): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3527): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3527): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3527): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3527): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3527): !@killApplicatoin: 10539, uninstall pkg
I/ActivityManager( 3527): Force stopping com.test.thalitest appid=10539 user=-1: uninstall pkg
I/ActivityManager( 3527): Killing 11675:com.test.thalitest/u0a539 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3527):   Force finishing activity ActivityRecord{79558f4 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3527): mDVFSHelper.acquire()
,W/PackageSettings( 3527): Skipping PackageSetting{3e8f4340 com.example.hello/10529} due to missing metadata
,I/WindowState( 3527): WIN DEATH: Window{24af619a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3527): Client connection lost with reason: 4
,I/SurfaceFlinger( 2854): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2854): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3527): Force stopping com.test.thalitest appid=10539 user=0: pkg removed
,I/ActivityManager( 3527):   Force finishing activity ActivityRecord{79558f4 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3527): Duplicate finish request for ActivityRecord{79558f4 u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 8753): Explicit concurrent mark sweep GC freed 30058(1675KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.220ms total 42.117ms
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/InputReader( 3527): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4037): Explicit concurrent mark sweep GC freed 55892(2MB) AllocSpace objects, 6(96KB) LOS objects, 21% free, 28MB/36MB, paused 1.376ms total 70.259ms
,E/SamsungIME( 4513): mOCRHelper is null
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/art     ( 4777): Explicit concurrent mark sweep GC freed 27250(1550KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.153ms total 93.077ms
,W/GeofencerStateMachine( 4621): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/LWLocationManager(12956): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(12956): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (13627): MountEmulatedStorage()
E/Zygote  (13627): v2
I/libpersona(13627): KNOX_SDCARD checking this for 10063
I/libpersona(13627): KNOX_SDCARD not a persona
,I/SELinux (13627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13627 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/EnterpriseDeviceManagerService( 3527): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3527): Admin package name: com.google.android.gms
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 915us total 21.663ms
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourceType( 5368): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5368): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/TimaKeyStoreProvider(13627): TimaSignature is unavailable
,D/ActivityThread(13627): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 821us total 18.808ms
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3527): uri = 14 selection = getSealedState
D/SecContentProvider2( 3527): mCursor = null
,D/ApplicationPolicy( 3527): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 543us total 11.282ms
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,D/ResourcesManager(13627): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 103557(9MB) AllocSpace objects, 156(2MB) LOS objects, 24% free, 49MB/65MB, paused 1.984ms total 214.720ms
I/art     ( 3527): WaitForGcToComplete blocked for 184.634ms for cause Explicit
D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6243): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,D/VRSetupWizardStub/PackageIntentReceiver(13627): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13627): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13627): packagename:com.test.thalitest
I/DBG_DM  ( 6243): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6243): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ActivityManager( 3527): post active user change for 0
D/KnoxTimeoutHandler( 3527): postActiveUserChange for user 0
I/KLMS-2.4.521: (11938): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 07 09:47:48 GMT+01:00 2016
,I/DBG_DM  ( 6243): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/SurfaceFlinger( 2854): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3527): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3527): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3527): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3527): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6243): updateVisibility : ActivityRecord{21e75144 token=android.os.BinderProxy@abb8c71 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 3527): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/StatusBarManagerService( 3527): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/InputMethodManagerService( 3527): Got RemoteException sending setActive(false) notification to pid 11675 uid 10539
,I/KLMS-2.4.521: (11938): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3527): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3527): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onCreate()
,E/Zygote  (13647): MountEmulatedStorage()
E/Zygote  (13647): v2
I/libpersona(13647): KNOX_SDCARD checking this for 10106
I/libpersona(13647): KNOX_SDCARD not a persona
,I/SELinux (13647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/ActivityManager( 3527): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13647 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (13647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,I/KLMS-2.4.521: (11938): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11938): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  (13661): MountEmulatedStorage()
E/Zygote  (13661): v2
I/libpersona(13661): KNOX_SDCARD checking this for 10160
I/libpersona(13661): KNOX_SDCARD not a persona
,I/SELinux (13661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/RCPManager(12043):  in createShortcut() for packageName: com.test.thalitest userId0
,I/SELinux (13661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/RCPManagerService( 3527):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3527): queryAllProviders():  providerCallBack is not register for 0
I/Timeline( 6243): Timeline: Activity_idle id: android.os.BinderProxy@abb8c71 time:638898
E/SELinux (13661): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13661 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(13647): TimaSignature is unavailable
D/ActivityThread(13647): Added TimaKeyStore provider
,I/KLMS-2.4.521: (11938): KLMSIntentService(): PACKAGE_REMOVED
,E/Zygote  (13673): MountEmulatedStorage()
E/Zygote  (13673): v2
I/libpersona(13673): KNOX_SDCARD checking this for 10050
I/libpersona(13673): KNOX_SDCARD not a persona
,I/SELinux (13673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3527): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13673 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/SecContentProvider2( 3527): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3527): mCursor = null
,W/ResourceType( 3527): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/KLMS-2.4.521: (11938): KLMSIntentService(): listeningToPackageRemoved().START
,D/TimaKeyStoreProvider(13661): TimaSignature is unavailable
,D/ActivityThread(13661): Added TimaKeyStore provider
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk,
I/art     ( 3527): Explicit concurrent mark sweep GC freed 8905(462KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 7.759ms total 197.059ms
I/art     ( 3527): WaitForGcToComplete blocked for 253.612ms for cause Explicit
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (11938): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider(13673): TimaSignature is unavailable
,D/ActivityThread(13673): Added TimaKeyStore provider
,D/RegisteredServicesCache( 3968): empty dynamic service
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/BatteryService( 3527): !@BatteryListener : batteryPropertiesChanged!
D/ResourcesManager(13647): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/BatteryService( 3527): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3527): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-159
D/PackageManager( 3527): delete codoeFile: 
D/BatteryService( 3527): stay LED for fully charged
,I/AASAUninstall( 3527):  com.test.thalitest not target!
D/PackageManager( 3527): result of delete: 1{387017642}
,D/AndroidRuntime(13606): Shutting down VM
D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ActivityManager( 3527): mDVFSHelper.release()
I/Timeline( 3527): Timeline: Activity_windows_visible id: ActivityRecord{321888d0 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:639010
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/elm:14491(13647): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(13647): ELMEngine.ELMEngine( context ).
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/elm:14491(13647): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(13661): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/ResourcesManager(13661): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13661): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13661): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(12956): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(13673): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,W/ResourcesManager(13673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13673): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13673): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(13673): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/elm:14491(13647): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/elm:14491(13647): ElmAgentService : onCreate()
,D/elm:14491(13647): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(13647): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13647): MDMBridge.getInstance()
D/elm:14491(13647): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(13647): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.4.521: (11938): KLMSIntentService(): listeningToPackageRemoved().END
,E/Zygote  (13695): MountEmulatedStorage()
E/Zygote  (13695): v2
I/libpersona(13695): KNOX_SDCARD checking this for 10101
I/libpersona(13695): KNOX_SDCARD not a persona
,I/SELinux (13695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3527): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13695 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (13695): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/elm:14491(13647): ElmAgentService : onDestroy().
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11938): KLMSIntentService(): onDestroy()
D/ResourcesManager(12956): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  (13712): MountEmulatedStorage()
E/Zygote  (13712): v2
I/libpersona(13712): KNOX_SDCARD checking this for 10019
I/libpersona(13712): KNOX_SDCARD not a persona
,I/SELinux (13712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(13695): TimaSignature is unavailable
,E/SELinux (13712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13712 uid=10019 gids={50019, 9997} abi=armeabi-v7a
D/ActivityThread(13695): Added TimaKeyStore provider
D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,V/Common  (13661): getScreenSize 1440 2560
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/art     ( 3527): Explicit concurrent mark sweep GC freed 10798(653KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.297ms total 192.141ms
,W/ResourcesManager(12956): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12956): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12956): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12956): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3527): Killing 11904:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(13712): TimaSignature is unavailable
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/ActivityThread(13712): Added TimaKeyStore provider
,I/JAM     (13661): Load The ApaService JNI
,I/JAM     (13661): version: ProfessionalAudio_v1.0.b5
I/JAM     (13661): Try v1.0.b3 ...
D/Spen    (13661): SpenSdk version level = 55
D/Spen    (13661): SpenSdk jar version = 3.0.243
,D/Spen    (13661): SpenSdk apk version = 3.0.235
D/Spen    (13661): Server UPDATE Check
,W/linker  (13661): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/ActivityManager( 3527): Killing 11922:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##31
,D/SPenError(13661): JNI_OnLoad
,D/JNI_Bitmap(13661): Init .. Done
D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SPenSpiDecoder(13661): JNI_OnLoad .. Done
D/SPenError(13661): JNI_OnLoad Success
,D/PluginManager(13661): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(13661): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(13661): JNI_OnLoad
D/Init_SPenSdk_Jni(13661): AndroidSDK: 21
D/Init_SPenSdk_Jni(13661): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(13661): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(13661): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(13661): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(13661): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(13661): JNI_OnLoad .. Done
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/Model_PageDoc_Jni(13661): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(13661): check build type eng[0]
D/Model_NoteDoc_Jni(13661): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(13661): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(13661): JNI_OnLoad .. Done
D/Model   (13661): OnLoad class Done
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/spe_log (13661): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(13661): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(13661): Canvas JNI_OnLoad enter!!
,D/SPen_Library(13661): Canvas JNI_OnLoad Success
D/SPen_Library(13661): TextView JNI_OnLoad enter!!
,D/SPen_Library(13661): TextView JNI_OnLoad Success
D/SPen_Library(13661): Text JNI_OnLoad enter!!
D/SPen_Library(13661): Text JNI_OnLoad Success
D/SPen_Library(13661): FontManager JNI_OnLoad enter!!
D/SPen_Library(13661): FontManager JNI_OnLoad Success
D/SPen_Library(13661): CapturePage JNI_OnLoad enter!!
D/SPen_Library(13661): CapturePage JNI_OnLoad Success
D/SPen_Library(13661): Multi JNI_OnLoad enter!!
,D/SPen_Library(13661): Multi JNI_OnLoad Success
D/SPen_Library(13661): Draw Engine JNI_OnLoad Success
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(13695): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/SPen_Library(13661): Brush JNI_OnLoad enter!!
,D/SPen_Library(13661): Brush JNI_OnLoad Success
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SPen_Library(13661): ChineseBrush JNI_OnLoad enter!!
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SPen_Library(13661): ChineseBrush JNI_OnLoad Success
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/SPen_Library(13661): InkPen JNI_OnLoad enter!!
,D/SPen_Library(13661): InkPen JNI_OnLoad Success
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/libpersona(13730): KNOX_SDCARD checking this for 10160
D/SPen_Library(13661): Marker JNI_OnLoad enter!!
I/libpersona(13730): KNOX_SDCARD not a persona
E/Zygote  (13730): MountEmulatedStorage()
E/Zygote  (13730): v2
D/SPen_Library(13661): Marker JNI_OnLoad Success
I/SELinux (13730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/SPen_Library(13661): Pencil JNI_OnLoad enter!!
D/SPen_Library(13661): Pencil JNI_OnLoad Success
D/SPen_Library(13661): NativePen JNI_OnLoad enter!!
D/SPen_Library(13661): NativePen JNI_OnLoad Success
,D/SPen_Library(13661): MontblancFountainPen JNI_OnLoad enter!!
I/SELinux (13730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SPen_Library(13661): MontblancFountainPen JNI_OnLoad Success
,E/SELinux (13730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SPen_Library(13661): MontblancCalligraphyPen JNI_OnLoad enter!!
I/ActivityManager( 3527): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=13730 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/SPen_Library(13661): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(13661): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(13661): MagicPen JNI_OnLoad Success
,D/SPen_Library(13661): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(13661): ObliquePen JNI_OnLoad Success
,D/SPen_Library(13661): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(13661): FountainPen JNI_OnLoad Success
D/Spen    (13661): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(13661): SPenSdk_init2
D/Init_SPenSdk(13661): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(13661): Total S Pen SDK Directory Size = 0
D/Spen    (13661): initialize complete
,W/linker  (13661): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/TimaKeyStoreProvider(13730): TimaSignature is unavailable
,D/ActivityThread(13730): Added TimaKeyStore provider
,D/PackageManager( 3527): findPreferredActivity: No PreferredActivities set
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager( 3527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3527): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(13712): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
I/ActivityManager( 3527): Killing 11954:com.sec.android.soagent/u0a38 (adj 15): bgCount ##31
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/DocsApplication(13695): Installing DEX configuration.
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  (13749): MountEmulatedStorage()
E/Zygote  (13749): v2
I/libpersona(13749): KNOX_SDCARD checking this for 10183
I/libpersona(13749): KNOX_SDCARD not a persona
,I/SELinux (13749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/SELinux (13749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Books/Books.apk
I/ActivityManager( 3527): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13749 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
E/SELinux (13749): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/ActivityManager( 3527): Killing 11969:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/lowmemorykiller( 2828): Error writing /proc/11969/oom_score_adj; errno=22
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3527): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/DexInstaller(13695): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/com.sec.android.service.health.upgrade.UninstallReceiver(13712): onReceive()
W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/com.sec.android.service.health.upgrade.UninstallReceiver(13712): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(13712): onReceive() : package name is not s health. Return !!!
D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources( 3527): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3527): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3527): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(13730): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider(13749): TimaSignature is unavailable
,D/ActivityThread(13749): Added TimaKeyStore provider
,D/LocationWidgetApplication(12956): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/PackageInfoHelper(13695): Provided clientMode=RELEASE, packageInfo=PackageInfo{104afe3c com.google.android.apps.docs}
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/TAG     (13695): onCreate()
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3527): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/ResourcesManager(13730): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(13730): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13730): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3527): PackageReceiver onReceive()
I/HarmonyEASService( 3527): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(12956): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/CrossAppStateProvider(13695): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/KnoxMUMContainerPolicy( 3527): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,E/Zygote  (13765): MountEmulatedStorage()
E/Zygote  (13765): v2
I/libpersona(13765): KNOX_SDCARD checking this for 1000
I/libpersona(13765): KNOX_SDCARD not a persona
,I/SELinux (13765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3527): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=13765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ActivityManager( 3527): Killing 11160:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,I/SELinux (13765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(13749): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
E/SELinux (13765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3527): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3527): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
,E/SQLiteLog(13749): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
D/UsbHostManager( 3527): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3527): displayNotification : [0ah,00h,01h]
,E/SQLiteDatabase(13749): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(13749): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13749): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(13749): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(13749): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(13749): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(13749): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(13749): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(13749): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(13749): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13749): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13749): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13749): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13749): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13749): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13749): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13749): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(13749): Shutting down VM
,E/AndroidRuntime(13749): FATAL EXCEPTION: main
E/AndroidRuntime(13749): Process: com.samsung.android.provider.shootingmodeprovider, PID: 13749
E/AndroidRuntime(13749): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13749): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(13749): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(13749): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(13749): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(13749): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(13749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13749): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(13749): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(13749): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(13749): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(13749): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(13749): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(13749): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13749): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13749): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13749): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13749): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(13749): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(13749): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(13749): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(13749): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(13749): 	... 11 more
,D/UsbHostManager( 3527): usbDeviceRemoved : /dev/bus/usb/001/003
,E/UsbHostManager( 3527): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3527): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/NearbySource(13673): Nearby Source Create!
,D/NearbyContext(13673): Nearby Context Create!
V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,D/UsbHostManager( 3527): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3527): displayNotification : [09h,00h,00h]
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(13765): TimaSignature is unavailable
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,D/ActivityThread(13765): Added TimaKeyStore provider
,D/SNoteProvider(13730): onCreate enableSnoteSync = true
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(13673): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(13673): Samsung link source created
,E/Zygote  (13789): MountEmulatedStorage()
E/Zygote  (13789): v2
I/libpersona(13789): KNOX_SDCARD checking this for 10190
I/libpersona(13789): KNOX_SDCARD not a persona
,I/SELinux (13789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,I/SELinux (13789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13789 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/ActivityManager( 3527): Killing 12011:com.samsung.android.scloud.backup/u0a67 (adj 15): bgCount ##31
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/UsbHostManager( 3527): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3527): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/TimaKeyStoreProvider(13789): TimaSignature is unavailable
,D/ActivityThread(13789): Added TimaKeyStore provider
,I/Process (13749): Sending signal. PID: 13749 SIG: 9
,I/EventHub( 3527): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(13765): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/EventHub( 3527): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/SNoteProvider(13730): ===query=== 
,E/SQLiteLog(13730): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,I/PCWCLIENTTRACE_LOG(13765): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(13765): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(13765): new DMDBOpenHelper instance
,E/SQLiteLog(13765): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13765): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13765): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13765): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13765): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13765): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13765): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(13765): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(13765): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(13765): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(13765): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(13765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(13765): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13765): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13765): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13765): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13765): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(13765): Shutting down VM
,E/AndroidRuntime(13765): FATAL EXCEPTION: main
E/AndroidRuntime(13765): Process: com.sec.pcw.device, PID: 13765
E/AndroidRuntime(13765): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13765): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(13765): 	,at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(13765): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(13765): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(13765): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(13765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13765): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(13765): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(13765): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(13765): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(13765): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(13765): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(13765): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13765): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13765): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13765): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13765): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(13765): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(13765): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(13765): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(13765): 	... 11 more
,E/SQLiteDatabase(13730): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
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
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(13730): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(13730): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(13730): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(13730): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(13730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(13730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(13730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(13730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(13730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(13730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(13730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(13730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(13730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(13730): 	at com.samsung.android.snote.model.provid,er.SNoteProvider.query(SourceFile:751)
W/System.err(13730): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(13730): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(13730): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(13730): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(13730): message = not an error (code 0): Could not open the database in read/write mode.
,D/ResourcesManager(13789): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,V/ApplicationPolicy( 3527): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Maps/Maps.apk
E/SQLiteLog(13673): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3527): Removing device '/dev/input/event8' due to inotify event
,E/SQLiteDatabase(13673): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(13673): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13673): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13673): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13673): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13673): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(13673): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(13673): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(13673): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(13673): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(13673): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(13673): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(13673): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13673): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13673): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13673): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13673): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13673): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13673): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13673): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper(13673): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(13673): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13673): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13673): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13673): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(13673): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(13673): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(13673): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(13673): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(13673): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(13673): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(13673): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(13673): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(13673): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(13673): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(13673): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(13673): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(13673): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(13673): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(13673): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(13673): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper(13673): Opened local.db in read-only mode
,I/ActivityManager( 3527): Killing 12061:com.android.chrome/u0a90 (adj 13): bgCount ##31
,E/DropBoxManagerService( 3527): Can't write: system_app_crash
E/DropBoxManagerService( 3527): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3527): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3527): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3527): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3527): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3527): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3527): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3527): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3527): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3527): 	... 5 more
,I/ActivityManager( 3527): Process com.samsung.android.provider.shootingmodeprovider (pid 13749)(adj 9) has died(175,1194)
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/EventHub( 3527): Removing device '/dev/input/event9' due to inotify event
,I/TapandpayWidget:TanpandpayAppWidgetProvider(13789): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13789): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/SNoteProvider(13730): ===query=== 
,V/Common  (13730): getScreenSize 1440 2560
,E/SQLiteLog(13730): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13730): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
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
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(13730): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(13730): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(13730): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(13730): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err(13730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err(13730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
I/TapandpayWidget:Utils(13789): Clear T&P info.
,W/System.err(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(13730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,W/System.err(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12956): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,W/System.err(13730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(13730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
,W/System.err(13730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
,W/System.err(13730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
,W/System.err(13730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
,D/TapandpayWidget:TanpandpayAppWidgetProvider(13789): Widget is not attached.
W/System.err(13730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,W/System.err(13730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(13730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(13730): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(13730): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(13730): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(13730): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(13730): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(13730): message = not an error (code 0): Could not open the database in read/write mode.
,I/EventHub( 3527): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  (13810): MountEmulatedStorage()
E/Zygote  (13810): v2
I/libpersona(13810): KNOX_SDCARD checking this for 10035
I/libpersona(13810): KNOX_SDCARD not a persona
,I/SELinux (13810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3527): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=13810 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/Process (13765): Sending signal. PID: 13765 SIG: 9
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/EventHub( 3527): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/EventHub( 3527): Removing device '/dev/input/event13' due to inotify event
,D/WifiDisplayAdapter( 3527): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(13810): TimaSignature is unavailable
,D/ActivityThread(13810): Added TimaKeyStore provider
D/ContactProvider(13673): getAllContactInfoList Start
,D/PackageBroadcastService( 4777): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4777): Clearing selected account for com.test.thalitest
,D/ResourcesManager(12956): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/EventHub( 3527): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(12956): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/MtpClient(13673): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(13673): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,I/ActivityManager( 3527): Process com.sec.pcw.device (pid 13765)(adj 9) has died(177,1195)
,E/SQLiteLog( 4777): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 4777): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SharedPreferencesImpl(13673): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/LocationSettingsChecker( 4777): Removing dialog suppression flag for package com.test.thalitest
,I/FeatureConfig(13810): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,E/DriveAsyncService( 4777): disk I/O error (code 3850)
E/DriveAsyncService( 4777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4777): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4777): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4777): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4777): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4777): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4777): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4777): 	at java.lang.Thread.run(Thread.java:818)
,D/ChimeraCfgMgr( 4777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4777): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3527): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4777): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4777): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4777): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4777): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4777): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4777): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4777): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4777): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4777): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4777): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4777): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4777): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4777): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
