#### Test 50650278b86327b_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3480): !@Sync 4
,--------- beginning of main
D/AndroidRuntime(11717): 
D/AndroidRuntime(11717): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11717): CheckJNI is OFF
D/AndroidRuntime(11717): readGMSProperty: start
D/AndroidRuntime(11717): readGMSProperty: already setted!!
D/AndroidRuntime(11717): readGMSProperty: end
D/AndroidRuntime(11717): addProductProperty: start
E/AffinityControl(11717): AffinityControl: registerfunction enter
D/AndroidRuntime(11717): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3480): inState():  stateMachine is null !!
I/PersonaManagerService( 3480): PersonaId don't exist
I/ActivityManager( 3480): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3480): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3480): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3480): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3480): mDVFSHelper.acquire()
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/Zygote  (11739): MountEmulatedStorage()
E/Zygote  (11739): v2
I/libpersona(11739): KNOX_SDCARD checking this for 10482
I/libpersona(11739): KNOX_SDCARD not a persona
I/SELinux (11739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3480): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11739 uid=10482 gids={50482, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11739): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11717): Shutting down VM
D/PointerIcon( 3480): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3480): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3480): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3480): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11739): TimaSignature is unavailable
D/ActivityThread(11739): Added TimaKeyStore provider
D/SSRM:n  ( 3480): SIOP:: AP = 270, PST = 286, CUR = 37
I/SurfaceFlinger( 2857): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2857): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11739): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6265): updateVisibility : ActivityRecord{1e636669 token=android.os.BinderProxy@13ed0722 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11739): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11739): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11739): Loading: webviewchromium
I/LibraryLoader(11739): Time to load native libraries: 3 ms (timestamps 4141-4144)
I/LibraryLoader(11739): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11739): Binding Chromium to main looper Looper (main, tid 1) {bcfd180}
I/LibraryLoader(11739): Expected native library version number "",actual native library version number ""
I/chromium(11739): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11739): Initializing chromium process, renderers=0
,W/art     (11739): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11739): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11739): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11739): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11739): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11739): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11739): Attempt to remove local handle scope entry from IRT, ignoring
D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,W/AwContents(11739): onDetachedFromWindow called when already detached. Ignoring
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/SystemWebViewEngine(11739): CordovaWebView is running on device made by: samsung
W/art     (11739): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11739): Attempt to remove local handle scope entry from IRT, ignoring
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/Activity(11739): performCreate Call secproduct feature valuefalse
D/Activity(11739): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11739): Render dirty regions requested: true
,D/ActivityManager( 3480): post active user change for 0
D/KnoxTimeoutHandler( 3480): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3480): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2857): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3480): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3480): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3480): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3480): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3480): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3480): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11739): Initialized EGL, version 1.4
,I/OpenGLRenderer(11739): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278652144 
,D/OpenGLRenderer(11739): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11739): Enabling debug mode 0
,D/mali_winsys(11739): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11739): updateVisibility : ActivityRecord{1b3a9ab0 token=android.os.BinderProxy@1ce7267 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3480): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3480): mDVFSHelper.release()
I/Timeline( 3480): Timeline: Activity_windows_visible id: ActivityRecord{1410aa6 u0 com.test.thalitest/.MainActivity t26} time:134506
,W/IInputConnectionWrapper(11739): showStatusIcon on inactive InputConnection
,I/Timeline(11739): Timeline: Activity_idle id: android.os.BinderProxy@1ce7267 time:134515
,D/JsMessageQueue(11739): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11739): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11739): 
,D/jxcore_app_log(11739): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357428096
D/JX-Cordova(11739): jxcore cordova android initializing
,W/jxcore-log(11739): Initializing JXcore engine
W/jxcore-log(11739): JXcore engine is ready
,W/jxcore-log(11739): Starting JXcore engine
,E/auditd  ( 4620): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3480): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3480): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11739): Platform android
W/jxcore-log(11739): 
W/jxcore-log(11739): Process ARCH arm
W/jxcore-log(11739): 
,I/jxcore-log(11739): JXcore Cordova bridge is ready!
I/jxcore-log(11739): 
W/jxcore-log(11739): JXcore engine is started
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11739): Toggling radios to true
I/jxcore-log(11739): 
,D/BluetoothAdapter(11739): enable()
,D/BluetoothAdapter(11739): enable(): BT is already enabled..!
,D/WifiService( 3480): New client listening to asynchronous messages
,I/WifiManager(11739): packageName : com.test.thalitest
,D/SecContentProvider( 3480): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3480): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3480): mCursor = null
D/WifiService( 3480): setWifiEnabled: true pid=11739, uid=10482
E/WifiService( 3480): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3480): Permission Denial: getCurrentUser() from pid=11739, uid=10482 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3480): Failed getting userId using ActivityManagerNative
W/WifiService( 3480): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11739, uid=10482 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3480): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3480): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3480): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3480): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3480): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3480): name = wifi_on
,I/WifiService( 3480): disconnect: pid=11739, uid=10482
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11739): Radios toggled
I/jxcore-log(11739): 
,I/jxcore-log(11739): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11739): 
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/jxcore-log(11739): Perf Test app loaded loaded
I/jxcore-log(11739): 
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log(11739): check test folder
I/jxcore-log(11739): 
E/WifiStateMachine( 3480): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): Disconnected - do not scan
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/jxcore-log(11739): found test : ./testFindPeers.js
I/jxcore-log(11739): 
E/WifiStateMachine( 3480): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3480): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3480): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3480): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11739): found test : ./testSendData.js
I/jxcore-log(11739): 
E/WifiStateMachine( 3480): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3480): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3480): do suspend true
D/WifiP2pService( 3480): InactiveState{ what=143375 }
D/WifiP2pService( 3480): P2pEnabledState{ what=143375 }
D/CommandListener( 2853): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
V/NativeCrypto( 4630): Read error: ssl=0x9c71fe00: I/O error during system call, Connection timed out
V/NativeCrypto( 4630): SSL shutdown failed: ssl=0x9c71fe00: I/O error during system call, Broken pipe
E/WifiStateMachine( 3480): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3480): updateNetworkInfo()
D/ConnectivityService( 3480): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3480): updateNetworkInfo()
D/ConnectivityService( 3480): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3480): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/WifiTrafficPoller( 3480): evaluateTrafficStatsPolling
D/ConnectivityService( 3480): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): ValidatedState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): DefaultState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
I/System.out( 3480): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3480): Tagging socket 388 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3480, getuid(): 1000
,I/System.out( 3480): (HTTPLog)-Static: isSBSettingEnabled false
,I/Hs20UtilService( 4108): Starting #8
,E/WifiStateMachine( 3480): Start Disconnecting Watchdog 1
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> SCANNING
I/Hs20UtilService( 4108): Message received 5007
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3833): First Scan Start
E/WifiStateMachine( 3480): ConnectModeState: Network connection lost 
I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3480): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3480): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/NearbySettings( 8786): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8786): MountReceiver.onReceive - Start HandlerThread
,E/WifiStateMachine( 3480): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3480): do suspend true
,D/NearbySettings( 8786): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 8786): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8786): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/WifiService( 3480): New client listening to asynchronous messages
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8786): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8786): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 3480): InactiveState{ what=143375 }
D/WifiP2pService( 3480): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11420): NETWORK_STATE_CHANGED_ACTION
,D/EnterpriseController( 2853): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2853): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener( 2853): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3480): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3480): Not allowed due to - mEnabled false
E/WifiStateMachine( 3480): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Validated
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
D/ConnectivityService( 3480): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine( 3480): updateConfiguredNetworkExpiration - currTime: 1449756747273
D/WifiStateMachine( 3480): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker( 3480): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3480): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/CSLegacyTypeTracker( 3480): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3480): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3480): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 6951): CM callback handler got msg 524292
E/WifiStateMachine( 3480): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3480): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/WifiTrafficPoller( 3480): evaluateTrafficStatsPolling
E/WifiStateMachine( 3480): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3480): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3480): NetworkAgent: NetworkAgent channel lost
D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3480): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3480): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3480): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3480): Not allowed due to - mEnabled false
,D/ConnectivityService( 3480): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering( 3480): MasterInitialState.processMessage what=3
,D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
,D/SmartBondingService( 3480): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3480): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3480): updateIfacesLocked()
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
V/NetworkStats( 3480): performPollLocked(flags=0x1)
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3480): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/SmartBondingService( 3480): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
V/NetworkStats( 3480): performPollLocked() took 3ms
,I/chromium(11739): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/Hs20UtilService( 4108): Starting #9
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
V/NetworkStats( 3480): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
I/Hs20UtilService( 4108): Message received 5007
D/StatusBar.NetworkController( 3694): applyOpen
,D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
,D/NearbySettings( 8786): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8786): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8786): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8786): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
,I/SignOutReceiver(11420): NETWORK_STATE_CHANGED_ACTION
,I/chromium(11739): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
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
,D/ConnectivityService( 3480): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3480): updateDataUsageMap
,I/ApplicationPolicy( 3480): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3480): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3480): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3480): getSBEnabled() enabled =false
,D/SmartBondingService( 3480): getSBEnabled() enabled =false
,D/SmartBondingService( 3480): getSBEnabled() enabled =false
,D/SmartBondingService( 3480): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3480): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3480): No Active Data Connection
,I/DBG_DM  ( 6265): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6265): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11840): MountEmulatedStorage()
E/Zygote  (11840): v2
I/libpersona(11840): KNOX_SDCARD checking this for 10110
I/libpersona(11840): KNOX_SDCARD not a persona
,I/SELinux (11840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3480): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11840 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11840): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11840): TimaSignature is unavailable
,D/ActivityThread(11840): Added TimaKeyStore provider
,D/ResourcesManager(11840): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11840): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11840): not using cross-dex optimization: ART in use
,I/art     (11840): Thread[1,tid=11840,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11840): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11840): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(11840): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11840): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11840): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11840): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11840): loading pre-built fallback odex files
,V/MultiDexClassLoader(11840): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11840): released odex store lock
D/DexLibLoader(11840): DexLibLoader.loadAll took 44 ms
,W/ca      (11840): Verify
,W/appmanager(:<default>):LightSharedPreferencesImpl(11840): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl(11840): 	... 10 more
,I/wpa_supplicant( 3833): nl80211: Received scan results (12 BSSes)
I/wpa_supplicant( 3833): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3833): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3833): wlan0: State: SCANNING -> ASSOCIATING
E/WifiStateMachine( 3480): [1,449,756,748,330 ms] noteScanEnd no scan source
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3480): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@13ada77d sup_state=SCANNING debouncing=false
E/WifiStateMachine( 3480): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3480): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3480): setDetailed state send new extra info
D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11878): MountEmulatedStorage()
E/Zygote  (11878): v2
I/libpersona(11878): KNOX_SDCARD checking this for 1000
I/libpersona(11878): KNOX_SDCARD not a persona
,I/SELinux (11878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3480): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11878 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Killing 10999:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11840): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11878): TimaSignature is unavailable
,W/appmanager(:<default>):b(11840): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ActivityThread(11878): Added TimaKeyStore provider
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3833): Associated with C0.AA.48
,E/WifiStateMachine( 3480): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3480): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3480): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3480): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3480): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3833): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3833): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3833): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3833): Blacklist: Clear (temp) 
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3480): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine( 3480): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3480): Network connection established
,D/ResourcesManager(11878): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/WifiNative-HAL( 3480): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3480): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3480): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3480): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3480): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3480): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3480): updateNetworkInfo()
D/ConnectivityService( 3480): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiStateMachine( 3480): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3480): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/PCWCLIENTTRACE_LOG(11878): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11878): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11878): new DMDBOpenHelper instance
,E/WifiStateMachine( 3480): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
W/appmanager(:<default>):QuickExperimentControllerImpl(11840): Exposure of experiment com.facebook.common.network.l@26e1f4f7 occurred when no user was logged in
E/WifiStateMachine( 3480): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3480): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3480): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2853): Setting iface cfg
,E/WifiStateMachine( 3480): Start Dhcp Watchdog 2
,I/PCWCLIENTTRACE_PushUtil(11878): SPPPushClient is installed : true
W/BroadcastQueue( 3480): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{de5319a u0 ReceiverList{20b69645 11840 com.facebook.appmanager/10110/u0 remote:3e4f46bc}}
I/PCWCLIENTTRACE_PushUtil(11878): sales region : global
I/PCWCLIENTTRACE_PushUtil(11878): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11878): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11878): noConnectivity : true
,W/BroadcastQueue( 3480): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{de5319a u0 ReceiverList{20b69645 11840 com.facebook.appmanager/10110/u0 remote:3e4f46bc}}
,D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
,E/WifiStateMachine( 3480): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3480): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11907): MountEmulatedStorage()
E/Zygote  (11907): v2
I/libpersona(11907): KNOX_SDCARD checking this for 10135
I/libpersona(11907): KNOX_SDCARD not a persona
,I/SELinux (11907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11907): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11907 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3480): Killing 11014:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11907): TimaSignature is unavailable
,D/ActivityThread(11907): Added TimaKeyStore provider
,D/ResourcesManager(11907): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine( 3480): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3480): do suspend false
,D/SecContentProvider2( 3480): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3480): mCursor = null
D/WifiP2pService( 3480): InactiveState{ what=143375 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=143375 }
,W/BroadcastQueue( 3480): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3d86233e u0 ReceiverList{8b77f9 11840 com.facebook.appmanager/10110/u0 remote:2b908ec0}}
,I/MusicStore(11907): Database version: 104
,D/ResourcesManager(11907): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11907): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/dhcpcd  (11939): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11939): version 5.5.6 starting
,W/ActivityThread(11907): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11907): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@93228d4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11907): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11907): GMSCore installation verified
,E/dhcpcd  (11939): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ConfigStore(11907): Config Database version: 1
,I/dhcpcd  (11939): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (11939): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11939): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11939): bssid match
I/dhcpcd  (11939): wlan0: rebinding lease of 192.168.1.124
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11840): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/ContextImpl(11840): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11907): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3480): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3480): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3480): getStreamVolume 3 index 0
,I/MediaRouter(11907): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/appmanager(:<default>):QuickExperimentControllerImpl(11840): Exposure of experiment com.facebook.imagepipeline.a.g@3dcce0e4 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11840): Exposure of experiment com.facebook.imagepipeline.a.d@22204d49 occurred when no user was logged in
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11949): MountEmulatedStorage()
E/Zygote  (11949): v2
I/libpersona(11949): KNOX_SDCARD checking this for 10002
I/libpersona(11949): KNOX_SDCARD not a persona
,I/SELinux (11949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11949): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11949 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3480): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 861us total 23.374ms
,I/art     (11840): Explicit concurrent mark sweep GC freed 48154(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.840ms total 49.583ms
,W/appmanager(:<default>):m(11840): No feature status reporters found; is this dead code?
I/NetworkMonitor(11907): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11949): TimaSignature is unavailable
,D/ActivityThread(11949): Added TimaKeyStore provider
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 866us total 21.529ms
,I/ActivityManager( 3480): Killing 11029:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(11949): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 781us total 15.256ms
,I/ActivityManager( 3480): Killing 11044:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11971): MountEmulatedStorage()
E/Zygote  (11971): v2
I/libpersona(11971): KNOX_SDCARD checking this for 1000
I/libpersona(11971): KNOX_SDCARD not a persona
,I/SELinux (11971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11971): TimaSignature is unavailable
,D/ActivityThread(11971): Added TimaKeyStore provider
,D/ResourcesManager(11971): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11971): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11971): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11971): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11971): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11971): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11987): MountEmulatedStorage()
I/libpersona(11987): KNOX_SDCARD checking this for 10012
E/Zygote  (11987): v2
I/libpersona(11987): KNOX_SDCARD not a persona
,I/SELinux (11987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11987 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (11987): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11987): TimaSignature is unavailable
,D/ActivityThread(11987): Added TimaKeyStore provider
,D/ResourcesManager(11987): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3480): Killing 11065:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(11987): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11987): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11987): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12004): MountEmulatedStorage()
E/Zygote  (12004): v2
I/libpersona(12004): KNOX_SDCARD checking this for 10021
I/libpersona(12004): KNOX_SDCARD not a persona
,I/SELinux (12004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12004 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12004): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Killing 10894:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/10894/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12004): TimaSignature is unavailable
,D/ActivityThread(12004): Added TimaKeyStore provider
,D/ResourcesManager(12004): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12004): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 15:12:29 GMT+01:00 2015
,I/KLMS-2.4.521: (12004): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12004): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12004): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12004): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12004): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12004): StateImplV2(): networkChangeListener().END
,E/Zygote  (12020): MountEmulatedStorage()
E/Zygote  (12020): v2
I/libpersona(12020): KNOX_SDCARD checking this for 10038
I/libpersona(12020): KNOX_SDCARD not a persona
,I/SELinux (12020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12020 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (12020): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3480): Killing 11098:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12020): TimaSignature is unavailable
,D/ActivityThread(12020): Added TimaKeyStore provider
,D/ResourcesManager(12020): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12020): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12035): MountEmulatedStorage()
I/libpersona(12035): KNOX_SDCARD checking this for 1000
E/Zygote  (12035): v2
I/libpersona(12035): KNOX_SDCARD not a persona
,I/SELinux (12035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Killing 11076:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12035): TimaSignature is unavailable
,D/ActivityThread(12035): Added TimaKeyStore provider
,D/ResourcesManager(12035): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12055): MountEmulatedStorage()
E/Zygote  (12055): v2
I/libpersona(12055): KNOX_SDCARD checking this for 10039
I/libpersona(12055): KNOX_SDCARD not a persona
,I/SELinux (12055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12055): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12055 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3480): Killing 11144:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12055): TimaSignature is unavailable
,D/ActivityThread(12055): Added TimaKeyStore provider
,D/ResourcesManager(12055): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12055): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12055): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12055): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12055): PushLog.txt file is not deleted.
D/SPPClientService(12055): PushLog.txt file is not deleted.
D/SPPClientService(12055): ============PushLog. stop!
,I/SA      (11223): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11223): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11223): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11223): [SLFUCHKMGR] constructor called
,E/SPPClientService(12055): [[SystemStateMonitorService]] No Active Internet
I/SA      (11223): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11223): [OR] == isSIMCardReady false ==
,I/SA      (11223): [SCU] == networkStateCheck == false
I/SA      (11223): [OR] onReceive END
,V/DownloadManager( 5729): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12075): MountEmulatedStorage()
E/Zygote  (12075): v2
,I/libpersona(12075): KNOX_SDCARD checking this for 10067
I/libpersona(12075): KNOX_SDCARD not a persona
,I/SELinux (12075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3480): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12075 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Killing 11182:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12075): TimaSignature is unavailable
,D/ActivityThread(12075): Added TimaKeyStore provider
,D/ResourcesManager(12075): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/dhcpcd  (11939): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/sCloudBackupApp(12075): sCloudBackupApp Version Info : 4.00.4.KK_APP
,I/SCloudBackupReceiver(12075): Other Intent
,I/dhcpcd  (11939): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3480): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0},
,E/WifiStateMachine( 3480): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager( 3480): Killing 11161:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/accuweather( 5381): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5381): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5381): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5381): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5381): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5381): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5381): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12109): MountEmulatedStorage()
E/Zygote  (12109): v2
I/libpersona(12109): KNOX_SDCARD checking this for 1000
I/libpersona(12109): KNOX_SDCARD not a persona
,I/SELinux (12109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12109): TimaSignature is unavailable
,D/ActivityThread(12109): Added TimaKeyStore provider
,D/ResourcesManager(12109): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12109): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12109): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12109): premStatus:2
,I/KnoxUsageLogPro(12109): isEulaShown : false
I/KnoxUsageLogPro(12109): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12136): MountEmulatedStorage()
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD checking this for 10090
I/libpersona(12136): KNOX_SDCARD not a persona
,I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3480): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12136 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Killing 11118:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ActivityThread(12136): Added TimaKeyStore provider
,D/ResourcesManager(12136): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12156): MountEmulatedStorage()
E/Zygote  (12156): v2
I/libpersona(12156): KNOX_SDCARD checking this for 10127
I/libpersona(12156): KNOX_SDCARD not a persona
,I/SELinux (12156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12156 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12156): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Killing 11276:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12156): TimaSignature is unavailable
,D/ActivityThread(12156): Added TimaKeyStore provider
,E/WifiStateMachine( 3480): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/ResourcesManager(12156): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
E/WifiStateMachine( 3480): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3480): do suspend true
,D/WifiP2pService( 3480): InactiveState{ what=143375 }
D/WifiP2pService( 3480): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3480): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3480): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3480): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3480): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3480): Not connected state, yet.
E/WifiStateMachine( 3480): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3480): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3480): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3480): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3480): callSECApiInt - ID [210]
,E/WifiStateMachine( 3480): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3480): updateNetworkInfo()
,D/KeyguardWallpaperUpdator(12156): cancelUpdateWallpaper
D/ConnectivityService( 3480): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3480): Adding iface wlan0 to network 503
,D/KeyguardWallpaperUpdator(12156): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12156): stopCheckCategoryVersion
,D/WifiWatchdogStateMachine( 3480): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3480): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3480): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3480): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3480): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3480): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3480): Now, connected state.
E/WifiStateMachine( 3480): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 3480): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3480): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3480): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3480): Unexpected mtu value: 0, wlan0
,V/        ( 2853): QcRouteController
,E/Zygote  (12175): MountEmulatedStorage()
,E/Zygote  (12175): v2
I/libpersona(12175): KNOX_SDCARD checking this for 10136
I/libpersona(12175): KNOX_SDCARD not a persona
,I/SELinux (12175): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12175): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12175 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12175): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Killing 11295:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,E/WifiStateMachine( 3480): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
V/        ( 2853): QcRouteController
,I/WifiTrafficPoller( 3480): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3480): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8744(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 886us total 26.072ms
,E/WifiStateMachine( 3480): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiTrafficPoller( 3480): evaluateTrafficStatsPolling
,V/        ( 2853): QcRouteController
,D/WifiNative-HAL( 3480): callSECApiVoid - ID [212]
,I/WifiStateMachine( 3480): REQUEST_POWER_SAVE_ON
,D/TimaKeyStoreProvider(12175): TimaSignature is unavailable
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/ActivityThread(12175): Added TimaKeyStore provider
,V/        ( 2853): QcRouteController
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.040ms total 23.249ms
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/ResourcesManager(12175): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,V/        ( 2853): QcRouteController
I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 747us total 17.819ms
,V/        ( 2853): QcRouteController
,V/        ( 2853): QcRouteController
,V/        ( 2853): QcRouteController
,D/ConnectivityService( 3480): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3480): LTETest block dns file not exists
,D/ConnectivityService( 3480): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 3480): updateNetworkInfo()
,E/ConnectivityService( 3480): updateNetworkInfo()
D/ConnectivityService( 3480): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3480): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3480): rematching NetworkAgentInfo [WIFI () - 503]
,I/System.out( 3480): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2853): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2853): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3480):    accepting network in place of null
,D/TelephonyNetworkFactory( 3979): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3480): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3480): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3480): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering( 3480): MasterInitialState.processMessage what=3
D/ConnectivityService( 3480): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService( 3480): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3480): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/EntConnectivity( 3480): Not allowed due to - mEnabled false
D/ConnectivityService( 3480): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,V/NetworkStats( 3480): updateIfacesLocked()
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
V/NetworkStats( 3480): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3480): UpdateStatsForKnox
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/SmartBondingService( 3480): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
V/NetworkStats( 3480): performPollLocked() took 8ms
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
V/NetworkStats( 3480): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 6951): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
D/NtpTrustedTime( 3480): currentTimeMillis() cache hit
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/System.out( 3480): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 14:12:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449756751113], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449756751095]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3480): Validated
,D/ConnectivityService( 3480): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3480): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3480): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3480): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6951): CM callback handler got msg 524290
,D/ConnectivityService( 3480): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/WebViewFactory(12175): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12175): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12175): Loading: webviewchromium
,I/LibraryLoader(12175): Time to load native libraries: 5 ms (timestamps 764-769)
I/LibraryLoader(12175): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12175): Binding Chromium to main looper Looper (main, tid 1) {11f8debe}
,I/LibraryLoader(12175): Expected native library version number "",actual native library version number ""
,I/chromium(12175): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12175): Initializing chromium process, renderers=0
,W/art     (12175): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12175): Requires BLUETOOTH permission
,W/chromium(12175): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12175): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium(12175): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12175): Starting up...
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12258): MountEmulatedStorage()
E/Zygote  (12258): v2
I/libpersona(12258): KNOX_SDCARD checking this for 10150
I/libpersona(12258): KNOX_SDCARD not a persona
,I/SELinux (12258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3480): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12258 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Killing 11261:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/ConnectivityService( 3480): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider(12258): TimaSignature is unavailable
,D/ActivityThread(12258): Added TimaKeyStore provider
,D/SmartBondingService( 3480): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3480): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3480): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3480): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
,D/SmartBondingService( 3480): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3480): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6265): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6265): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5227): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5227): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11907): type=WIFI subType= reason=null isConnected=true
,D/ResourcesManager(12258): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12258): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12258): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12258): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12258): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/art     ( 3480): Explicit concurrent mark sweep GC freed 87903(4MB) AllocSpace objects, 16(304KB) LOS objects, 24% free, 49MB/65MB, paused 2.362ms total 178.617ms
,D/SecContentProvider2( 3480): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3480): mCursor = null
,I/QuickConnect(12258): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12279): MountEmulatedStorage()
E/Zygote  (12279): v2
I/libpersona(12279): KNOX_SDCARD checking this for 10178
I/libpersona(12279): KNOX_SDCARD not a persona
,I/SELinux (12279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3480): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12279 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (12279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Killing 11313:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12279): TimaSignature is unavailable
,D/ActivityThread(12279): Added TimaKeyStore provider
,D/ResourcesManager(12279): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12279): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12279): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12279): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12279): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
,D/ConnectivityService( 3480): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/Zygote  (12307): MountEmulatedStorage()
E/Zygote  (12307): v2
I/libpersona(12307): KNOX_SDCARD checking this for 10082
I/libpersona(12307): KNOX_SDCARD not a persona
,I/SELinux (12307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
I/SELinux (12307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12307): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
I/ActivityManager( 3480): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12307 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12323): MountEmulatedStorage()
I/libpersona(12323): KNOX_SDCARD checking this for 1000
E/Zygote  (12323): v2
I/libpersona(12323): KNOX_SDCARD not a persona
,I/SELinux (12323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12323 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3480): Killing 11328:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12307): TimaSignature is unavailable
,D/ActivityThread(12307): Added TimaKeyStore provider
,I/ActivityManager( 3480): Killing 11444:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12323): TimaSignature is unavailable
,D/ResourcesManager(12307): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/ActivityThread(12323): Added TimaKeyStore provider
,D/ResourcesManager(12323): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12307): onCreate
D/BadgeProvider(12307): DatabaseHelper
,D/BadgeProvider(12307): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3480): Killing 11461:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,W/ActivityManager( 3480): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/BadgeProvider(12307): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(12307): sendNotify, [notify] : null
D/BadgeProvider(12307): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12307): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12307): update, [UpdateCount] : 1
D/Launcher.Model( 4000): reloadBadges entered.
,I/jxcore-log(11739): BLE supported!!
I/jxcore-log(11739): 
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12340): MountEmulatedStorage()
E/Zygote  (12340): v2
I/libpersona(12340): KNOX_SDCARD checking this for 10013
I/libpersona(12340): KNOX_SDCARD not a persona
,I/SELinux (12340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12340): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12340 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12340): TimaSignature is unavailable
,D/ActivityThread(12340): Added TimaKeyStore provider
,D/ResourcesManager(12340): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12340): notifyNetworkActivated
,W/ContextImpl(12340): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3480): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12340): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12340): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12340): exit::IDLE
D/InitializeManagerStateMachine(12340): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12340): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12340): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12340): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12340): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): entry::SUCCESS
D/hcjo    (12340): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    (12340): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 4108): Starting #10
,D/InitializeManagerStateMachine(12340): exit::SUCCESS
D/InitializeManagerStateMachine(12340): entry::IDLE
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8786): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 8786): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8786): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 3480): Killing 11482:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SignOutReceiver(11420): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4108): Starting #11
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8786): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8786): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11420): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4108): Starting #12
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8786): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8786): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8786): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8786): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8786): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11420): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4108): Starting #13
,I/Hs20UtilService( 4108): Message received 5007
,D/NearbySettings( 8786): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8786): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3480): callSECApi what=220
D/WifiStateMachine( 3480): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11420): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11878): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11878): sales region : global
I/PCWCLIENTTRACE_PushUtil(11878): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11878): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2857): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3480): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3480
,I/DIAGMON_AGENT(11971): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11971): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/FOTA_Client(11987): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11987): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11987): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12004): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 15:12:32 GMT+01:00 2015
,I/KLMS-2.4.521: (12004): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12004): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12004): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12004): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12004): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12004): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12004): NetworkChangeOperations(): uploadRequestLog().START 
,I/SO_AGENT(12020): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12004): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12004): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onDestroy()
,E/SPPClientService(12055): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11223): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11223): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11223): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11223): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11223): [OR] == isSIMCardReady false ==
,I/SA      (11223): [SCU] == networkStateCheck == true
I/SA      (11223): [DM] getCountryCodeFromCSC : PL
I/SA      (11223): isChinaCountryCode : false
I/SA      (11223): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11223): [OR] == networkStateCheck true ==
,I/SA      (11223): [OR] GetMyCountryZoneTask
I/SA      (11223): [OR] onReceive END
,I/SA      (11223): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5729): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11223): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11223): [SSP] query invoked
,I/SCloudBackupReceiver(12075): Other Intent
,D/accuweather( 5381): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,I/SA      (11223): [TPMU] GetMccFromDB : null
I/SA      (11223): [SCU] getMccFromPreferece mcc = 260
I/SA      (11223): [TPM] isNoProxy(default) : true
,D/accuweather( 5381): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5381): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5381): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5381): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5381): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5381): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12109): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12109): premStatus:2
,I/KnoxUsageLogPro(12109): isEulaShown : false
I/KnoxUsageLogPro(12109): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12156): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12156): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12156): stopCheckCategoryVersion
,D/QuickConnect(12258): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12258): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12258): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
,D/RCPManagerService( 3480): exchangeData() failure , invalid userId
,D/hcjo    (12340): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12340): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12340): exit::IDLE
D/InitializeManagerStateMachine(12340): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12340): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12340): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12340): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12340): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12340): entry::SUCCESS
D/hcjo    (12340): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12340): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12340): exit::SUCCESS
D/InitializeManagerStateMachine(12340): entry::IDLE
,I/dhcpcd  (11939): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (11939): wlan0: sendmsg: Cannot assign requested address
,I/SA      (11223): [RC New] Execute method=[GET] start
,I/SA      (11223): [RC New] Security=[true]
,I/System.out(11223): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11223): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11223): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11223): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2853): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    ( 2853): getNetworkForDns: using netid 503 for uid 10045
,E/WifiStateMachine( 3480): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3480): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3480): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/SmartBondingService( 3480): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3480): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
D/SmartBondingService( 3480): getSBEnabled() enabled =false
V/        ( 2853): QcRouteController
,V/        ( 2853): QcRouteController
,W/NetworkManagementService( 3480): route cmd failed: 
W/NetworkManagementService( 3480): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3480): '
W/NetworkManagementService( 3480): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3480): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3480): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3480): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3480): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3480): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3480): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3480): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3480): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3480): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6951): CM callback handler got msg 524295
D/ConnectivityService( 3480): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6951): CM callback handler got msg 524295
,I/SA      (11223): [RC New] [v2liruge] api execute + 762
,I/SA      (11223): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11223): AsyncTask #1 calls detatch()
,I/SA      (11223): [TPMU] getNetworkMcc : 
,I/SA      (11223): [SCU] saveMccToPreferece Start
I/SA      (11223): [SCU] RegionMCC : 260
,I/SA      (11223): [SSP] query invoked
,I/SA      (11223): [TPMU] GetMccFromDB : null
I/SA      (11223): [SCU] getMccFromPreferece mcc = 260
I/SA      (11223): [SCU] saveMccToPreferece End
,I/SA      (11223): [RC New] executeRequest [v2liruge] end. 834
I/SA      (11223): [RC New] Execute end
,I/SA      (11223): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11223): [OR] GetMyCountryZoneTask Success
,D/WearableService( 4630): callingUid 10014, callindPid: 4630
,D/ResourcesManager(11907): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11907): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11907): Conditions not met for autocaching.
I/MusicLeanback(11907): Stop autocaching.
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11907): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11907): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11907): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11907): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@128a797e that was originally bound here
E/ActivityThread(11907): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@128a797e that was originally bound here
E/ActivityThread(11907): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11907): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11907): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11907): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11907): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11907): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11907): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11907): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11907): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11907): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11907): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11907): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11907): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11907): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11907): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11907): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11907): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3480): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3480): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/PackageManager( 3480): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/SSRM:n  ( 3480): SIOP:: AP = 280, PST = 284, CUR = 61
,I/PowerManagerService( 3480): [PWL] Off : 50s ago
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GAV4    (12175): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger( 2857): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2857): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3480): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3480) eventTime = 145680
,D/PowerManagerService( 3480): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3480 (0x0)
D/PowerManagerService( 3480): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3480, ws=WorkSource{10060}) (elapsedTime=3475)
,I/dhcpcd  (11939): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver(11878): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11878): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11878): ================================================
I/CSTORAGE(11878):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11878): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11878): [GetString-S]
E/art     (11878): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11878): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11878): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11878): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11878): sales region : global
I/PCWCLIENTTRACE_PushUtil(11878): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11878): [ensureRegistration] - No Samsung account
,W/ProcessCpuTracker( 3480): Skipping unknown process pid 12475
,I/dhcpcd  (11939): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11939): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12340): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12340): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12340): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12340): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12340): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12340): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12340): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12340): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12340): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12340): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12340): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12340): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12340): entry::IDLE
,D/SSRM:n  ( 3480): SIOP:: AP = 270, PST = 281, CUR = 29
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3480): Waited long enough for: ServiceRecord{1efea247 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3480): !@Sync 5
,D/SSRM:n  ( 3480): SIOP:: AP = 260, PST = 278, CUR = 52
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:73
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3480): [PWL] Off : 75s ago
,V/AlarmManager( 3480): waitForAlarm result :8
,D/SSRM:n  ( 3480): SIOP:: AP = 260, PST = 276, CUR = 57
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4630): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3480): SIOP:: AP = 260, PST = 275, CUR = 56
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:65
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3480): !@Sync 6
,D/SSRM:n  ( 3480): SIOP:: AP = 260, PST = 270, CUR = 54
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3480): [PWL] Off : 105s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 265, CUR = 51
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 262, CUR = 47
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3480): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3480): !@Sync 7
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 260, CUR = 47,
,W/ProcessCpuTracker( 3480): Skipping unknown process pid 12598
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3480): waitForAlarm result :8
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 257, CUR = 45,
,I/PowerManagerService( 3480): [PWL] Off : 140s ago
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 255, CUR = 42
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3480): !@Sync 8
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 254, CUR = 41
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11739): Connected to the server!
I/jxcore-log(11739): 
,I/chromium(11739): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log(11739): --- start :testFindPeers.js---
I/jxcore-log(11739): 
,I/jxcore-log(11739): testFindPeers created [object Object]
I/jxcore-log(11739): 
,I/jxcore-log(11739): serverPort is 8876
I/jxcore-log(11739): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): initialize: E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9922
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11739): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11739): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11739): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/BluetoothSocket(11739): bindListen(), new LocalSocket 
D/BluetoothSocket(11739): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11739): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12a64e2e
,D/BluetoothSocket(11739): channel: 6
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Waiting for incoming connections...
,D/WifiP2pService( 3480): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: RUNNING
I/io.jxcore.node.ConnectionHelper(11739): start: OK
,I/jxcore-log(11739): StartBroadcasting started ok
I/jxcore-log(11739): 
,D/WifiP2pService( 3480): InactiveState{ what=139265 },
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onWifiStateChanged: State changed to 2
,D/WifiP2pService( 3480): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): startWifiPeerDiscovery: Already started
,I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: RUNNING
I/chromium(11739): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 253, CUR = 42
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3480): [PWL] Off : 180s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 252, CUR = 40
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 9
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 251, CUR = 40
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 251, CUR = 37
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 38
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3480): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3480): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3480): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3480): initializing...
,I/TLC_TIMA_PKM_initialize( 3480): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3480): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3480): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3480): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3480): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3480): process = ffffffff00000000000000000000000a, process_strlen = 32,
,I/TZ: mc_tlc_communication( 3480): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3480): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 3480): device_id = 0x0
I/TZ: mc_tlc_communication( 3480): tlc_open() was called
,I/TZ: mc_tlc_communication( 3480): Opening MobiCore device
I/TZ: mc_tlc_communication( 3480): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3480): Opening the session
,I/TZ: mc_tlc_communication( 3480): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 3480): Trustlet response is completed
,E/Watchdog( 3480): !@Sync 10
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 35
,I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3480): stay LED for fully charged
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3480): [PWL] Off : 225s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 37
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 36,
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 },
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 11
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 36
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 34
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 35
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/WifiDisplayController( 3480): Received list of peers.
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3480): [PWL] Off : 275s ago
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 },
D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,E/Watchdog( 3480): !@Sync 12
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services,
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 34
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 32
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 32
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery,
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,E/Watchdog( 3480): !@Sync 13
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 32,
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,V/AlarmManager( 3480): waitForAlarm result :8
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 32
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3480): [PWL] Off : 330s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 32
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 14
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 31
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 29
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 31
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 15
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 29
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 29
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
,I/jxcore-log(11739): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT8387","peerAvailable":true}]
I/jxcore-log(11739): 
,I/jxcore-log(11739): Found peer : 90:E7:C4:F6:69:77, peerAvailable: true
I/jxcore-log(11739): 
,I/jxcore-log(11739): weAreDoneNow
I/jxcore-log(11739): 
,I/jxcore-log(11739): done, now sending data to server
I/jxcore-log(11739): 
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log(11739): teardown
I/jxcore-log(11739): 
,I/jxcore-log(11739): testFindPeers stopped
I/jxcore-log(11739): 
,I/io.jxcore.node.ConnectionHelper(11739): stop
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): shutdown
,D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@24793665, channel: 6, state: LISTENING
,D/BluetoothSocket(11739): close() this: android.bluetooth.BluetoothSocket@24793665, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12a64e2e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d4d1f3amSocket: android.net.LocalSocket@2a3627eb impl:android.net.LocalSocketImpl@3fac948 fd:FileDescriptor[115]
D/BluetoothSocket(11739): Closing mSocket: android.net.LocalSocket@2a3627eb impl:android.net.LocalSocketImpl@3fac948 fd:FileDescriptor[115]
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:637)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:614)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:514)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
D/WifiP2pService( 3480): InactiveState{ what=139298 }
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Socket is null
D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onIncomingConnectionFailed: Socket is null
D/WifiP2pService( 3480): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: NOT_INITIALIZED
I/jxcore-log(11739): StopBroadcasting went ok
I/jxcore-log(11739): 
D/WifiP2pService( 3480): InactiveState{ what=139307 }
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: INITIALIZED
D/WifiP2pService( 3480): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/chromium(11739): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63),
D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/jxcore-log(11739): --- start :testSendData.js---
I/jxcore-log(11739): 
,I/jxcore-log(11739): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":2}bt-address length : 0
I/jxcore-log(11739): 
,I/jxcore-log(11739): daya100000
I/jxcore-log(11739): 
,I/jxcore-log(11739): check server
I/jxcore-log(11739): 
,I/jxcore-log(11739): serverPort is 32820
I/jxcore-log(11739): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): initialize: E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9922
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11739): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11739): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11739): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,D/BluetoothSocket(11739): bindListen(), new LocalSocket 
D/BluetoothSocket(11739): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(11739): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b4d57c7
D/BluetoothSocket(11739): channel: 6
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): startWifiPeerDiscovery: Started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: RUNNING
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Waiting for incoming connections...
,D/WifiP2pService( 3480): discovery change broadcast true
,I/jxcore-log(11739): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT8387","peerAvailable":true}]
I/jxcore-log(11739): 
,I/jxcore-log(11739): Found peer : HTC-HTC One M8s_PT8387, Available: true
I/jxcore-log(11739): 
,I/jxcore-log(11739): startWithNextDevice
I/jxcore-log(11739): 
,I/jxcore-log(11739): device[1]: 90:E7:C4:F6:69:77
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:14.329Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:14.331Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:14.332Z SendDataConnector.js: do connect now
I/jxcore-log(11739): 
,I/io.jxcore.node.ConnectionHelper(11739): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper(11739): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): connect: Android_608e
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper(11739): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
I/io.jxcore.node.ConnectionHelper(11739): start: OK
,I/jxcore-log(11739): StartBroadcasting started ok
I/jxcore-log(11739): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 1659)
,I/jxcore-log(11739): null
I/jxcore-log(11739): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils(11739): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,I/jxcore-log(11739): 2015-12-10T14:18:14.353Z SendDataTCPServer.js: TCP/IP server is bound to port: 32820
I/jxcore-log(11739): 
,W/BluetoothAdapter(11739): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 5634): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 5634): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5634): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5634): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 5634): db_query_execute: result 1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): startWifiPeerDiscovery: Already started
,I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
D/BluetoothSocket(11739): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=147493 }
D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): discovery change broadcast false
,I/chromium(11739): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/PowerManagerService( 3480): [PWL] Off : 390s ago
,I/PowerManagerService( 3480): [PWL]   PowerManagerService.WakeLocks: ref count=1,
,I/PowerManagerService( 3480): [PWL]     mWakeLockSummary : 0x1,
,I/PowerManagerService( 3480): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5634, ws=null) (elapsedTime=335)
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 28
,W/bt-btif ( 5634): scb return value : 1
,D/IOP_DB_BT( 5634): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 5634): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5634): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5634): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5634): db_query_execute: result 1
,W/bt-btif ( 5634): info:x10
D/        ( 5634): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5634): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8786): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 5634): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 5634): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,V/BluetoothEventManager( 8786): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 3480): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5634): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5634): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5634): isSecureModeOn:false
I/BluetoothBondStateMachine( 5634): Entering PendingCommandState State
,D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8786): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 8786): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8786): onReceive
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12953): MountEmulatedStorage()
E/Zygote  (12953): v2
I/libpersona(12953): KNOX_SDCARD checking this for 10102
I/libpersona(12953): KNOX_SDCARD not a persona
,I/SELinux (12953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3480): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.common.receiver.AutoLaunchReceiver: pid=12953 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/SELinux (12953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12953): TimaSignature is unavailable
,D/ActivityThread(12953): Added TimaKeyStore provider
,D/ResourcesManager(12953): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager(12953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/btif_config_util( 5634): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5634): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 5634): Failed to remove device: 90:E7:C4:F6:69:77
,D/SecContentProvider( 3480): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5634): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5634): isSecureModeOn:false
,V/BluetoothEventManager( 8786): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/BluetoothTile( 3694):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3694):  handleUpdatestate:false name:null
,D/HidService( 5634): getHidService(): returning com.android.bluetooth.hid.HidService@4265d72
,D/SettingsProvider( 3480): name = bluetooth_input_device_priority_90:E7:C4:F6:69:77
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 1002
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
,D/HidService( 5634): Saved priority 90:E7:C4:F6:69:77 = -1
,D/SettingsProvider( 3480): name = bluetooth_a2dp_sink_priority_90:E7:C4:F6:69:77
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 1002
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
,D/SettingsProvider( 3480): name = bluetooth_headset_priority_90:E7:C4:F6:69:77
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 1002
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
I/BluetoothBondStateMachine( 5634): StableState(): Entering Off State
,E/[CarMode](12953): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager(12953): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(12953): mContext is not null
,I/VlingoAndroidCore(12953): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12977): MountEmulatedStorage()
E/Zygote  (12977): v2
I/libpersona(12977): KNOX_SDCARD checking this for 10034
I/libpersona(12977): KNOX_SDCARD not a persona
,I/SELinux (12977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=12977 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/SELinux (12977): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12977): TimaSignature is unavailable
,D/ActivityThread(12977): Added TimaKeyStore provider
,D/ResourcesManager(12977): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/System.out(12977): Inside WakeupProvider
,E/DatabaseUtils(12977): Writing exception to parcel
E/DatabaseUtils(12977): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12977): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12977): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12977): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12977): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12977): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12977): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12977): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12977): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12977): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12977): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(12953): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(12953): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err(12953): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
,W/System.err(12953): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
,W/System.err(12953): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
,W/System.err(12953): 	at android.content.ContentResolver.query(ContentResolver.java:484)
,W/System.err(12953): 	at android.content.ContentResolver.query(ContentResolver.java:428)
,W/System.err(12953): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
,W/System.err(12953): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
,W/System.err(12953): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(12953): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(12953): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(12953): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
,W/System.err(12953): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(12953): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(12953): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12953): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12953): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12953): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12953): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12953): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12953): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12953): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils(12977): Writing exception to parcel
E/DatabaseUtils(12977): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12977): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12977): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12977): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12977): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12977): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12977): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12977): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12977): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12977): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12977): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(12953): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(12953): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12953): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12953): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12953): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12953): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12953): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12953): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12953): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12953): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(12953): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(12953): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(12953): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(12953): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12953): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12953): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12953): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12953): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12953): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12953): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12953): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode](12953): [DLApplication]-Init Called!:false
W/[CarMode](12953): [CommonUtil]-=========================================
W/[CarMode](12953): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](12953): [CommonUtil]-=========================================
E/[CarMode](12953): [DLApplication]-Init Started!:true
I/[CarModeFW](12953): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](12953): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](12953): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](12953): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](12953): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](12953): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](12953): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](12953): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](12953): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](12953): ### android.os.Looper::loop(145)
I/[CarModeFW](12953): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](12953): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](12953): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](12953): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication(12977): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
I/MessageDataHandler(12953): initialize
D/[CarModeFW](12953): CDH-initiazlieCaches : before sync
D/[CarModeFW](12953): CDH-initiazlieCaches : after sync
,D/[CarModeFW](12953): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW](12953): CDH-ContactDataHandler initiazlieCaches time : 22
D/[CarModeFW](12953): CDH-initiazlieCaches : end sync
,I/VlingoAndroidCore(12977): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
,D/[CarModeFW](12953): DrivingManager-initialize...
,I/SensorService( 3480): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3480): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3480): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3480): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3480): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,D/VlingoApplication(12977): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,I/MediaPlayer(12953): Need to enable context aware info
V/MediaPlayer-JNI(12953): native_setup
V/MediaPlayer(12953): constructor
D/VlingoApplication(12977): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(12977): initQueue()
,V/MediaPlayer(12953): setListener
,D/[CarModeFW](12953): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW](12953): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode](12953): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1449757096268
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1449757096268
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1449757096273
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1449757096273
,D/[CarMode](12953): [DLServiceManager]-updateLocationList
D/[CarMode](12953): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW](12953): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 11
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1449757096282
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1449757096284
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1449757096284
D/[CarModeFW](12953): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,D/TP/SmsProvider( 3979): query,matched:2, calling pid = 12953
,D/TP/SmsProvider( 3979): query,matched:2, calling pid = 12953
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 3979): match 2:Elapsed time : 1.435 ms
D/TP/SmsProvider( 3979): match 2:Elapsed time : 1.381 ms
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
F/DLApplication(12953): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,I/[CarMode](12953): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW](12953): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 15
,D/[CarModeFW](12953): ContactDataHandler-getFavoriteContactList : cur len = 0
,E/Zygote  (13022): MountEmulatedStorage()
E/Zygote  (13022): v2
I/libpersona(13022): KNOX_SDCARD checking this for 10047
D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 22
I/libpersona(13022): KNOX_SDCARD not a persona
,I/SELinux (13022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3480): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=13022 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/[CarMode](12953): [DLApplication]-Init End!:true
,D/[CarModeFW](12953): CalllogDataHandler-getCalllogList : cur len = 0
E/SELinux (13022): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/[CarMode](12953): [TAG]-phone sound mode is: 0
V/[CarMode](12953): [DLApplication]-savePreviousGpsState
,D/MessageDataHandler(12953):  getInboxList smsCursor : 42
,D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 49
,D/TP/MmsProvider( 3979): Query uri=content://mms, match=0, calling pid = 12953
,D/TP/MmsProvider( 3979): Query uri=content://mms/inbox, match=2, calling pid = 12953
,V/[CarMode](12953): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/MessageDataHandler(12953):  getInboxList mmsCursor : 9
,I/MessageDataHandler(12953): getUnreadMessageCount :0
D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 54
,D/MessageDataHandler(12953):  getInboxList mms,sms cursor join : 6
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 12953
V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 4.456 ms
,D/[CarMode](12953): [DLApplication]-GooglePlayServices SUCCESS.
,E/[CarMode](12953): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/TP/MmsSmsProvider( 3979): query,matched:13, calling pid = 12953
,D/TP/MmsSmsProvider( 3979): match 13:Elapsed time : 2.070 ms
,D/TimaKeyStoreProvider(13022): TimaSignature is unavailable
,I/[CarMode](12953): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](12953): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
D/ActivityThread(13022): Added TimaKeyStore provider
,D/[CarMode](12953): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/MessageDataHandler(12953):  getInboxList address cursor : 16
D/[CarMode](12953): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED HTC One M8s state is 11
,D/DialogFlow(12953): initQueue()
,I/ActivityManager( 3480): Killing 11532:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 12953
,V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 2.552 ms
,D/ResourcesManager(13022): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager(13022): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MessageDataHandler(12953):  getInboxList thread cursor : 17
,D/MessageDataHandler(12953):  thread, addr result: 6
I/[CarModeFW](12953): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 113
I/[CarModeFW](12953): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 113
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2(13022): CalendarProvider2.onCreate() called
,E/Zygote  (13037): MountEmulatedStorage()
I/libpersona(13037): KNOX_SDCARD checking this for 10121
E/Zygote  (13037): v2
I/libpersona(13037): KNOX_SDCARD not a persona
,I/SELinux (13037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=13037 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SELinux (13037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/[CarModeFW](12953): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/TimaKeyStoreProvider(13037): TimaSignature is unavailable,
D/ActivityThread(13037): Added TimaKeyStore provider
,D/[CarModeFW](12953): ConnectivityManager-handleMessage PAIRING_DEVICES
,I/ActivityManager( 3480): Killing 11514:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/ActivityManager( 3480): Killing 11547:com.android.calendar/u0a164 (adj 15): bgCount ##32
,D/ResourcesManager(13037): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/art     ( 3480): Explicit concurrent mark sweep GC freed 66590(5MB) AllocSpace objects, 108(1729KB) LOS objects, 24% free, 49MB/65MB, paused 1.334ms total 115.937ms
,I/System.out(12977): INFO:Resource not found:/Common.properties Using default values
,E/BluetoothHeadset(13037): BTStateChangeCB is registed
,E/BluetoothHeadset(13037): BluetoothHeadset service is binded
,D/GMFPReceiver(13037): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver(13037): jangil::setProperties()
,D/GMFPReceiver(13037): jangil::printBTStatus()
,D/[CarModeFW](12953): LocationDataHandler-No schedules found.
,D/SettingsProvider( 3480): name = Wearable0001
D/[CarModeFW](12953): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 10121
,D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,W/BackupManagerService( 3480): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/GMFPReceiver(13037): ::::::::Wearable0001::false
,D/SettingsProvider( 3480): name = Wearable0002
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 10121
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
,W/BackupManagerService( 3480): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,E/Zygote  (13058): MountEmulatedStorage()
,E/Zygote  (13058): v2
I/libpersona(13058): KNOX_SDCARD checking this for 10003
I/libpersona(13058): KNOX_SDCARD not a persona
,D/GMFPReceiver(13037): ::::::::Wearable0002::false
,I/SELinux (13058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/GMFPReceiver(13037): onServiceConnected() : 1
D/GMFPReceiver(13037): mBluetoothHeadset = true
,I/SELinux (13058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3480): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=13058 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,D/BluetoothNotiBroadcastReceiver( 8786): onReceive
,D/[CarMode](12953): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12953): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED HTC One M8s state is 10
,D/TimaKeyStoreProvider(13058): TimaSignature is unavailable
,D/ActivityThread(13058): Added TimaKeyStore provider
,V/[CarModeFW](12953): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(13037): BTStateChangeCB is registed
,D/ResourcesManager(13058): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/BluetoothHeadset(13037): BluetoothHeadset service is binded
,D/GMFPReceiver(13037): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13037): jangil::setProperties()
,D/GMFPReceiver(13037): jangil::printBTStatus()
,D/SettingsProvider( 3480): name = Wearable0001
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 10121
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
,D/GMFPReceiver(13037): ::::::::Wearable0001::false
D/SettingsProvider( 3480): name = Wearable0002
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 10121
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
,D/GMFPReceiver(13037): ::::::::Wearable0002::false
D/GMFPReceiver(13037): onServiceConnected() : 1
,D/GMFPReceiver(13037): mBluetoothHeadset = true
,I/ActivityManager( 3480): Killing 10821:com.android.defcontainer/u0a5 (adj 15): bgCount ##31
,D/UserAnalysis.PlaceProvider(13058): PlaceProvider onCreate()
,D/BootupListener( 3979): ACTION_DRIVELINK
,D/SettingsProvider( 3480): name = drivelink_navigation
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 1001
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
D/BootupListener( 3979): NAVI : com.here.app.maps
,D/SettingsProvider( 3480): name = internet_call_settings_visibility
D/SettingsProvider( 3480): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3480): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3480): selectionArgs: false
D/SettingsProvider( 3480): selectionArgs: 1001
D/SecContentProvider( 3480): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3480): ret = -1
D/BootupListener( 3979): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/UserAnalysis.SecureDbManager(13058): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(13058): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(13058): Create SecureDbHelper
,D/IntelligenceServiceApplication(13058): onCreate()
,D/[CarModeFW](12953): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](12953): MyPlaceProvider-=============
D/[CarModeFW](12953): MyPlaceProvider-=============
D/[CarModeFW](12953): MyPlaceProvider-=============
D/[CarModeFW](12953): MyPlaceProvider-=============
D/[CarModeFW](12953): MyPlaceProvider-=============
,D/[CarModeFW](12953): MyPlaceProvider-=============
D/[CarModeFW](12953): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](12953): MyPlaceProvider-==============
D/[CarModeFW](12953): MyPlaceProvider-==============
D/[CarModeFW](12953): MyPlaceProvider-==============
D/[CarModeFW](12953): MyPlaceProvider-==============
D/[CarModeFW](12953): MyPlaceProvider-==============
,D/[CarModeFW](12953): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1449757096805 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](12953): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(12953): loadLocationDestinationList is null
D/[CarModeFW](12953): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 525
,I/CalendarProvider2(13022): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13082): MountEmulatedStorage()
,E/Zygote  (13082): v2
I/libpersona(13082): KNOX_SDCARD checking this for 10022
I/libpersona(13082): KNOX_SDCARD not a persona
,I/SELinux (13082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3480): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=13082 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/SELinux (13082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Killing 11622:com.android.vending/u0a31 (adj 15): bgCount ##31
E/SELinux (13082): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 945us total 23.634ms
,D/TimaKeyStoreProvider(13082): TimaSignature is unavailable
,D/ActivityThread(13082): Added TimaKeyStore provider
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 989us total 19.877ms
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager(13082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13082): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13082): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 803us total 18.398ms
,I/LocationWidgetApplication(13082): onCreate() : start
,D/LocationWidgetApplication(13082): countryCode = POLAND
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
D/LocationWidgetUtils(13082): getUpcommingInstances() start: 1449757097794, end: 1450306799999
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
D/LocationWidgetUtils(13082): getUpcommingInstances() DB begin time >= start:1449757097794, DB begin time <= end:1450306799999
,E/Zygote  (13106): MountEmulatedStorage()
E/Zygote  (13106): v2
I/libpersona(13106): KNOX_SDCARD checking this for 10163
I/libpersona(13106): KNOX_SDCARD not a persona
,I/SELinux (13106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3480): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=13106 uid=10163 gids={50163, 9997} abi=armeabi-v7a
E/SELinux (13106): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Killing 12307:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(13106): TimaSignature is unavailable
,D/ActivityThread(13106): Added TimaKeyStore provider
,D/ResourcesManager(13106): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(13106): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13106): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13121): MountEmulatedStorage()
E/Zygote  (13121): v2
I/libpersona(13121): KNOX_SDCARD checking this for 10164
I/libpersona(13121): KNOX_SDCARD not a persona
,I/SELinux (13121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=13121 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
E/SELinux (13121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3480): Killing 11420:com.samsung.android.snote/u0a160 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11420/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(13121): TimaSignature is unavailable
,D/ActivityThread(13121): Added TimaKeyStore provider
,D/ResourcesManager(13121): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(13121): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(13121): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13121): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13121): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3480): stay LED for fully charged
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/LocationManagerService( 3480): getProviders()=[]
D/LocationManagerService( 3480): getProviders()=[passive]
D/LocationManagerService( 3480): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LWLocationManager(13082): mPrivacy is null
,W/ContextImpl(13082): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3480): Killing 11878:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,D/ContextFramework:PrivacyManager(13082): Service for PrivacyManager is connected
,D/LWLocationManager(13082): Privacy service : STATUS_PLACE
D/LWLocationManager(13082): updateLocationStatus()
,I/LocationWidgetFuctionData(13082): readDB
,I/LocationWidgetFuctionData(13082): selectedAppSize: 3
I/LocationWidgetFuctionData(13082): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(13082): selectedAppSize: 3
,I/LocationWidgetFuctionData(13082): selectedAppSize: 3
,I/LocationWidgetFuctionData(13082): selectedAppSize: 3
,I/LocationWidgetFuctionData(13082): selectedAppSize: 3
,E/LWLocationManager(13082): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(13082): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(13082): setShouldUpdateLocationId
D/LWLocationManager(13082): setShouldUpdateLocationId return false
D/LWLocationManager(13082): setShouldUpdateLocationId
D/LWLocationManager(13082): setShouldUpdateLocationId return false
D/LWLocationManager(13082): setShouldUpdateLocationId
D/LWLocationManager(13082): setShouldUpdateLocationId return false
D/LWLocationManager(13082): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,W/bt-btif ( 5634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 5634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 5634): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket(11739): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3750cd1d
,E/BluetoothRemoteDevices( 5634): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Incoming connection accepted
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,W/bt-btif ( 5634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5634): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5634): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onSocketConnected: Authenticating next: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 1659)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): onBytesWritten: 82 bytes successfully written (thread ID: 1661)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread(11739): Entering thread (ID: 1661)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): Outgoing connection initialized (*handshake* thread ID: 1661)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): Exiting thread (thread ID: 1659)
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Incoming connection initialized (thread ID: 1660)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Waiting for incoming connections...
D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread(11739): Entering thread (ID: 1660)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): onBytesRead: Read 81 bytes successfully (thread ID: 1660)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): onBytesWritten: 82 bytes successfully written (thread ID: 1660)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): removeThreadFromList: Removing thread with ID 1660
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Handshake thread disposed (thread ID: 1660)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread(11739): Exiting thread (ID: 1660)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/io.jxcore.node.ConnectionHelper(11739): onConnected: Incoming connection, peer ID: 90:E7:C4:F6:69:77, name: HTC-HTC One M8s_PT8387, Bluetooth address: 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper(11739): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
,I/io.jxcore.node.ConnectionHelper(11739): onConnected: Incoming socket thread, for peer with ID 90:E7:C4:F6:69:77, created successfully
D/io.jxcore.node.ConnectionHelper(11739): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread(11739): Entering thread (ID: 1662)
,D/EnterpriseController( 2853): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2853): getNetworkForDns: using netid 503 for uid 10482
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): onBytesRead: Read 81 bytes successfully (thread ID: 1661)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11739): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onAuthenticated: Fully connected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread(11739): Exiting thread (ID: 1661)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/io.jxcore.node.ConnectionHelper(11739): onConnected: Outgoing connection, peer ID: 90:E7:C4:F6:69:77, name: HTC-HTC One M8s_PT8387, Bluetooth address: 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper(11739): hasConnection: We have an incoming connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper(11739): onConnected: Already connected with peer (ID: 90:E7:C4:F6:69:77), continuing anyway...
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
,I/io.jxcore.node.IncomingSocketThread(11739): Local host address: localhost/127.0.0.1, port: 32820
D/io.jxcore.node.IncomingSocketThread(11739): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread(11739): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread(11739): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.ConnectionHelper(11739): onConnected: Outgoing socket thread, for peer with ID 90:E7:C4:F6:69:77, created successfully
D/io.jxcore.node.ConnectionHelper(11739): onConnected: The total number of connections is now 2
,I/io.jxcore.node.StreamCopyingThread(11739): Entering thread (ID: 1664, name: Sender)
,I/io.jxcore.node.OutgoingSocketThread(11739): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread(11739): Exiting thread (ID: 1662)
,I/jxcore-log(11739): 2015-12-10T14:18:20.794Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11739): 
,D/io.jxcore.node.OutgoingSocketThread(11739): Entering thread (ID: 1663)
,D/io.jxcore.node.OutgoingSocketThread(11739): Server socket local port: 35228
I/io.jxcore.node.OutgoingSocketThread(11739): Now accepting connections...
,I/io.jxcore.node.StreamCopyingThread(11739): Entering thread (ID: 1665, name: Receiver)
,I/io.jxcore.node.ConnectionHelper(11739): onListeningForIncomingConnections: Outgoing connection is using port 35228 (peer ID: 90:E7:C4:F6:69:77)
,I/jxcore-log(11739): 2015-12-10T14:18:21.098Z SendDataConnector.js: CLIENT connected to 35228, error: null
I/jxcore-log(11739): 
I/jxcore-log(11739): 2015-12-10T14:18:21.098Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11739): 
,I/io.jxcore.node.OutgoingSocketThread(11739): Incoming data from address: /127.0.0.1, port: 35228
D/io.jxcore.node.OutgoingSocketThread(11739): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11739): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11739): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11739): Entering thread (ID: 1666, name: Sender)
I/io.jxcore.node.OutgoingSocketThread(11739): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread(11739): Exiting thread (ID: 1663)
,I/io.jxcore.node.StreamCopyingThread(11739): Entering thread (ID: 1667, name: Receiver)
,I/jxcore-log(11739): 2015-12-10T14:18:21.106Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11739): 
,D/        ( 5634): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11978
,I/jxcore-log(11739): 2015-12-10T14:18:21.523Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.575Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.585Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.674Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.726Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.741Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log(11739): 
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc,
I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/jxcore-log(11739): 2015-12-10T14:18:21.819Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.924Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.936Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.950Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:21.987Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.027Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.121Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.135Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.301Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.319Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.421Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.453Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.518Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.746Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.760Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.793Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.815Z SendDataTCPServer.js: TCP/IP server has received 67516 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.883Z SendDataTCPServer.js: TCP/IP server has received 69496 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.914Z SendDataTCPServer.js: TCP/IP server has received 77416 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.929Z SendDataTCPServer.js: TCP/IP server has received 83356 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.933Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:22.969Z SendDataTCPServer.js: TCP/IP server has received 85336 bytes of data
I/jxcore-log(11739): 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log(11739): 2015-12-10T14:18:23.040Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.079Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.145Z SendDataTCPServer.js: TCP/IP server has received 99196 bytes of data
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.178Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11739): 
,D/        ( 5634): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17330
,W/bt-btif ( 5634): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread(11739): Either failed to read from the output stream or write to the input stream (thread ID: 1665, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11739): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper(11739): onDisconnected: Incoming connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1662
,I/io.jxcore.node.OutgoingSocketThread(11739): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11739): doStop: Thread ID: 1665
,I/io.jxcore.node.OutgoingSocketThread(11739): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11739): doStop: Thread ID: 1664
,I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11739): Either failed to read from the output stream or write to the input stream (thread ID: 1664, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11739): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11739): onDisconnected: Incoming connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/jxcore-log(11739): 2015-12-10T14:18:23.239Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11739): 
,I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread(11739): closeBluetoothSocketAndStreams
D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@2d545b92, channel: 6, state: CONNECTED
,D/BluetoothSocket(11739): close() this: android.bluetooth.BluetoothSocket@2d545b92, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25bda963, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ef7960mSocket: android.net.LocalSocket@1d321e19 impl:android.net.LocalSocketImpl@13d89ede fd:FileDescriptor[115]
D/BluetoothSocket(11739): Closing mSocket: android.net.LocalSocket@1d321e19 impl:android.net.LocalSocketImpl@13d89ede fd:FileDescriptor[115]
,D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@2d545b92, channel: 6, state: CLOSED
D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@2d545b92, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread(11739): Exiting thread (ID: 1664, name: Sender)
,I/io.jxcore.node.StreamCopyingThread(11739): Exiting thread (ID: 1665, name: Receiver)
,I/jxcore-log(11739): 2015-12-10T14:18:23.254Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11739): 
,E/Watchdog( 3480): !@Sync 16
,D/        ( 5634): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7430
,I/jxcore-log(11739): 2015-12-10T14:18:23.360Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.441Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.545Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.808Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.879Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.888Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.935Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.940Z SendDataConnector.js: got all data for this round
I/jxcore-log(11739): 
,I/jxcore-log(11739): oneRoundDownNow
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.949Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:18:23.951Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11739): 
,D/io.jxcore.node.ConnectionHelper(11739): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
,I/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
,I/io.jxcore.node.OutgoingSocketThread(11739): close
,I/io.jxcore.node.OutgoingSocketThread(11739): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11739): doStop: Thread ID: 1667
I/io.jxcore.node.OutgoingSocketThread(11739): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11739): doStop: Thread ID: 1666
,I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11739): Either failed to read from the output stream or write to the input stream (thread ID: 1666, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11739): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11739): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread(11739): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread(11739): closeBluetoothSocketAndStreams
D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@315778bf, channel: 6, state: CONNECTED
,D/BluetoothSocket(11739): close() this: android.bluetooth.BluetoothSocket@315778bf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bc2cb8c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@163d82d5mSocket: android.net.LocalSocket@3bcbcaea impl:android.net.LocalSocketImpl@2894e1db fd:FileDescriptor[117]
,D/BluetoothSocket(11739): Closing mSocket: android.net.LocalSocket@3bcbcaea impl:android.net.LocalSocketImpl@2894e1db fd:FileDescriptor[117]
,W/io.jxcore.node.StreamCopyingThread(11739): Either failed to read from the output stream or write to the input stream (thread ID: 1667, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11739): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper(11739): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@315778bf, channel: 6, state: CLOSED
,D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@315778bf, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper(11739): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread(11739): Exiting thread (ID: 1666, name: Sender)
E/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper(11739): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread(11739): Exiting thread (ID: 1667, name: Receiver)
,I/jxcore-log(11739): 2015-12-10T14:18:23.984Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log(11739): 
,W/bt-btif ( 5634): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log(11739): ---- round done--------
I/jxcore-log(11739): 
,I/jxcore-log(11739): startWithNextDevice
I/jxcore-log(11739): 
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 9
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,E/bt-btm  ( 5634): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5634): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3694): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 5634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bcfd180
D/KeyguardViewMediator( 3694): isGear1: device is not B1!
,D/BtConfig.SecureMode( 5634): isSecureModeOn:false
,V/BluetoothEventManager( 8786): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 8786): ACTION_ACL_DISCONNECTED
,D/SecContentProvider( 3480): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 5634): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,V/[CarModeFW](12953): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12953): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
D/[CarModeFW](12953): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12953): ConnectivityManager-Paired Devices list is empty
,E/[CarMode](12953): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4054): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4054): Bluetooth Device Name: HTC One M8s
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3480): stay LED for fully charged
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3480): Skipping unknown process pid 13223
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 22
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 24
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,E/Watchdog( 3480): !@Sync 17
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 27
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
,I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 28
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 28
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3480): [PWL] Off : 455s ago
,E/Watchdog( 3480): !@Sync 18
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 28
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 27
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 27
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 19
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 27
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services,
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3480): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 26
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 27
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3480): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3480): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3480): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3480): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 26
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3480): [PWL] Off : 525s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 27
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3480): Killing 11949:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##31
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 25
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 21
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 25
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services,
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3480): discovery change broadcast false
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
D/WifiP2pService( 3480): discovery change broadcast true
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
D/WifiP2pService( 3480): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 },
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 24
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3480): stay LED for fully charged
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 250, PST = 250, CUR = 22
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3480): !@Sync 22
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 249, CUR = 22,
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 249, CUR = 24
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery,
,D/WifiP2pService( 3480): InactiveState{ what=139307 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/PowerManagerService( 3480): [PWL] Off : 600s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 249, CUR = 24
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc,
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 23
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 248, CUR = 24
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 248, CUR = 23
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 248, CUR = 23
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/Watchdog( 3480): !@Sync 24
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 247, CUR = 21
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 247, CUR = 22
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 247, CUR = 21
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 25
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery,
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 246, CUR = 22
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 },
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/PowerManagerService( 3480): [PWL] Off : 680s ago
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 246, CUR = 20
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 246, CUR = 20
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 26
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 245, CUR = 22
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery,
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 245, CUR = 21
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 245, CUR = 21
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 27
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 244, CUR = 20
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 244, CUR = 19
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 244, CUR = 19
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 28
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 243, CUR = 20
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3480): [PWL] Off : 765s ago
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 243, CUR = 20
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,D/WifiP2pService( 3480): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
D/WifiP2pService( 3480): InactiveState{ what=139265 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
D/WifiP2pService( 3480): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 243, CUR = 19
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 29
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 242, CUR = 18
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 242, CUR = 18
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 242, CUR = 20
,D/TimaService( 3480): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3480): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3480): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3480): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 241, CUR = 20
,W/ProcessCpuTracker( 3480): Skipping unknown process pid 13690
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 241, CUR = 20
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services,
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
D/WifiP2pService( 3480): InactiveState{ what=147477 }
D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
D/WifiDisplayController( 3480): Received list of peers.
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
D/WifiP2pService( 3480): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/WifiDisplayController( 3480): Received list of peers.
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/WifiP2pService( 3480): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 241, CUR = 19
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 },
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 31
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 18
,I/PowerManagerService( 3480): [PWL] Off : 855s ago
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged,
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 18
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 32
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 17
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
,I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Peer already exists in the list of peers
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 33
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3480): !@Sync 34,
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 17
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/PowerManagerService( 3480): [PWL] Off : 950s ago
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3480): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 35
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 14
,E/Watchdog( 3480): !@Sync 36
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,D/WifiP2pService( 3480): remove channel information from framework
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3480): discovery change broadcast false
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
D/WifiP2pService( 3480): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
D/WifiP2pService( 3480): discovery change broadcast true
D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3480): P2pEnabledState discover services
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,E/Watchdog( 3480): !@Sync 37
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4393, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3480): [PWL] Off : 1050s ago
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=147494 },
D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 38
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15,
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,E/Watchdog( 3480): !@Sync 39
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 14
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
D/WifiP2pService( 3480): discovery change broadcast true
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/TimaService( 3480): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3480): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3480): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3480): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3480): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3480): Updating Usage Statistics in DB @ 1449757821829
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
,W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.a,ndroid.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUs,age.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3480): ::getAppControlDB: Exception to create DB
W/System.err( 3480): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3480): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3480): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3480): Done Updating Usage Statistics in DB @ 1449757821946
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/Watchdog( 3480): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3480): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3480): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully,
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 14
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
D/WifiP2pService( 3480): InactiveState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-57
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,E/Watchdog( 3480): !@Sync 41
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,I/PowerManagerService( 3480): [PWL] Off : 1155s ago
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13,
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3480): stay LED for fully charged
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 12
,E/Watchdog( 3480): !@Sync 42
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
,D/WifiP2pService( 3480): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): remove channel information from framework
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
D/WifiP2pService( 3480): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 3480): InactiveState{ what=139283 }
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 14
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/WifiP2pService( 3480): InactiveState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3480): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8387","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8387 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: 1 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper(11739): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT8387, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
,I/io.jxcore.node.ConnectionHelper(11739): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,E/Watchdog( 3480): !@Sync 43
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 12
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 11
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,D/BatteryService( 3480): stay LED for fully charged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 12,
,E/Watchdog( 3480): !@Sync 44
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 14
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): start: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT9922","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper(11739): onPeerListChanged: Got a list of peers, which is null
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,D/WifiP2pService( 3480): InactiveState{ what=139292 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3480): P2pEnabledState add service
,D/WifiP2pService( 3480): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local service added successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 3833): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,D/WifiP2pService( 3480): InactiveState{ what=139310 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 },
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,I/PowerManagerService( 3480): [PWL] Off : 1265s ago
,E/Watchdog( 3480): !@Sync 45
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,E/Watchdog( 3480): !@Sync 46
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13,
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 12
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): startServiceDiscovery: Invalid state, try calling restart()
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 11
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...,
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
D/WifiDisplayController( 3480): Received list of peers.
D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/Watchdog( 3480): !@Sync 47
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3480): stay LED for fully charged
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3480): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 13
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3480): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 11
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3480): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): restart: Restarting...
,D/WifiP2pService( 3480): InactiveState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3480): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,E/Watchdog( 3480): !@Sync 48
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): start: Starting peer discovery...
,D/WifiP2pService( 3480): InactiveState{ what=139265 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139265 }
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
,D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery started successfully
,D/WifiP2pService( 3480): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 3480): InactiveState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3480): P2pEnabledState add service request
,D/WifiP2pManager(11739): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service request added successfully
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/WifiP2pService( 3480): InactiveState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3480): P2pEnabledState discover services
,D/WifiService( 3480): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3480): callSECApi what=74
D/WifiStateMachine( 3480): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3480): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3833): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): onServiceListChanged: Got empty list
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 11
,I/wpa_supplicant( 3833): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService( 3480): InactiveState{ what=147477 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3480): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3480): InactiveState{ what=139283 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3480): DefaultState{ what=139283 }
,D/WifiDisplayController( 3480): Received list of peers.
,D/WifiDisplayController( 3480):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3480):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3480): stay LED for fully charged
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 11
,I/PowerManagerService( 3480): [PWL] Off : 1380s ago
,D/BatteryService( 3480): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3480): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3480): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3480): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3480): Plugged
,I/MotionRecognitionService( 3480): setPowerConnected  = true
,D/BatteryService( 3480): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5634): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3480): SIOP:: AP = 240, PST = 240, CUR = 11
,E/Watchdog( 3480): !@Sync 49
,I/jxcore-log(11739): timeout now
I/jxcore-log(11739): 
,I/jxcore-log(11739): weAreDoneNow, resultArray.length: 1
I/jxcore-log(11739): 
,I/jxcore-log(11739): sendReportNow
I/jxcore-log(11739): 
,I/jxcore-log(11739): done, now sending data to server
I/jxcore-log(11739): 
,I/jxcore-log(11739): 2015-12-10T14:34:54.371Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11739): 
,I/jxcore-log(11739): teardown
I/jxcore-log(11739): 
,I/jxcore-log(11739): testSendData stopped
I/jxcore-log(11739): 
,I/io.jxcore.node.ConnectionHelper(11739): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): shutdown
D/BluetoothSocket(11739): close() in, this: android.bluetooth.BluetoothSocket@2c69bf89, channel: 6, state: LISTENING
D/BluetoothSocket(11739): close() this: android.bluetooth.BluetoothSocket@2c69bf89, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b4d57c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e587b8emSocket: android.net.LocalSocket@2f260faf impl:android.net.LocalSocketImpl@3c562fbc fd:FileDescriptor[116]
D/BluetoothSocket(11739): Closing mSocket: android.net.LocalSocket@2f260faf impl:android.net.LocalSocketImpl@3c562fbc fd:FileDescriptor[116]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11739): stop: Stopping services
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:637)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:614)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:514)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11739): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11739): onServerStopped
D/WifiP2pService( 3480): InactiveState{ what=139298 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onIsDiscoveryStartedChanged: false
D/WifiP2pService( 3480): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): setState: NOT_INITIALIZED
,I/jxcore-log(11739): StopBroadcasting went ok
I/jxcore-log(11739): 
D/WifiP2pService( 3480): InactiveState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3480): P2pEnabledState clear service request
D/WifiP2pService( 3480): remove channel information from framework
,D/WifiP2pService( 3480): InactiveState{ what=139268 }
,I/wpa_supplicant( 3833): P2P-FIND-STOPPED 
I/jxcore-log(11739): 2015-12-10T14:34:54.456Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log(11739): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11739): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper(11739): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11739): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Service requests cleared successfully
D/WifiP2pService( 3480): InactiveState{ what=147493 }
,D/WifiP2pService( 3480): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11739): Peer discovery stopped successfully
,D/WifiP2pService( 3480): discovery change broadcast false
,I/jxcore-log(11739): ****TEST TOOK:  ms ****
I/jxcore-log(11739): 
,I/jxcore-log(11739): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11739): 
,I/chromium(11739): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime(14367): 
D/AndroidRuntime(14367): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(14367): CheckJNI is OFF
,D/AndroidRuntime(14367): readGMSProperty: start
D/AndroidRuntime(14367): readGMSProperty: already setted!!
,D/AndroidRuntime(14367): readGMSProperty: end
D/AndroidRuntime(14367): addProductProperty: start
,E/AffinityControl(14367): AffinityControl: registerfunction enter
,D/AndroidRuntime(14367): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3480): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3480): START PACKAGE DELETE: observer{599063877}
D/PackageManager( 3480): pkg{<packageName>}
D/PackageManager( 3480): user{0}
D/PackageManager( 3480): caller{2000}
D/PackageManager( 3480): flags{3}
D/PersonaManagerService( 3480): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3480): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3480): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3480): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3480): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3480): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3480): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3480): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3480): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3480): !@killApplicatoin: 10482, uninstall pkg
,I/ActivityManager( 3480): Force stopping com.test.thalitest appid=10482 user=-1: uninstall pkg
,I/ActivityManager( 3480): Killing 11739:com.test.thalitest/u0a482 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3480):   Force finishing activity ActivityRecord{1410aa6 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3480): mDVFSHelper.acquire()
,W/PackageSettings( 3480): Skipping PackageSetting{230061f1 com.example.hello/10462} due to missing metadata
,I/WindowState( 3480): WIN DEATH: Window{29976a5c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3480): Client connection lost with reason: 4
,I/SurfaceFlinger( 2857): id=14 Removed NainActivit (5/8)
,D/PointerIcon( 3480): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3480): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3480): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3480): setHoveringSpenCustomIcon IconType is same.1
,I/art     ( 3480): Background sticky concurrent mark sweep GC freed 114441(10MB) AllocSpace objects, 301(4MB) LOS objects, 13% free, 50MB/58MB, paused 3.372ms total 115.507ms
,I/ActivityManager( 3480): Force stopping com.test.thalitest appid=10482 user=0: pkg removed
,I/ActivityManager( 3480):   Force finishing activity ActivityRecord{1410aa6 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3480): Duplicate finish request for ActivityRecord{1410aa6 u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3480): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,I/art     ( 8934): Explicit concurrent mark sweep GC freed 28468(1608KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.229ms total 40.474ms
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     ( 6951): Explicit concurrent mark sweep GC freed 30686(1752KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.070ms total 68.947ms
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/InputReader( 3480): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/GeofencerStateMachine( 4630): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4465): mOCRHelper is null
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 7
,I/art     ( 4054): Explicit concurrent mark sweep GC freed 37358(2MB) AllocSpace objects, 2(55KB) LOS objects, 21% free, 28MB/36MB, paused 750us total 80.680ms
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/LWLocationManager(13082): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(13082): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
D/ResourcesManager( 3480): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,E/Zygote  (14387): MountEmulatedStorage()
E/Zygote  (14387): v2
I/libpersona(14387): KNOX_SDCARD checking this for 10063
I/libpersona(14387): KNOX_SDCARD not a persona
,I/SELinux (14387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3480): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=14387 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/SELinux (14387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (14387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3480): uri = 14 selection = getSealedState
D/SecContentProvider2( 3480): mCursor = null
,D/ApplicationPolicy( 3480): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3480): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/TimaKeyStoreProvider(14387): TimaSignature is unavailable
,D/ActivityThread(14387): Added TimaKeyStore provider
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
,I/art     ( 3480): Explicit concurrent mark sweep GC freed 25186(1657KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 49MB/65MB, paused 2.770ms total 143.885ms
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6265): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6265): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6265): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,W/ResourceType( 5227): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5227): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ActivityManager( 3480): post active user change for 0
D/KnoxTimeoutHandler( 3480): postActiveUserChange for user 0
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6265): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2857): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3480): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/StatusBarManagerService( 3480): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/PointerIcon( 3480): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3480): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3480): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3480): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityThread( 6265): updateVisibility : ActivityRecord{1e636669 token=android.os.BinderProxy@13ed0722 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager(14387): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/InputMethodManagerService( 3480): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 3480): Got RemoteException sending setActive(false) notification to pid 11739 uid 10482
,W/ContextImpl( 3480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/PackageManager( 3480): delete codoeFile: 
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/AASAUninstall( 3480):  com.test.thalitest not target!
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/PackageManager( 3480): result of delete: 1{599063877}
D/RegisteredServicesCache( 3964): empty dynamic service
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/AndroidRuntime(14367): Shutting down VM
D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/VRSetupWizardStub/PackageIntentReceiver(14387): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(14387): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(14387): packagename:com.test.thalitest
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/KLMS-2.4.521: (12004): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 15:34:55 GMT+01:00 2015
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Timeline( 6265): Timeline: Activity_idle id: android.os.BinderProxy@13ed0722 time:1484994
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/KLMS-2.4.521: (12004): KLMSAbstractReciever(): onReceive().END.
,D/SecContentProvider2( 3480): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3480): mCursor = null
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/splitIntent( 3480): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3480): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.521: (12004): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12004): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12004): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12004): KLMSIntentService(): PACKAGE_REMOVED
D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/KLMS-2.4.521: (12004): KLMSIntentService(): listeningToPackageRemoved().START
,E/Zygote  (14408): MountEmulatedStorage()
E/Zygote  (14408): v2
I/libpersona(14408): KNOX_SDCARD checking this for 10106
I/libpersona(14408): KNOX_SDCARD not a persona
,I/SELinux (14408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12004): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/SELinux (14408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=14408 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (14408): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3480): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(13082): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/RCPManagerService( 3480): PackageReceiver onReceive()
I/HarmonyEASService( 3480): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3480): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3480): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3480): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3480): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3480): uID is 10482
V/EnterpriseBillingPolicy( 3480): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3480): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3480): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3480): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3480): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3480): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3480): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
D/RCPManager(12109):  in createShortcut() for packageName: com.test.thalitest userId0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3480):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3480): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/TimaKeyStoreProvider(14408): TimaSignature is unavailable
,D/ActivityThread(14408): Added TimaKeyStore provider
,E/Zygote  (14423): MountEmulatedStorage()
,E/Zygote  (14423): v2
I/libpersona(14423): KNOX_SDCARD checking this for 10160
I/libpersona(14423): KNOX_SDCARD not a persona
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/SELinux (14423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=14423 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
E/SELinux (14423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 3480): mDVFSHelper.release()
I/Timeline( 3480): Timeline: Activity_windows_visible id: ActivityRecord{16ad8a5d u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1485082
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(13082): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13082): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13082): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/Zygote  (14438): MountEmulatedStorage()
E/Zygote  (14438): v2
I/libpersona(14438): KNOX_SDCARD checking this for 10050
I/libpersona(14438): KNOX_SDCARD not a persona
,I/SELinux (14438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(14423): TimaSignature is unavailable
,E/SELinux (14438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityThread(14423): Added TimaKeyStore provider
D/ResourcesManager(13082): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/ActivityManager( 3480): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=14438 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/KLMS-2.4.521: (12004): KLMSIntentService(): listeningToPackageRemoved().END
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(14408): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/Zygote  (14453): MountEmulatedStorage()
E/Zygote  (14453): v2
I/libpersona(14453): KNOX_SDCARD checking this for 10101
I/libpersona(14453): KNOX_SDCARD not a persona
,I/SELinux (14453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=14453 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (14453): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(14423): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/TimaKeyStoreProvider(14438): TimaSignature is unavailable
,D/ActivityThread(14438): Added TimaKeyStore provider
,W/ResourcesManager(14423): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(14423): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(14423): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(14408): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(14408): ELMEngine.ELMEngine( context ).
,D/elm:14491(14408): MDMBridge.setEnterpriseBridge()
D/KnoxTimeoutHandler( 3480): handleActiveUserChange for user 0
,D/TaskPersister( 3480): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3480): removeObsoleteFile: deleting file=24_task.xml
,D/elm:14491(14408): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/KLMS-2.4.521: (12004): KLMSIntentService(): onDestroy()
,D/elm:14491(14408): ElmAgentService : onCreate()
,D/elm:14491(14408): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(13082): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491(14408): MainReceiver.listeningToPackageRemoved()
D/elm:14491(14408): MDMBridge.getInstance()
D/elm:14491(14408): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(14408): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(14453): TimaSignature is unavailable
,D/ActivityThread(14453): Added TimaKeyStore provider
,D/ResourcesManager(13082): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(14438): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ResourcesManager(14438): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/Zygote  (14470): MountEmulatedStorage()
E/Zygote  (14470): v2
I/libpersona(14470): KNOX_SDCARD checking this for 10019
I/libpersona(14470): KNOX_SDCARD not a persona
,I/SELinux (14470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=14470 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (14470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/PanelView( 3694): There is/are notification(s) 
D/PanelView( 3694): There is/are notification(s) 
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
I/StatusBar( 3694): Icon Only
D/elm:14491(14408): ElmAgentService : onDestroy().
D/PanelView( 3694): There is/are notification(s) 
D/ResourcesManager(13082): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/ResourcesManager(14438): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(14438): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(14438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(14438): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(14438): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(14438): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(14438): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3480): Killing 11971:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##31
,I/ActivityManager( 3480): Killing 11987:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##31
,D/ResourcesManager(14453): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider(14470): TimaSignature is unavailable
,D/ActivityThread(14470): Added TimaKeyStore provider
,V/Common  (14423): getScreenSize 1440 2560
,D/ResourcesManager(14470): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/JAM     (14423): Load The ApaService JNI
,I/JAM     (14423): version: ProfessionalAudio_v1.0.b5
I/JAM     (14423): Try v1.0.b3 ...
D/Spen    (14423): SpenSdk version level = 55
D/Spen    (14423): SpenSdk jar version = 3.0.243
,D/Spen    (14423): SpenSdk apk version = 3.0.235
D/Spen    (14423): Server UPDATE Check
,W/linker  (14423): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
E/Zygote  (14490): MountEmulatedStorage()
E/Zygote  (14490): v2
I/libpersona(14490): KNOX_SDCARD checking this for 10160
I/libpersona(14490): KNOX_SDCARD not a persona
,D/SPenError(14423): JNI_OnLoad
,D/JNI_Bitmap(14423): Init .. Done
D/SPenSpiDecoder(14423): JNI_OnLoad .. Done
D/SPenError(14423): JNI_OnLoad Success
,D/PluginManager(14423): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(14423): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(14423): JNI_OnLoad
,D/Init_SPenSdk_Jni(14423): AndroidSDK: 21
D/Init_SPenSdk_Jni(14423): JNI_OnLoad .. Done
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/Model_ObjectBase_Jni(14423): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(14423): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(14423): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(14423): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(14423): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(14423): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(14423): check build type eng[0]
D/Model_NoteDoc_Jni(14423): JNI_OnLoad .. Done
I/ActivityManager( 3480): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=14490 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
I/SELinux (14490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/Model_NoteFile_Jni(14423): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(14423): JNI_OnLoad .. Done
D/Model   (14423): OnLoad class Done
,I/SELinux (14490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/spe_log (14423): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
D/SPen_Library(14423): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(14423): Canvas JNI_OnLoad enter!!
,E/SELinux (14490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SPen_Library(14423): Canvas JNI_OnLoad Success
D/SPen_Library(14423): TextView JNI_OnLoad enter!!
,D/SPen_Library(14423): TextView JNI_OnLoad Success
D/SPen_Library(14423): Text JNI_OnLoad enter!!
D/SPen_Library(14423): Text JNI_OnLoad Success
D/SPen_Library(14423): FontManager JNI_OnLoad enter!!
D/SPen_Library(14423): FontManager JNI_OnLoad Success
D/SPen_Library(14423): CapturePage JNI_OnLoad enter!!
D/SPen_Library(14423): CapturePage JNI_OnLoad Success
D/SPen_Library(14423): Multi JNI_OnLoad enter!!
,D/SPen_Library(14423): Multi JNI_OnLoad Success
D/SPen_Library(14423): Draw Engine JNI_OnLoad Success
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/SPen_Library(14423): Brush JNI_OnLoad enter!!
,D/SPen_Library(14423): Brush JNI_OnLoad Success
D/DocsApplication(14453): Installing DEX configuration.
,D/SPen_Library(14423): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(14423): ChineseBrush JNI_OnLoad Success
D/com.sec.android.service.health.upgrade.UninstallReceiver(14470): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(14470): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(14470): onReceive() : package name is not s health. Return !!!
,D/SPen_Library(14423): InkPen JNI_OnLoad enter!!
,D/SPen_Library(14423): InkPen JNI_OnLoad Success
,D/DexInstaller(14453): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/SPen_Library(14423): Marker JNI_OnLoad enter!!
D/SPen_Library(14423): Marker JNI_OnLoad Success
I/PackageInfoHelper(14453): Provided clientMode=RELEASE, packageInfo=PackageInfo{43a8581 com.google.android.apps.docs}
,D/SPen_Library(14423): Pencil JNI_OnLoad enter!!
D/TAG     (14453): onCreate()
,D/SPen_Library(14423): Pencil JNI_OnLoad Success
E/SQLiteLog(14438): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,D/SPen_Library(14423): NativePen JNI_OnLoad enter!!
D/SPen_Library(14423): NativePen JNI_OnLoad Success
,D/CrossAppStateProvider(14453): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/SPen_Library(14423): MontblancFountainPen JNI_OnLoad enter!!
D/SPen_Library(14423): MontblancFountainPen JNI_OnLoad Success
,E/SQLiteDatabase(14438): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(14438): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(14438): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(14438): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(14438): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(14438): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(14438): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(14438): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(14438): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(14438): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(14438): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(14438): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/SPen_Library(14423): MontblancCalligraphyPen JNI_OnLoad enter!!
D/LocationWidgetApplication(13082): getLastUiLocationId() : mLastUiLocationId = -100
D/SPen_Library(14423): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(14423): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(14423): MagicPen JNI_OnLoad Success
,D/SPen_Library(14423): ObliquePen JNI_OnLoad enter!!
D/SPen_Library(14423): ObliquePen JNI_OnLoad Success
D/SPen_Library(14423): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(14423): FountainPen JNI_OnLoad Success
D/Spen    (14423): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(14423): SPenSdk_init2
D/Init_SPenSdk(14423): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(14423): Total S Pen SDK Directory Size = 0
D/Spen    (14423): initialize complete
,W/linker  (14423): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/UsbHostManager( 3480): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3480): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3480): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3480): displayNotification : [0ah,00h,00h]
D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/UsbHostManager( 3480): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3480): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3480): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3480): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3480): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3480): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3480): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/SharedPreferencesImpl(14438): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3480): findPreferredActivity: No PreferredActivities set
D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/TimaKeyStoreProvider(14490): TimaSignature is unavailable
,D/ActivityThread(14490): Added TimaKeyStore provider
D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Zygote  (14515): MountEmulatedStorage()
,E/Zygote  (14515): v2
I/libpersona(14515): KNOX_SDCARD checking this for 1000
I/libpersona(14515): KNOX_SDCARD not a persona
,I/SELinux (14515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=14515 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (14515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3480): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3480): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3480): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3480): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/ActivityManager( 3480): Killing 12020:com.sec.android.soagent/u0a38 (adj 15): bgCount ##31
,I/EventHub( 3480): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(13082): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/ActivityManager( 3480): Killing 11223:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,I/ActivityManager( 3480): Killing 12035:com.policydm/1000 (adj 15): bgCount ##32
,E/lowmemorykiller( 2827): Error writing /proc/12035/oom_score_adj; errno=22
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Books/Books.apk
I/EventHub( 3480): Removing device '/dev/input/event7' due to inotify event
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,E/Zygote  (14531): MountEmulatedStorage()
E/Zygote  (14531): v2
I/libpersona(14531): KNOX_SDCARD checking this for 10183
I/libpersona(14531): KNOX_SDCARD not a persona
I/SELinux (14531): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14531): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (14531): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3480): Removing device '/dev/input/event8' due to inotify event
,I/ActivityManager( 3480): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=14531 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider(14515): TimaSignature is unavailable
,D/ActivityThread(14515): Added TimaKeyStore provider
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.220ms total 44.164ms
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 987us total 30.799ms
,D/ResourcesManager(14490): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/TimaKeyStoreProvider(14531): TimaSignature is unavailable
,I/art     ( 2897): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 597us total 29.290ms
,D/ActivityThread(14531): Added TimaKeyStore provider
,W/ResourcesManager(14490): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(14490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(14490): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/NearbySource(14438): Nearby Source Create!
D/NearbyContext(14438): Nearby Context Create!
,D/ResourcesManager(14515): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(14438): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(14438): Samsung link source created
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(14531): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,I/PCWCLIENTTRACE_LOG(14515): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG(14515): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper(14515): new DMDBOpenHelper instance
,E/SQLiteLog(14515): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(14515): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(14515): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(14515): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(14515): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(14515): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(14515): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(14515): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(14515): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(14515): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(14515): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(14515): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(14515): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(14515): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(14515): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(14515): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(14515): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(14515): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(14515): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(14515): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(14515): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(14515): Shutting down VM
,E/AndroidRuntime(14515): FATAL EXCEPTION: main
E/AndroidRuntime(14515): Process: com.sec.pcw.device, PID: 14515
E/AndroidRuntime(14515): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(14515): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(14515): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(14515): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(14515): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(14515): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(14515): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(14515): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(14515): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(14515): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(14515): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(14515): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(14515): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(14515): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(14515): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(14515): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(14515): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(14515): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(14515): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(14515): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(14515): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(14515): 	... 11 more
,D/SNoteProvider(14490): onCreate enableSnoteSync = true
,E/SQLiteLog(14438): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(14438): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(14438): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(14438): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(14438): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(14438): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(14438): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(14438): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(14438): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(14438): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(14438): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(14438): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(14438): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(14438): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(14438): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(14438): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(14438): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(14438): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(14438): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(14438): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(14438): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(14438): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(14438): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(14438): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(14438): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(14438): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(14438): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(14438): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(14438): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(14438): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(14438): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(14438): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(14438): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(14438): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(14438): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(14438): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(14438): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(14438): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(14438): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(14438): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/ApplicationPolicy( 3480): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,W/SQLiteOpenHelper(14438): Opened local.db in read-only mode
,E/SQLiteLog(14531): (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30),
,E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
,D/SNoteProvider(14490): ===query=== 
,E/DropBoxManagerService( 3480): Can't write: system_app_crash
E/DropBoxManagerService( 3480): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3480): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3480): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3480): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3480): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3480): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3480): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3480): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3480): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3480): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3480): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3480): 	... 5 more
,E/SQLiteDatabase(14531): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
E/SQLiteDatabase(14531): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(14531): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(14531): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(14531): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(14531): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/SQLiteDatabase(14531): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/SQLiteDatabase(14531): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(14531): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(14531): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(14531): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(14531): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(14531): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(14531): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(14531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(14531): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(14531): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(14531): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(14531): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(14531): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(14531): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(14531): Shutting down VM
,E/AndroidRuntime(14531): FATAL EXCEPTION: main
E/AndroidRuntime(14531): Process: com.samsung.android.provider.shootingmodeprovider, PID: 14531
E/AndroidRuntime(14531): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(14531): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(14531): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(14531): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(14531): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(14531): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(14531): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(14531): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(14531): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(14531): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(14531): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(14531): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(14531): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(14531): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(14531): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(14531): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(14531): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(14531): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:269)
E/AndroidRuntime(14531): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:232)
E/AndroidRuntime(14531): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(14531): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(14531): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(14531): 	... 11 more
,E/SQLiteLog(14490): (28) failed to open "/data/user/0/com.samsung.android.snote/databases/Snote.db" with flag (131138) and mode_t (0) due to error (30)
,D/WifiDisplayAdapter( 3480): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (14551): MountEmulatedStorage()
E/Zygote  (14551): v2
I/libpersona(14551): KNOX_SDCARD checking this for 10035
I/libpersona(14551): KNOX_SDCARD not a persona
,I/SELinux (14551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3480): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=14551 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (14551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/ApplicationPolicy( 3480): isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,E/SQLiteDatabase(14490): Failed to open database '/data/user/0/com.samsung.android.snote/databases/Snote.db'.
E/SQLiteDatabase(14490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(14490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(14490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(14490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(14490): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
E/SQLiteDatabase(14490): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
E/SQLiteDatabase(14490): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
E/SQLiteDatabase(14490): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(14490): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(14490): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(14490): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Process (14515): Sending signal. PID: 14515 SIG: 9
,E/DropBoxManagerService( 3480): Can't write: system_app_crash
E/DropBoxManagerService( 3480): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3480): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3480): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3480): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3480): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3480): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3480): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3480): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3480): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3480): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3480): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3480): 	... 5 more
,W/System.err(14490): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(14490): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
W/System.err(14490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
W/System.err(14490): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
W/System.err(14490): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/ActivityManager( 3480): checkUser: useridlist=null, currentuser=0
W/System.err(14490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(14490): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(14490): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(14490): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(14490): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(14490): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(14490): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(14490): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(14490): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(14490): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:156)
W/System.err(14490): 	at com.samsung.android.snote.model.provider.SNoteProvider.a(SourceFile:2285)
W/System.err(14490): 	at com.samsung.android.snote.model.provider.SNoteProvider.query(SourceFile:751)
W/System.err(14490): 	at android.content.ContentProvider.query(ContentProvider.java:987)
W/System.err(14490): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
W/System.err(14490): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
W/System.err(14490): 	at android.os.Binder.execTransact(Binder.java:446)
D/SNoteProvider(14490): message = not an error (code 0): Could not open the database in read/write mode.
,V/Common  (14490): getScreenSize 1440 2560
D/ResourcesManager(13082): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk

```
