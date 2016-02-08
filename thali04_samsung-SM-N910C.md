#### Test 581356550b07fff_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,I/PowerManagerService( 3523): [PWL] Off : 140s ago
D/SSRM:n  ( 3523): SIOP:: AP = 260, PST = 268, CUR = 58
--------- beginning of main
D/AndroidRuntime(11639): 
D/AndroidRuntime(11639): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11639): CheckJNI is OFF
D/AndroidRuntime(11639): readGMSProperty: start
D/AndroidRuntime(11639): readGMSProperty: already setted!!
D/AndroidRuntime(11639): readGMSProperty: end
D/AndroidRuntime(11639): addProductProperty: start
E/AffinityControl(11639): AffinityControl: registerfunction enter
D/AndroidRuntime(11639): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11657): MountEmulatedStorage()
E/Zygote  (11657): v2
I/libpersona(11657): KNOX_SDCARD checking this for 10637
I/libpersona(11657): KNOX_SDCARD not a persona
I/SELinux (11657): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11657): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11657 uid=10637 gids={50637, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11657): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11639): Shutting down VM
D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11657): TimaSignature is unavailable
D/ActivityThread(11657): Added TimaKeyStore provider
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11657): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6189): updateVisibility : ActivityRecord{36ec1dd0 token=android.os.BinderProxy@a02d24d {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory(11657): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11657): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11657): Loading: webviewchromium
,I/LibraryLoader(11657): Time to load native libraries: 5 ms (timestamps 5019-5024)
I/LibraryLoader(11657): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11657): Binding Chromium to main looper Looper (main, tid 1) {1b8cc092}
,I/LibraryLoader(11657): Expected native library version number "",actual native library version number ""
,I/chromium(11657): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11657): Initializing chromium process, renderers=0
,W/art     (11657): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11657): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11657): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11657): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11657): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11657): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11657): Attempt to remove local handle scope entry from IRT, ignoring
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:61
D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3523): stay LED for fully charged
,I/MotionRecognitionService( 3523): Plugged
I/MotionRecognitionService( 3523): setPowerConnected  = true
,W/AwContents(11657): onDetachedFromWindow called when already detached. Ignoring
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5617): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5617): Disconnected process message: 10
,D/SystemWebViewEngine(11657): CordovaWebView is running on device made by: samsung
,W/art     (11657): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11657): Attempt to remove local handle scope entry from IRT, ignoring
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ActivityManager( 3523): Activity pause timeout for ActivityRecord{123ea4e u0 com.test.thalitest/.MainActivity t26}
,D/Activity(11657): performCreate Call secproduct feature valuefalse
D/Activity(11657): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11657): Render dirty regions requested: true
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,V/ActivityThread(11657): updateVisibility : ActivityRecord{dc27242 token=android.os.BinderProxy@1ed71ce1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2851): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11657): Initialized EGL, version 1.4
,I/OpenGLRenderer(11657): HWUI protection enabled for context ,  &this =0xaf6051a0 ,&mEglDisplay = 1 , &mEglConfig = -1278775024 
,D/OpenGLRenderer(11657): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
,D/OpenGLRenderer(11657): Enabling debug mode 0
,D/mali_winsys(11657): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{123ea4e u0 com.test.thalitest/.MainActivity t26} time:235485
,W/IInputConnectionWrapper(11657): showStatusIcon on inactive InputConnection
,I/Timeline(11657): Timeline: Activity_idle id: android.os.BinderProxy@1ed71ce1 time:235489
,W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium(11657): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11657): 
,D/JsMessageQueue(11657): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11657): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
,I/chromium(11657): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11657): Initializing JXcore engine
W/jxcore-log(11657): JXcore engine is ready
,E/auditd  ( 4604): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3523): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3523): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11657): Starting JXcore engine
,W/jxcore-log(11657): Platform android
W/jxcore-log(11657): 
W/jxcore-log(11657): Process ARCH arm
W/jxcore-log(11657): 
,I/jxcore-log(11657): JXcore Cordova bridge is ready!
I/jxcore-log(11657): 
W/jxcore-log(11657): JXcore engine is started
,I/jxcore-log(11657): Toggling radios to true
I/jxcore-log(11657): 
,D/BluetoothAdapter(11657): enable()
,D/BluetoothAdapter(11657): enable(): BT is already enabled..!
,D/WifiService( 3523): New client listening to asynchronous messages
,I/WifiManager(11657): packageName : com.test.thalitest
,D/SecContentProvider( 3523): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3523): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3523): mCursor = null
,D/WifiService( 3523): setWifiEnabled: true pid=11657, uid=10637
,E/WifiService( 3523): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3523): Permission Denial: getCurrentUser() from pid=11657, uid=10637 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3523): Failed getting userId using ActivityManagerNative
W/WifiService( 3523): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11657, uid=10637 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3523): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3523): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3523): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3523): name = wifi_on
I/WifiService( 3523): disconnect: pid=11657, uid=10637
,I/wpa_supplicant( 3825): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11657): Radios toggled
I/jxcore-log(11657): 
,I/jxcore-log(11657): My device name is: samsung-SM-N910C
I/jxcore-log(11657): 
,I/wpa_supplicant( 3825): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3825): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3825): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): Disconnected - do not scan
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3523): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,V/NativeCrypto( 4621): Read error: ssl=0x9c319e00: I/O error during system call, Connection timed out
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3523): updateNetworkInfo()
,V/NativeCrypto( 4621): SSL shutdown failed: ssl=0x9c319e00: I/O error during system call, Broken pipe
,D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/ConnectivityService( 3523): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine( 3523): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3825): First Scan Start
,I/wpa_supplicant( 3825): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3523): ConnectModeState: Network connection lost 
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
E/WifiStateMachine( 3523): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
I/qtaguid ( 3523): Tagging socket 388 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3523, getuid(): 1000
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/Hs20UtilService( 4071): Starting #8
,I/Hs20UtilService( 4071): Message received 5007
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3523): do suspend true
,D/NearbySettings( 8780): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 8780): MountReceiver.onReceive - Start HandlerThread
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
,D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,D/NearbySettings( 8780): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8780): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,V/NearbySettings( 8780): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3523): New client listening to asynchronous messages
,I/NearbySettings( 8780): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8780): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8780): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11247): NETWORK_STATE_CHANGED_ACTION
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener( 2846): Clearing all IP addresses on wlan0
D/ConnectivityService( 3523): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
,E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3523): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 6725): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 3523): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3523): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 3986): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - currTime: 1454950569502
,D/WifiStateMachine( 3523): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,D/EntConnectivity( 3523): Not allowed due to - mEnabled false
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/ConnectivityService( 3523): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService( 3523): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3523): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3523): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
D/Tethering( 3523): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3523): updateIfacesLocked()
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/SmartBondingService( 3523): getSBEnabled() enabled =false
V/NetworkStats( 3523): performPollLocked(flags=0x1)
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
V/NetworkStats( 3523): performPollLocked() took 8ms
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,I/Hs20UtilService( 4071): Starting #9
,I/Hs20UtilService( 4071): Message received 5007
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/NearbySettings( 8780): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8780): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8780): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8780): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8780): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11247): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3986): FileWriteThread : threadType = 3
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
,I/DBG_DM  ( 6189): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6189): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11777): MountEmulatedStorage()
E/Zygote  (11777): v2
I/libpersona(11777): KNOX_SDCARD checking this for 10110
I/libpersona(11777): KNOX_SDCARD not a persona
,I/SELinux (11777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11777 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11777): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11777): TimaSignature is unavailable
,D/ActivityThread(11777): Added TimaKeyStore provider
,D/ResourcesManager(11777): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11777): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11777): not using cross-dex optimization: ART in use
,I/art     (11777): Thread[1,tid=11777,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11777): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11777): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11777): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
,D/DexLibLoader(11777): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11777): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11777): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11777): loading pre-built fallback odex files
V/MultiDexClassLoader(11777): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11777): released odex store lock
D/DexLibLoader(11777): DexLibLoader.loadAll took 17 ms
,W/ca      (11777): Verify
,W/LightSharedPreferencesImpl(11777): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11777): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11777): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11777): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11777): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11777): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11777): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11777): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11777): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11777): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11777): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11777): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11777): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11777): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11777): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11777): 	... 10 more
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11802): MountEmulatedStorage()
E/Zygote  (11802): v2
I/libpersona(11802): KNOX_SDCARD checking this for 1000
I/libpersona(11802): KNOX_SDCARD not a persona
,I/SELinux (11802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11802 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10840:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/10840/oom_score_adj; errno=22
,W/appmanager(:<default>):b(11777): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11777): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11802): TimaSignature is unavailable
,D/ActivityThread(11802): Added TimaKeyStore provider
,D/ResourcesManager(11802): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/art     (11777): No such thread id for suspend: 19
,W/appmanager(:<default>):QuickExperimentControllerImpl(11777): Exposure of experiment com.facebook.common.network.l@29396a7b occurred when no user was logged in
,I/PCWCLIENTTRACE_LOG(11802): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11802): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11802): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11802): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11802): sales region : global
,I/PCWCLIENTTRACE_PushUtil(11802): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11802): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11802): noConnectivity : true
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{846e10c u0 ReceiverList{1ab0743f 11777 com.facebook.appmanager/10110/u0 remote:1252585e}}
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{846e10c u0 ReceiverList{1ab0743f 11777 com.facebook.appmanager/10110/u0 remote:1252585e}}
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11826): MountEmulatedStorage()
I/libpersona(11826): KNOX_SDCARD checking this for 10135
E/Zygote  (11826): v2
I/libpersona(11826): KNOX_SDCARD not a persona
,I/SELinux (11826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11826): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11826 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10855:com.policydm/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11826): TimaSignature is unavailable
,D/ActivityThread(11826): Added TimaKeyStore provider
,D/ResourcesManager(11826): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3523): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3ed41810 u0 ReceiverList{3bcbd4d3 11777 com.facebook.appmanager/10110/u0 remote:26bb4ec2}}
,I/MusicStore(11826): Database version: 104
,D/ResourcesManager(11826): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11826): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11826): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11826): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ebc2cc6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11826): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11826): GMSCore installation verified
,I/ConfigStore(11826): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11777): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11777): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3825): nl80211: Received scan results (4 BSSes)
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11826): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 3825): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3825): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3825): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3523): [1,454,950,570,530 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3523): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@158f579e sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3523): getStreamVolume 3 index 0
,I/MediaRouter(11826): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11859): MountEmulatedStorage()
I/libpersona(11859): KNOX_SDCARD checking this for 10002
E/Zygote  (11859): v2
I/libpersona(11859): KNOX_SDCARD not a persona
,I/SELinux (11859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11859): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11859 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11859): TimaSignature is unavailable
,D/ActivityThread(11859): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 69879(4MB) AllocSpace objects, 45(768KB) LOS objects, 24% free, 49MB/65MB, paused 1.448ms total 94.121ms
,I/NetworkMonitor(11826): type=WIFI subType= reason=null isConnected=false
,D/ResourcesManager(11859): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3523): Killing 10870:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3825): Associated with C0.AA.48
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3523): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,W/appmanager(:<default>):QuickExperimentControllerImpl(11777): Exposure of experiment com.facebook.imagepipeline.a.g@1d98c71 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11777): Exposure of experiment com.facebook.imagepipeline.a.d@3c11d5e2 occurred when no user was logged in
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3825): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3825): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3825): Blacklist: Clear (temp) 
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3523): Network connection established
I/ActivityManager( 3523): Killing 10891:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
D/WifiNative-HAL( 3523): callSECApiVoid - ID [50]
E/WifiStateMachine( 3523): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3523): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3523): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 3523): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
E/WifiStateMachine( 3523): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3523): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/art     (11777): Explicit concurrent mark sweep GC freed 43507(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 553us total 23.475ms
,W/appmanager(:<default>):m(11777): No feature status reporters found; is this dead code?
,E/WifiStateMachine( 3523): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3523): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine( 3523): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3523): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Zygote  (11879): MountEmulatedStorage()
E/Zygote  (11879): v2
I/libpersona(11879): KNOX_SDCARD checking this for 1000
I/libpersona(11879): KNOX_SDCARD not a persona
,I/SELinux (11879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CommandListener( 2846): Setting iface cfg
I/ActivityManager( 3523): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11879 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/WifiStateMachine( 3523): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider(11879): TimaSignature is unavailable
,D/ActivityThread(11879): Added TimaKeyStore provider
,D/ResourcesManager(11879): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11879): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend false
,I/DIAGMON_AGENT(11879): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
D/SecContentProvider2( 3523): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3523): mCursor = null
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT(11879): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11879): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11879): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11898): MountEmulatedStorage()
I/libpersona(11898): KNOX_SDCARD checking this for 10012
E/Zygote  (11898): v2
I/libpersona(11898): KNOX_SDCARD not a persona
I/SELinux (11898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11898): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11898 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11898): TimaSignature is unavailable
,D/ActivityThread(11898): Added TimaKeyStore provider
,D/ResourcesManager(11898): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3523): Killing 10906:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,I/FOTA_Client(11898): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/lowmemorykiller( 2829): Error writing /proc/10906/oom_score_adj; errno=22
,I/FOTA_Client(11898): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11898): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11914): MountEmulatedStorage()
I/libpersona(11914): KNOX_SDCARD checking this for 10021
E/Zygote  (11914): v2
I/libpersona(11914): KNOX_SDCARD not a persona
I/SELinux (11914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11914 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (11914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Killing 10923:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11914): TimaSignature is unavailable
,D/ActivityThread(11914): Added TimaKeyStore provider
,D/ResourcesManager(11914): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11914): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 17:56:10 GMT+01:00 2016
,I/KLMS-2.4.521: (11914): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11914): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11914): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11914): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11914): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (11914): StateImplV2(): networkChangeListener().END
,E/Zygote  (11930): MountEmulatedStorage()
I/libpersona(11930): KNOX_SDCARD checking this for 10038
E/Zygote  (11930): v2
I/libpersona(11930): KNOX_SDCARD not a persona
I/SELinux (11930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11930 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11930): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3523): Killing 10721:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/10721/oom_score_adj; errno=22
,E/dhcpcd  (11941): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11941): version 5.5.6 starting
,E/dhcpcd  (11941): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider(11930): TimaSignature is unavailable
,D/ActivityThread(11930): Added TimaKeyStore provider
,D/ResourcesManager(11930): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11930): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11952): MountEmulatedStorage()
I/libpersona(11952): KNOX_SDCARD checking this for 1000
E/Zygote  (11952): v2
I/libpersona(11952): KNOX_SDCARD not a persona
,I/SELinux (11952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/dhcpcd  (11941): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11941): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11941): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11941): bssid match
I/dhcpcd  (11941): wlan0: rebinding lease of 192.168.1.124
I/SELinux (11952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11952): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11952 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10945:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11952): TimaSignature is unavailable
,D/ActivityThread(11952): Added TimaKeyStore provider
,D/ResourcesManager(11952): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11972): MountEmulatedStorage()
,E/Zygote  (11972): v2
I/libpersona(11972): KNOX_SDCARD checking this for 10039
I/SELinux (11972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/libpersona(11972): KNOX_SDCARD not a persona
,I/SELinux (11972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11972): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=11972 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 10961:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 279us total 9.384ms
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 458us total 9.011ms
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 362us total 8.447ms
,D/TimaKeyStoreProvider(11972): TimaSignature is unavailable
,D/ActivityThread(11972): Added TimaKeyStore provider
,D/ResourcesManager(11972): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(11972): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(11972): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(11972): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(11972): PushLog.txt file is not deleted.
D/SPPClientService(11972): PushLog.txt file is not deleted.
D/SPPClientService(11972): ============PushLog. stop!
,I/SA      (11034): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11034): [SLFUCHKMGR] constructor called
,E/SPPClientService(11972): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11034): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11034): [OR] == isSIMCardReady false ==
,I/SA      (11034): [SCU] == networkStateCheck == false
I/SA      (11034): [OR] onReceive END
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3523): Killing 11014:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11992): MountEmulatedStorage()
I/libpersona(11992): KNOX_SDCARD checking this for 10067
E/Zygote  (11992): v2
I/libpersona(11992): KNOX_SDCARD not a persona
,I/SELinux (11992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=11992 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11992): TimaSignature is unavailable
,D/ActivityThread(11992): Added TimaKeyStore provider
,D/ResourcesManager(11992): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(11992): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(11992): Other Intent
,I/ActivityManager( 3523): Killing 10981:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/accuweather( 5187): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5187): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5187): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5187): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5187): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5187): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5187): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12008): MountEmulatedStorage()
I/libpersona(12008): KNOX_SDCARD checking this for 1000
E/Zygote  (12008): v2
I/libpersona(12008): KNOX_SDCARD not a persona
,I/SELinux (12008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12008): TimaSignature is unavailable
,D/ActivityThread(12008): Added TimaKeyStore provider
,D/ResourcesManager(12008): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12008): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12008): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12008): premStatus:2
,I/KnoxUsageLogPro(12008): isEulaShown : false
I/KnoxUsageLogPro(12008): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12023): MountEmulatedStorage()
I/libpersona(12023): KNOX_SDCARD checking this for 10090
E/Zygote  (12023): v2
I/libpersona(12023): KNOX_SDCARD not a persona
,I/SELinux (12023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12023): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12023 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11104:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12023): TimaSignature is unavailable
,D/ActivityThread(12023): Added TimaKeyStore provider
,D/ResourcesManager(12023): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12039): MountEmulatedStorage()
I/libpersona(12039): KNOX_SDCARD checking this for 10127
E/Zygote  (12039): v2
I/libpersona(12039): KNOX_SDCARD not a persona
,I/SELinux (12039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12039 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11125:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12039): TimaSignature is unavailable
,D/ActivityThread(12039): Added TimaKeyStore provider
,D/ResourcesManager(12039): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12039): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12039): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12039): stopCheckCategoryVersion
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12055): MountEmulatedStorage()
I/libpersona(12055): KNOX_SDCARD checking this for 10136
,E/Zygote  (12055): v2
I/libpersona(12055): KNOX_SDCARD not a persona
I/SELinux (12055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12055): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12055 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11089:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12055): TimaSignature is unavailable
,D/ActivityThread(12055): Added TimaKeyStore provider
,D/ResourcesManager(12055): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12055): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12055): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12055): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12055): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12055): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12055): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12055): Loading: webviewchromium
,I/LibraryLoader(12055): Time to load native libraries: 3 ms (timestamps 9099-9102)
I/LibraryLoader(12055): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12055): Binding Chromium to main looper Looper (main, tid 1) {3bbe4f52}
,I/LibraryLoader(12055): Expected native library version number "",actual native library version number ""
,I/chromium(12055): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12055): Initializing chromium process, renderers=0
,W/art     (12055): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12055): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12055): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12055): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12055): Requires BLUETOOTH permission
,I/NSApplication(12055): Starting up...
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12123): MountEmulatedStorage()
E/Zygote  (12123): v2
I/libpersona(12123): KNOX_SDCARD checking this for 10150
I/libpersona(12123): KNOX_SDCARD not a persona
,I/SELinux (12123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12123): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12123 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11143:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,E/lowmemorykiller( 2829): Error writing /proc/11143/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12123): TimaSignature is unavailable
,D/ActivityThread(12123): Added TimaKeyStore provider
,D/ResourcesManager(12123): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12123): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12123): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12123): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12123): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12123): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12123): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12138): MountEmulatedStorage()
E/Zygote  (12138): v2
I/libpersona(12138): KNOX_SDCARD checking this for 10178
I/libpersona(12138): KNOX_SDCARD not a persona
,I/SELinux (12138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3523): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12138 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3523): Killing 11158:com.samsung.helphub/1000 (adj 13): bgCount ##31
E/SELinux (12138): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12138): TimaSignature is unavailable
,D/ActivityThread(12138): Added TimaKeyStore provider
,D/ResourcesManager(12138): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12138): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12138): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12138): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12138): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12138): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/Zygote  (12161): MountEmulatedStorage()
I/libpersona(12161): KNOX_SDCARD checking this for 10082
E/Zygote  (12161): v2
I/libpersona(12161): KNOX_SDCARD not a persona
,I/SELinux (12161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12161): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12161 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12161): TimaSignature is unavailable
,D/ActivityThread(12161): Added TimaKeyStore provider
,D/ResourcesManager(12161): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider(12161): onCreate
D/BadgeProvider(12161): DatabaseHelper
,E/Zygote  (12177): MountEmulatedStorage()
I/libpersona(12177): KNOX_SDCARD checking this for 1000
E/Zygote  (12177): v2
I/libpersona(12177): KNOX_SDCARD not a persona
,I/SELinux (12177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12177 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3523): Killing 11288:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 11270:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##32
,D/BadgeProvider(12161): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider(12177): TimaSignature is unavailable
,D/ActivityThread(12177): Added TimaKeyStore provider
,D/ResourcesManager(12177): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12161): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12161): sendNotify, [notify] : null
D/BadgeProvider(12161): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12161): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12161): update, [UpdateCount] : 1
D/Launcher.Model( 4003): reloadBadges entered.
,W/ActivityManager( 3523): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3523): Killing 11307:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/iu.Environment( 6725): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6725): num queued entries: 0
,I/iu.UploadsManager( 6725): num updated entries: 0
I/iu.SyncManager( 6725): NEXT; no task
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12194): MountEmulatedStorage()
E/Zygote  (12194): v2
I/libpersona(12194): KNOX_SDCARD checking this for 10013
I/libpersona(12194): KNOX_SDCARD not a persona
,I/SELinux (12194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12194): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12194 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12194): TimaSignature is unavailable
,D/ActivityThread(12194): Added TimaKeyStore provider
,D/ResourcesManager(12194): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3523): Killing 11346:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4071): Starting #10
,I/Hs20UtilService( 4071): Message received 5007
,D/NearbySettings( 8780): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8780): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8780): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8780): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11247): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (11941): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (11941): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11657): 
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3523): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3523): do suspend true
,D/WifiP2pService( 3523): InactiveState{ what=143375 }
D/WifiP2pService( 3523): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3523): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3523): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3523): Not connected state, yet.
E/WifiStateMachine( 3523): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3523): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3523): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3523): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3523): callSECApiInt - ID [210]
,E/WifiStateMachine( 3523): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3523): updateNetworkInfo()
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3523): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3523): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3523): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 4071): Starting #11
,D/NearbySettings( 8780): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 4071): Message received 5007
,I/NearbySettings( 8780): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 3523): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 3523): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3523): Now, connected state.
E/WifiStateMachine( 3523): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SignOutReceiver(11247): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3523): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine( 3523): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService( 3523): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3523): Unexpected mtu value: 0, wlan0
I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
,V/        ( 2846): QcRouteController
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3523): evaluateTrafficStatsPolling
E/WifiStateMachine( 3523): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiNative-HAL( 3523): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3523): ConnectedState Enter  mScreenOn=false scanperiod=20000
,V/        ( 2846): QcRouteController
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,V/        ( 2846): QcRouteController
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
,I/Hs20UtilService( 4071): Starting #12
,I/Hs20UtilService( 4071): Message received 5007
V/        ( 2846): QcRouteController
,D/NearbySettings( 8780): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8780): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8780): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8780): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8780): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8780): MountReceiver.mPrefHandler - 7002
,V/        ( 2846): QcRouteController
,I/SignOutReceiver(11247): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2846): QcRouteController
I/Hs20UtilService( 4071): Starting #13
,V/        ( 2846): QcRouteController
I/Hs20UtilService( 4071): Message received 5007
,D/NearbySettings( 8780): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8780): MountReceiver.onReceive - Keep current state
,V/        ( 2846): QcRouteController
,I/WifiStateMachine( 3523): callSECApi what=220
D/WifiStateMachine( 3523): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11247): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3523): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3523): LTETest block dns file not exists
,D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3523): updateNetworkInfo()
D/ConnectivityService( 3523): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Checking http://clients3.google.com/generate_204 on "NG700"
,I/System.out( 3523): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3523):    accepting network in place of null
,D/TelephonyNetworkFactory( 3986): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 3523): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3523): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3523): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3523): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/ConnectivityManager.CallbackHandler( 6725): CM callback handler got msg 524290
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): updateIfacesLocked()
V/NetworkStats( 3523): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3523): UpdateStatsForKnox
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): performPollLocked() took 2ms
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
V/NetworkStats( 3523): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
D/NtpTrustedTime( 3523): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2851): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3523): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
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
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/System.out( 3523): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:56:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454950572609], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454950572591]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3523): Validated
,D/ConnectivityService( 3523): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3523): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3523): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6725): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11657): 
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11657): 
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11657): 
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11657): 
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11657): 
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11657): 
,I/jxcore-log(11657): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11657): 
,D/ConnectivityService( 3523): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3523): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3523): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
D/SmartBondingService( 3523): getSBEnabled() enabled =false
,D/SmartBondingService( 3523): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3523): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6189): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6189): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(11826): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5319): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5319): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11802): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11802): sales region : global
I/PCWCLIENTTRACE_PushUtil(11802): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11802): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11879): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3523): mCursor = null
I/DIAGMON_AGENT(11879): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11898): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11898): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11898): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11914): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 17:56:13 GMT+01:00 2016
,I/KLMS-2.4.521: (11914): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11914): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11914): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SO_AGENT(11930): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11914): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11914): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11914): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11914): NetworkChangeOperations(): uploadRequestLog().START 
,E/SPPClientService(11972): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/KLMS-2.4.521: (11914): NetworkChangeOperations(): uploadRequestLog().END 
,I/SA      (11034): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/KLMS-2.4.521: (11914): StateImplV2(): networkChangeListener().END
I/SA      (11034): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11034): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onDestroy()
,I/SA      (11034): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11034): [OR] == isSIMCardReady false ==
,I/SA      (11034): [SCU] == networkStateCheck == true
I/SA      (11034): [DM] getCountryCodeFromCSC : PL
I/SA      (11034): isChinaCountryCode : false
I/SA      (11034): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11034): [OR] == networkStateCheck true ==
,I/SA      (11034): [OR] GetMyCountryZoneTask
I/SA      (11034): [OR] onReceive END
,I/SA      (11034): [SRS] prepareGetMyCountryZone
,I/SA      (11034): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11034): [SSP] query invoked
,I/SA      (11034): [TPMU] GetMccFromDB : null
I/SA      (11034): [SCU] getMccFromPreferece mcc = 260
I/SA      (11034): [TPM] isNoProxy(default) : true
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SCloudBackupReceiver(11992): Other Intent
,D/accuweather( 5187): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3776): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,D/accuweather( 5187): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5187): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5187): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5187): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5187): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5187): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12008): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12008): premStatus:2
,I/KnoxUsageLogPro(12008): isEulaShown : false
I/KnoxUsageLogPro(12008): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12039): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12039): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12039): stopCheckCategoryVersion
,D/QuickConnect(12123): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12123): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12123): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,D/RCPManagerService( 3523): exchangeData() failure , invalid userId
,I/iu.Environment( 6725): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6725): num queued entries: 0
,I/iu.UploadsManager( 6725): num updated entries: 0
,I/iu.SyncManager( 6725): NEXT; no task
,D/WaitQueueForNetworkActivate(12194): notifyNetworkActivated
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12194): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3523): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12194): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12194): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12194): exit::IDLE
D/InitializeManagerStateMachine(12194): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12194): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12194): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12194): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12194): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12194): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12194): entry::SUCCESS
D/hcjo    (12194): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12194): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    (12194): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12194): exit::SUCCESS
,D/InitializeManagerStateMachine(12194): entry::IDLE
,I/SA      (11034): [RC New] Execute method=[GET] start
,I/SA      (11034): [RC New] Security=[true]
,I/System.out(11034): Thread-1520(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11034): Thread-1520(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11034): Thread-1520(ApacheHTTPLog):isShipBuild true
I/System.out(11034): Thread-1520(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3523): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/WifiStateMachine( 3523): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3523): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3523): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2846): QcRouteController
,D/SmartBondingService( 3523): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3523): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
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
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityService( 3523): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 6725): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6725): CM callback handler got msg 524295
,I/SA      (11034): [RC New] [v2liruge] api execute + 606
I/SA      (11034): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11034): AsyncTask #1 calls detatch()
,I/SA      (11034): [TPMU] getNetworkMcc : 
,I/SA      (11034): [SCU] saveMccToPreferece Start
I/SA      (11034): [SCU] RegionMCC : 260
I/SA      (11034): [SSP] query invoked
,I/SA      (11034): [TPMU] GetMccFromDB : null
I/SA      (11034): [SCU] getMccFromPreferece mcc = 260
I/SA      (11034): [SCU] saveMccToPreferece End
,I/SA      (11034): [RC New] executeRequest [v2liruge] end. 626
I/SA      (11034): [RC New] Execute end
I/SA      (11034): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11034): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (11941): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4621): callingUid 10014, callindPid: 4621
,D/ResourcesManager(11826): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11826): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11826): Conditions not met for autocaching.
I/MusicLeanback(11826): Stop autocaching.
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11826): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11826): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11826): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11826): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@82895e that was originally bound here
E/ActivityThread(11826): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@82895e that was originally bound here
E/ActivityThread(11826): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11826): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11826): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11826): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11826): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11826): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11826): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11826): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11826): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11826): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11826): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11826): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11826): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11826): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11826): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11826): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11826): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11826): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11826): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11826): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11826): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3523): REQUEST_POWER_SAVE_ON
,I/jxcore-log(11657): Test app app.js loaded
I/jxcore-log(11657): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11657): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a77f884 added. We now have 1 listener(s)
,I/jxcore-log(11657): BLE advertisement is supported
I/jxcore-log(11657): 
,I/chromium(11657): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SurfaceFlinger( 2851): id=15 Removed Uoast (8/9)
I/SurfaceFlinger( 2851): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3523): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3523) eventTime = 243479
,D/PowerManagerService( 3523): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3523 (0x0)
D/PowerManagerService( 3523): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3523, ws=WorkSource{10060}) (elapsedTime=3462)
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 54206(3MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 49MB/65MB, paused 2.037ms total 157.610ms
,E/WifiStateMachine( 3523): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log(11657): --= Surplus to requirements =--
I/jxcore-log(11657): 
I/jxcore-log(11657): ****TEST TOOK:  ms ****
I/jxcore-log(11657): 
I/jxcore-log(11657): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11657): 
,I/GAV4    (12055): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12296): 
D/AndroidRuntime(12296): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12296): CheckJNI is OFF
,D/AndroidRuntime(12296): readGMSProperty: start
D/AndroidRuntime(12296): readGMSProperty: already setted!!
,D/AndroidRuntime(12296): readGMSProperty: end
D/AndroidRuntime(12296): addProductProperty: start
,D/SSRM:n  ( 3523): SIOP:: AP = 300, PST = 269, CUR = 52
,E/AffinityControl(12296): AffinityControl: registerfunction enter
,D/AndroidRuntime(12296): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3523): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3523): START PACKAGE DELETE: observer{752325261}
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
,D/PackageManager( 3523): !@killApplicatoin: 10637, uninstall pkg
I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10637 user=-1: uninstall pkg
,I/ActivityManager( 3523): Killing 11657:com.test.thalitest/u0a637 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{123ea4e u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3523): mDVFSHelper.acquire()
,W/PackageSettings( 3523): Skipping PackageSetting{1eda7f42 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3523): Force stopping com.test.thalitest appid=10637 user=0: pkg removed
,I/ActivityManager( 3523):   Force finishing activity ActivityRecord{123ea4e u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3523): Duplicate finish request for ActivityRecord{123ea4e u0 com.test.thalitest/.MainActivity t26 f}
,I/WindowState( 3523): WIN DEATH: Window{352ed544 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3523): Client connection lost with reason: 4
,I/SurfaceFlinger( 2851): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2851): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 2851): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6189): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 6725): Explicit concurrent mark sweep GC freed 25867(1483KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.532ms total 73.927ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 8797): Explicit concurrent mark sweep GC freed 25293(1473KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 2.926ms total 64.237ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/InputReader( 3523): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4494): mOCRHelper is null
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,W/GeofencerStateMachine( 4621): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 6189): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 11
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/LWLocationManager(11329): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11329): getLastUiLocationId() : mLastUiLocationId = -100
,I/DBG_DM  ( 6189): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/art     ( 4055): Explicit concurrent mark sweep GC freed 33083(2028KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 899us total 76.701ms
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  (12317): MountEmulatedStorage()
E/Zygote  (12317): v2
I/libpersona(12317): KNOX_SDCARD checking this for 10063
I/libpersona(12317): KNOX_SDCARD not a persona
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux (12317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3523): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12317 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourceType( 5319): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/ResourceType( 5319): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/SELinux (12317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12317): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/EnterpriseDeviceManagerService( 3523): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3523): Admin package name: com.google.android.gms
I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 866us total 24.965ms
,D/SecContentProvider2( 3523): uri = 14 selection = getSealedState
D/SecContentProvider2( 3523): mCursor = null
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 348us total 15.872ms
,D/ApplicationPolicy( 3523): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 381us total 11.163ms
,I/art     ( 3523): Explicit concurrent mark sweep GC freed 17071(1431KB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 49MB/65MB, paused 5.386ms total 155.427ms
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 11
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/ResourcesManager(11329): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6189): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6189): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6189): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6189): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6189): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3523): post active user change for 0
D/KnoxTimeoutHandler( 3523): postActiveUserChange for user 0
I/DBG_DM  ( 6189): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/TimaKeyStoreProvider(12317): TimaSignature is unavailable
,I/SurfaceFlinger( 2851): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
D/ActivityThread(12317): Added TimaKeyStore provider
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3523): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3523): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,V/ActivityThread( 6189): updateVisibility : ActivityRecord{36ec1dd0 token=android.os.BinderProxy@a02d24d {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/PointerIcon( 3523): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3523): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3523): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(11329): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/SecContentProvider2( 3523): uri = 11 selection = getMyKnoxAdmin
D/ResourcesManager(12317): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/SecContentProvider2( 3523): mCursor = null
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/VRSetupWizardStub/PackageIntentReceiver(12317): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12317): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12317): packagename:com.test.thalitest
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (11914): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 17:56:17 GMT+01:00 2016
,D/RegisteredServicesCache( 3964): empty dynamic service
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/KLMS-2.4.521: (11914): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3523): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3523): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Books/Books.apk
,D/InputMethodManagerService( 3523): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.4.521: (11914): KLMSIntentService(): onCreate()
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11914): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/PackageManager( 3523): delete codoeFile: 
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ContextImpl( 3523): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/AASAUninstall( 3523):  com.test.thalitest not target!
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/InputMethodManagerService( 3523): Got RemoteException sending setActive(false) notification to pid 11657 uid 10637
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/PackageManager( 3523): result of delete: 1{752325261}
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/AndroidRuntime(12296): Shutting down VM
E/Zygote  (12336): MountEmulatedStorage()
E/Zygote  (12336): v2
I/libpersona(12336): KNOX_SDCARD checking this for 10106
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/libpersona(12336): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (11914): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/SELinux (12336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/SELinux (12336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3523): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12336 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (12336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline( 6189): Timeline: Activity_idle id: android.os.BinderProxy@a02d24d time:244930
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.521: (11914): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (11914): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (11914): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11914): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,W/ActivityManager( 3523): mDVFSHelper.release()
I/Timeline( 3523): Timeline: Activity_windows_visible id: ActivityRecord{22beedfa u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:244957
,D/RCPManager(12008):  in createShortcut() for packageName: com.test.thalitest userId0
,D/PackageManager( 3523): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider(12336): TimaSignature is unavailable
,D/ActivityThread(12336): Added TimaKeyStore provider
,D/RCPManagerService( 3523):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3523): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,E/Zygote  (12353): MountEmulatedStorage()
E/Zygote  (12353): v2
I/libpersona(12353): KNOX_SDCARD checking this for 10050
I/libpersona(12353): KNOX_SDCARD not a persona
,I/SELinux (12353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12353 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
W/ResourcesManager(11329): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11914): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(12336): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/Zygote  (12368): MountEmulatedStorage()
E/Zygote  (12368): v2
I/libpersona(12368): KNOX_SDCARD checking this for 10101
D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/libpersona(12368): KNOX_SDCARD not a persona
,I/SELinux (12368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(12353): TimaSignature is unavailable
,E/SELinux (12368): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3523): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12368 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityThread(12353): Added TimaKeyStore provider
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourceType( 3523): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.4.521: (11914): KLMSIntentService(): onDestroy()
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
W/ResourcesManager(11329): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11329): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11329): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11329): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3523): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager(11329): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/elm:14491(12336): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(12336): ELMEngine.ELMEngine( context ).
,D/elm:14491(12336): MDMBridge.setEnterpriseBridge()
E/Zygote  (12383): MountEmulatedStorage()
I/libpersona(12383): KNOX_SDCARD checking this for 10183
E/Zygote  (12383): v2
I/libpersona(12383): KNOX_SDCARD not a persona
,I/SELinux (12383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager( 3523): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12383 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/SELinux (12383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(12368): TimaSignature is unavailable
D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ActivityThread(12368): Added TimaKeyStore provider
,D/ResourcesManager(12353): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14491(12336): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/ResourcesManager(12353): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12353): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12353): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12353): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12353): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12353): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(12353): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12353): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/elm:14491(12336): ElmAgentService : onCreate()
,D/elm:14491(12336): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(12336): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12336): MDMBridge.getInstance()
D/elm:14491(12336): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3523): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/elm:14491(12336): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider(12383): TimaSignature is unavailable
,D/ActivityThread(12383): Added TimaKeyStore provider
,I/ActivityManager( 3523): Killing 11362:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(12368): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/RCPManagerService( 3523): PackageReceiver onReceive()
I/HarmonyEASService( 3523): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:14491(12336): ElmAgentService : onDestroy().
,D/KnoxMUMContainerPolicy( 3523): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3523): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3523): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3523): uID is 10637
V/EnterpriseBillingPolicy( 3523): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3523): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - personal application - profile null
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
V/EnterpriseBillingPolicy( 3523): packageModificationReceiver - onreceive - might be a vpn vendor package 
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - start - com.test.thalitest
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
V/EnterpriseBillingPolicyStorage( 3523): getBillingProfileForVpnEngine - end - null
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11329): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3523): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(12383): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(11329): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3523): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  (12400): MountEmulatedStorage()
E/Zygote  (12400): v2
I/libpersona(12400): KNOX_SDCARD checking this for 10019
I/libpersona(12400): KNOX_SDCARD not a persona
,I/SELinux (12400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12400 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/UsbSettingsManager( 3523): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3523): onPackageRemoved : com.test.thalitest
,I/ActivityManager( 3523): Killing 11329:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,E/SQLiteLog(12383): (284) automatic index on shooting_modes(title_id)
,D/KnoxTimeoutHandler( 3523): handleActiveUserChange for user 0
,D/TaskPersister( 3523): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3523): removeObsoleteFile: deleting file=24_task.xml
,D/DocsApplication(12368): Installing DEX configuration.
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/StatusBar( 3693): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/Zygote  (12419): MountEmulatedStorage()
E/Zygote  (12419): v2
I/libpersona(12419): KNOX_SDCARD checking this for 10190
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/libpersona(12419): KNOX_SDCARD not a persona
,I/SELinux (12419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
I/SELinux (12419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/PersonaManager( 3693): isKioskContainerExistOnDevice
E/SELinux (12419): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
,D/PackageManager( 3523): findPreferredActivity: No PreferredActivities set
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12419 uid=10190 gids={50190, 9997} abi=armeabi-v7a
D/TimaKeyStoreProvider(12400): TimaSignature is unavailable
,D/ActivityThread(12400): Added TimaKeyStore provider
,D/DexInstaller(12368): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12368): Provided clientMode=RELEASE, packageInfo=PackageInfo{2f4408eb com.google.android.apps.docs}
,D/TAG     (12368): onCreate()
,D/TimaKeyStoreProvider(12419): TimaSignature is unavailable
,D/ActivityThread(12419): Added TimaKeyStore provider
I/ActivityManager( 3523): Killing 10649:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/CrossAppStateProvider(12368): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager(12400): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/PanelView( 3693): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ResourcesManager(12419): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/BatteryService( 3523): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3523): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3523): online:4, current avg:-216, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-204
D/BatteryService( 3523): stay LED for fully charged
,D/BatteryService( 3523): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3523): Plugged
,D/NearbySource(12353): Nearby Source Create!
I/MotionRecognitionService( 3523): setPowerConnected  = true
D/NearbyContext(12353): Nearby Context Create!
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12419): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12419): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5617): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
I/TapandpayWidget:Utils(12419): Clear T&P info.
D/HeadsetStateMachine( 5617): Disconnected process message: 10
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12400): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12400): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12400): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3523): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3523): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/TapandpayWidget:TanpandpayAppWidgetProvider(12419): Widget is not attached.
D/UsbHostManager( 3523): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3523): displayNotification : [0ah,00h,01h]
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/UsbHostManager( 3523): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3523): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3523): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/Zygote  (12441): MountEmulatedStorage()
E/Zygote  (12441): v2
I/libpersona(12441): KNOX_SDCARD checking this for 10022
I/libpersona(12441): KNOX_SDCARD not a persona
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,I/SELinux (12441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ContextImpl(12353): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12353): Samsung link source created
,I/ActivityManager( 3523): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12441 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Killing 11476:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/ActivityManager( 3523): Killing 12161:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,E/SQLiteLog(12353): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/TimaKeyStoreProvider(12441): TimaSignature is unavailable
,D/ActivityThread(12441): Added TimaKeyStore provider
,E/SQLiteDatabase(12353): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12353): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12353): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12353): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12353): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12353): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12353): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12353): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12353): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12353): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12353): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12353): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12353): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12353): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12353): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12353): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12353): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12353): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12353): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12353): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12353): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12353): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12353): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12353): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12353): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12353): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12353): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12353): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12353): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12353): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12353): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12353): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12353): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12353): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12353): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12353): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12353): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12353): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12353): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12353): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12353): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12353): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/UsbHostManager( 3523): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3523): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
W/SQLiteOpenHelper(12353): Opened local.db in read-only mode
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/EventHub( 3523): Removing device '/dev/input/event10' due to inotify event
,D/PackageBroadcastService( 6725): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6725): Clearing selected account for com.test.thalitest
,I/EventHub( 3523): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(12441): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,I/EventHub( 3523): Removing device '/dev/input/event8' due to inotify event
,I/PCWCLIENTTRACE_SYSTEMReceiver(11802): mConnectivityHandler : connected
,D/ContactProvider(12353): getAllContactInfoList Start
D/WifiDisplayAdapter( 3523): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager(12441): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 6725): Removing dialog suppression flag for package com.test.thalitest
,I/EventHub( 3523): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteLog( 6725): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6725): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 6725): disk I/O error (code 3850)
E/DriveAsyncService( 6725): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6725): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6725): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6725): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6725): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6725): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6725): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6725): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6725): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6725): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6725): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6725): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6725): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6725): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6725): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6725): 	at java.lang.Thread.run(Thread.java:818)
,D/ChimeraCfgMgr( 6725): Loading module com.google.android.gms.games from APK com.google.android.play.games
,E/SQLiteLog( 6725): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
D/ChimeraModuleLdr( 6725): Module APK com.google.android.play.games already loaded
,W/PCWCLIENTTRACE_AccountUtil(11802): [hasSamungAccount] - No Samsung Account
,I/EventHub( 3523): Removing device '/dev/input/event11' due to inotify event
,E/SQLiteDatabase( 6725): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6725): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6725): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6725): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6725): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6725): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6725): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6725): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6725): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6725): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6725): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6725): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6725): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6725): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6725): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6725): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6725): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/LocationWidgetApplication(12441): onCreate() : start
,D/LocationWidgetApplication(12441): countryCode = POLAND
W/SQLiteOpenHelper( 6725): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 6725): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 6725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 6725): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6725): Process: com.google.android.gms, PID: 6725
E/AndroidRuntime( 6725): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6725): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6725): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6725): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6725): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6725): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6725): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6725): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6725): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6725): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6725): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3523): Removing device '/dev/input/event12' due to inotify event
,D/MtpClient(12353): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(12353): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/SharedPreferencesImpl(12353): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/ChimeraCfgMgr( 6725): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6725): Module APK com.google.android.play.games already loaded
,I/EventHub( 3523): Removing device '/dev/input/event13' due to inotify event
,E/SQLiteLog( 6725): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6725): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 6725): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6725): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
I/Process ( 6725): Sending signal. PID: 6725 SIG: 9
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/art     ( 4621): Explicit concurrent mark sweep GC freed 85073(4MB) AllocSpace objects, 33(1463KB) LOS objects, 34% free, 30MB/46MB, paused 2.178ms total 137.202ms
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3523): Removing device '/dev/input/event14' due to inotify event
,E/ActivityManager( 3523): checkUser: useridlist=null, currentuser=0
,I/CSTORAGE(11802): ================================================
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
I/CSTORAGE(11802):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11802): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11802): [GetString-S]
E/art     (11802): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11802): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11802): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11802): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11802): sales region : global
I/PCWCLIENTTRACE_PushUtil(11802): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11802): [ensureRegistration] - No Samsung account
,E/Zygote  (12469): MountEmulatedStorage()
I/libpersona(12469): KNOX_SDCARD checking this for 10052
E/Zygote  (12469): v2
I/libpersona(12469): KNOX_SDCARD not a persona
,I/SELinux (12469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12469): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3523): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12469 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/LocationManagerService( 3523): getProviders()=[]
D/LocationManagerService( 3523): getProviders()=[passive]
D/LocationManagerService( 3523): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
E/JavaBinder( 3523): !!! FAILED BINDER TRANSACTION !!!
,D/LWLocationManager(12441): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12441): getLastUiLocationId() : mLastUiLocationId = -100
W/ActivityManager( 3523): Failure sending service ComponentInfo{com.google.android.gms/com.google.android.location.util.PreferenceService} to connection android.os.BinderProxy@1f4f4a4b (in com.google.android.gms)
W/ActivityManager( 3523): android.os.TransactionTooLargeException
W/ActivityManager( 3523): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3523): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3523): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager( 3523): 	at com.android.server.am.ActiveServices.publishServiceLocked(ActiveServices.java:918)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.publishService(ActivityManagerService.java:18251)
W/ActivityManager( 3523): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:993)
W/ActivityManager( 3523): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3523): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteLog(12441): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,D/ConnectivityService( 3523): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2ab90d1f)
,E/SQLiteDatabase(12441): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12441): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12441): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12441): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12441): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12441): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12441): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12441): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12441): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12441): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12441): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12441): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12441): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12441): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12441): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12441): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12441): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12441): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12441): Shutting down VM
,D/ConnectivityService( 3523): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/AndroidRuntime(12441): FATAL EXCEPTION: main
E/AndroidRuntime(12441): Process: com.sec.android.widgetapp.locationwidget, PID: 12441
E/AndroidRuntime(12441): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12441): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12441): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12441): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12441): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12441): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12441): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12441): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12441): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12441): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12441): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12441): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12441): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12441): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12441): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12441): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12441): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12441): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12441): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12441): 	... 9 more
,E/ConnectivityService( 3523): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/ApplicationPolicy( 3523): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
I/ActivityManager( 3523): Process com.google.android.gms (pid 6725)(adj 0) has died(260,1207)
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,E/SQLiteLog( 4621): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4621): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10993ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10992ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20992ms
W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30991ms
,W/ActivityManager( 3523): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30991ms
,D/AndroidRuntime( 4621): Shutting down VM
,E/AndroidRuntime( 4621): FATAL EXCEPTION: main
E/AndroidRuntime( 4621): Process: com.google.android.gms.persistent, PID: 4621
E/AndroidRuntime( 4621): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4621): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4621): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4621): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4621): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4621): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4621): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4621): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4621): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4621): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4621): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4621): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4621): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4621): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4621): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4621): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4621): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4621): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4621): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4621): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4621): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4621): 	... 9 more

```
