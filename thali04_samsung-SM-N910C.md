#### Test 5198634075bb434_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/SSRM:n  ( 3510): SIOP:: AP = 260, PST = 273, CUR = 43
I/PowerManagerService( 3510): [PWL] Off : 50s ago
D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
D/BatteryService( 3510): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11837): 
D/AndroidRuntime(11837): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11837): CheckJNI is OFF
D/AndroidRuntime(11837): readGMSProperty: start
D/AndroidRuntime(11837): readGMSProperty: already setted!!
D/AndroidRuntime(11837): readGMSProperty: end
D/AndroidRuntime(11837): addProductProperty: start
E/AffinityControl(11837): AffinityControl: registerfunction enter
D/AndroidRuntime(11837): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3510): inState():  stateMachine is null !!
I/PersonaManagerService( 3510): PersonaId don't exist
I/ActivityManager( 3510): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3510): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3510): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3510): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3510): mDVFSHelper.acquire()
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/Zygote  (11856): MountEmulatedStorage()
I/libpersona(11856): KNOX_SDCARD checking this for 10443
E/Zygote  (11856): v2
I/libpersona(11856): KNOX_SDCARD not a persona
I/SELinux (11856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3510): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11856 uid=10443 gids={50443, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11837): Shutting down VM
E/SELinux (11856): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3510): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3510): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3510): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3510): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11856): TimaSignature is unavailable
D/ActivityThread(11856): Added TimaKeyStore provider
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (5/8)
D/ResourcesManager(11856): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6406): updateVisibility : ActivityRecord{1d594a48 token=android.os.BinderProxy@61a5fe5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11856): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11856): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11856): Loading: webviewchromium
I/LibraryLoader(11856): Time to load native libraries: 3 ms (timestamps 5026-5029)
I/LibraryLoader(11856): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11856): Binding Chromium to main looper Looper (main, tid 1) {f560fbb}
I/LibraryLoader(11856): Expected native library version number "",actual native library version number ""
I/chromium(11856): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11856): Initializing chromium process, renderers=0
,W/art     (11856): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11856): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11856): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11856): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11856): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11856): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11856): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11856): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11856): CordovaWebView is running on device made by: samsung
,W/art     (11856): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11856): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11856): performCreate Call secproduct feature valuefalse
D/Activity(11856): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11856): Render dirty regions requested: true
,D/ActivityManager( 3510): post active user change for 0
D/KnoxTimeoutHandler( 3510): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3510): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2852): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3510): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3510): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3510): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3510): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3510): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3510): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11856): Initialized EGL, version 1.4
I/OpenGLRenderer(11856): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1278742256 
,D/OpenGLRenderer(11856): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11856): Enabling debug mode 0
,D/mali_winsys(11856): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11856): updateVisibility : ActivityRecord{3a65dab token=android.os.BinderProxy@3371823e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3510): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3510): mDVFSHelper.release()
I/Timeline( 3510): Timeline: Activity_windows_visible id: ActivityRecord{32309a2d u0 com.test.thalitest/.MainActivity t26} time:145383
,I/art     ( 3510): Explicit concurrent mark sweep GC freed 40434(2MB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 49MB/65MB, paused 2.031ms total 121.422ms
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(11856): showStatusIcon on inactive InputConnection
,I/Timeline(11856): Timeline: Activity_idle id: android.os.BinderProxy@3371823e time:145509
,D/JsMessageQueue(11856): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11856): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11856): 
,D/jxcore_app_log(11856): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259353344
D/JX-Cordova(11856): jxcore cordova android initializing
,W/jxcore-log(11856): Initializing JXcore engine
W/jxcore-log(11856): JXcore engine is ready
,W/jxcore-log(11856): Starting JXcore engine
,E/auditd  ( 4599): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3510): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3510): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11856): Platform android
W/jxcore-log(11856): 
W/jxcore-log(11856): Process ARCH arm
W/jxcore-log(11856): 
,I/jxcore-log(11856): JXcore Cordova bridge is ready!
I/jxcore-log(11856): 
W/jxcore-log(11856): JXcore engine is started
,I/jxcore-log(11856): Toggling radios to true
I/jxcore-log(11856): 
,D/BluetoothAdapter(11856): enable()
D/BluetoothAdapter(11856): enable(): BT is already enabled..!
,D/WifiService( 3510): New client listening to asynchronous messages
,I/WifiManager(11856): packageName : com.test.thalitest
,D/SecContentProvider( 3510): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3510): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3510): mCursor = null
,D/WifiService( 3510): setWifiEnabled: true pid=11856, uid=10443
E/WifiService( 3510): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3510): Permission Denial: getCurrentUser() from pid=11856, uid=10443 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3510): Failed getting userId using ActivityManagerNative
W/WifiService( 3510): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11856, uid=10443 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3510): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3510): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3510): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3510): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3510): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3510): name = wifi_on
,I/WifiService( 3510): disconnect: pid=11856, uid=10443
,I/wpa_supplicant( 3834): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11856): Radios toggled
I/jxcore-log(11856): 
,I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3510): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): Disconnected - do not scan
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3510): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3510): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3510): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3510): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3510): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3510): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3510): do suspend true
,D/WifiP2pService( 3510): InactiveState{ what=143375 }
,D/WifiP2pService( 3510): P2pEnabledState{ what=143375 }
,D/CommandListener( 2847): Clearing all IP addresses on wlan0
,V/NativeCrypto( 4167): Read error: ssl=0x99610e00: I/O error during system call, Connection timed out
,E/WifiStateMachine( 3510): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3510): updateNetworkInfo()
D/ConnectivityService( 3510): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3510): updateNetworkInfo()
D/ConnectivityService( 3510): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,V/NativeCrypto( 4167): SSL shutdown failed: ssl=0x99610e00: I/O error during system call, Broken pipe
,I/WifiTrafficPoller( 3510): evaluateTrafficStatsPolling
,E/WifiConfigStore( 3510): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
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
,D/ConnectivityService( 3510): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): ValidatedState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): DefaultState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out( 3510): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3510): Tagging socket 420 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3510, getuid(): 1000
,I/System.out( 3510): (HTTPLog)-Static: isSBSettingEnabled false
,D/NearbySettings( 8947): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8947): MountReceiver.onReceive - Start HandlerThread
,I/Hs20UtilService( 4104): Starting #8
,I/Hs20UtilService( 4104): Message received 5007
,D/NearbySettings( 8947): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8947): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8947): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3510): New client listening to asynchronous messages
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8947): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8947): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11491): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3510): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3834): First Scan Start
,E/WifiStateMachine( 3510): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3510): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3510): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3510): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3510): do suspend true
,D/WifiP2pService( 3510): InactiveState{ what=143375 }
D/WifiP2pService( 3510): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener( 2847): Clearing all IP addresses on wlan0
D/ConnectivityService( 3510): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 3510): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Validated
D/EntConnectivity( 3510): Not allowed due to - mEnabled false
,D/WifiStateMachine( 3510): updateConfiguredNetworkExpiration - currTime: 1449063234430
D/WifiStateMachine( 3510): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524292
E/WifiStateMachine( 3510): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3510): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 3510): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller( 3510): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 3980): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3510): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3510): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityManager.CallbackHandler( 7002): CM callback handler got msg 524292
,E/WifiStateMachine( 3510): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3510): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/CSLegacyTypeTracker( 3510): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3510): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,E/WifiStateMachine( 3510): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3510): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3510): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3510): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine( 3510): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3510): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3510): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3510): mCursor = null
,D/Tethering( 3510): MasterInitialState.processMessage what=3
D/EntConnectivity( 3510): Not allowed due to - mEnabled false
,D/SmartBondingService( 3510): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
V/NetworkStats( 3510): updateIfacesLocked()
V/NetworkStats( 3510): performPollLocked(flags=0x1)
D/SmartBondingService( 3510): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3510): UpdateStatsForKnox
D/ConnectivityService( 3510): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SmartBondingService( 3510): getNetworkEnabled : wifi : true mobile : false
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
V/NetworkStats( 3510): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
,V/NetworkStats( 3510): performPollLocked() took 6ms
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
,I/Hs20UtilService( 4104): Starting #9
,D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
I/Hs20UtilService( 4104): Message received 5007
D/SecContentProvider2( 3510): mCursor = null
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
,D/NearbySettings( 8947): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8947): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8947): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8947): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11491): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3980): FileWriteThread : threadType = 3
,D/ConnectivityService( 3510): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3510): updateDataUsageMap
I/ApplicationPolicy( 3510): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3510): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3510): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3510): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3510): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3510): No Active Data Connection
,I/DBG_DM  ( 6406): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6406): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11957): MountEmulatedStorage()
E/Zygote  (11957): v2
I/libpersona(11957): KNOX_SDCARD checking this for 10114
I/libpersona(11957): KNOX_SDCARD not a persona
,I/SELinux (11957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3510): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11957 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11957): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11957): TimaSignature is unavailable
,D/ActivityThread(11957): Added TimaKeyStore provider
,D/ResourcesManager(11957): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/ResourcesManager(11957): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (11957): Thread[1,tid=11957,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
,W/art     (11957): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/StaticBindingVerifier(11957): Verify
,W/LightSharedPreferencesImpl(11957): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11957): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11957): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11957): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11957): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(upload_queue:56)
W/LightSharedPreferencesImpl(11957): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(upload_system_version:61)
W/LightSharedPreferencesImpl(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11957): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_logging_level:77)
W/LightSharedPreferencesImpl(11957): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_spec_display:327)
W/LightSharedPreferencesImpl(11957): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11957): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11957): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_state:42)
W/LightSharedPreferencesImpl(11957): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11957): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11957): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11957): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11957): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11957): 	... 10 more
,D/WifiService( 3510): New client listening to asynchronous messages
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ApplicationOnCreate (null); Monotonic Timestamp (ms): 148207; Elapsed: 178 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ApplicationOnCreate (null); Monotonic Timestamp (ms): 148207; Elapsed: 178 ms
,W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/FBAppImpl.onCreate (null); Monotonic Timestamp (ms): 148029; Elapsed: 77 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/FBAppImpl.onCreate (null); Monotonic Timestamp (ms): 148029; Elapsed: 77 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/FBApp.onBaseContextAttached (null); Monotonic Timestamp (ms): 147988; Elapsed: 35 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/FBApp.onBaseContextAttached (null); Monotonic Timestamp (ms): 147988; Elapsed: 35 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker CatchMeIfYouCan_Setup (null); Monotonic Timestamp (ms): 147954; Elapsed: 0 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker CatchMeIfYouCan_Setup (null); Monotonic Timestamp (ms): 147954; Elapsed: 0 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ACRA_Setup (null); Monotonic Timestamp (ms): 147965; Elapsed: 10 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ACRA_Setup (null); Monotonic Timestamp (ms): 147965; Elapsed: 10 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker FacebookApplication#getAppType (null); Monotonic Timestamp (ms): 147959; Elapsed: 4 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker FacebookApplication#getAppType (null); Monotonic Timestamp (ms): 147959; Elapsed: 4 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker BreakpadManager_Setup (null); Monotonic Timestamp (ms): 147987; Elapsed: 16 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker BreakpadManager_Setup (null); Monotonic Timestamp (ms): 147987; Elapsed: 16 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/FBApp.createDelegate (null); Monotonic Timestamp (ms): 148004; Elapsed: 16 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/FBApp.createDelegate (null); Monotonic Timestamp (ms): 148004; Elapsed: 16 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/EnsureDexsLoaded (null); Monotonic Timestamp (ms): 148002; Elapsed: 13 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/EnsureDexsLoaded (null); Monotonic Timestamp (ms): 148002; Elapsed: 13 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker DLL_checkstate (null); Monotonic Timestamp (ms): 147992; Elapsed: 1 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker DLL_checkstate (null); Monotonic Timestamp (ms): 147992; Elapsed: 1 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/ReplaceLinearAllocBuffer (null); Monotonic Timestamp (ms): 148002; Elapsed: 0 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/ReplaceLinearAllocBuffer (null); Monotonic Timestamp (ms): 148002; Elapsed: 0 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/FallbackReplaceLinearAllocBuffer (null); Monotonic Timestamp (ms): 148004; Elapsed: 2 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/FallbackReplaceLinearAllocBuffer (null); Monotonic Timestamp (ms): 148004; Elapsed: 2 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/FBInjector.create (null); Monotonic Timestamp (ms): 148065; Elapsed: 20 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/FBInjector.create (null); Monotonic Timestamp (ms): 148065; Elapsed: 20 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/FBInjector.inject (null); Monotonic Timestamp (ms): 148132; Elapsed: 67 ms
,W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/FBInjector.inject (null); Monotonic Timestamp (ms): 148132; Elapsed: 67 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/AppInitialization (null); Monotonic Timestamp (ms): 148209; Elapsed: 76 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/AppInitialization (null); Monotonic Timestamp (ms): 148209; Elapsed: 76 ms
W/fb4a(:<default>):NNFColdStart(11957): Stopped Marker ColdStart/UIThreadBlockedOnAppInit (null); Monotonic Timestamp (ms): 148207; Elapsed: 22 ms
W/fb4a(:<default>):NNFColdStartFirstRun(11957): Stopped Marker ColdStart/UIThreadBlockedOnAppInit (null); Monotonic Timestamp (ms): 148207; Elapsed: 22 ms
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12001): MountEmulatedStorage()
I/libpersona(12001): KNOX_SDCARD checking this for 1000
E/Zygote  (12001): v2
I/libpersona(12001): KNOX_SDCARD not a persona
,I/SELinux (12001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3510): Killing 11194:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12001): TimaSignature is unavailable
,D/ActivityThread(12001): Added TimaKeyStore provider
,D/ResourcesManager(12001): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12001): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12001): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12001): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12001): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12001): sales region : global
I/PCWCLIENTTRACE_PushUtil(12001): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12001): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12001): noConnectivity : true
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12017): MountEmulatedStorage()
I/libpersona(12017): KNOX_SDCARD checking this for 10135
E/Zygote  (12017): v2
I/libpersona(12017): KNOX_SDCARD not a persona
,I/SELinux (12017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12017): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12017 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3510): Killing 10414:com.sec.android.gallery3d/u0a50 (adj 15): bgCount ##31
,E/lowmemorykiller( 2830): Error writing /proc/10414/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12017): TimaSignature is unavailable
,D/ActivityThread(12017): Added TimaKeyStore provider
,D/ResourcesManager(12017): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/wpa_supplicant( 3834): nl80211: Received scan results (11 BSSes)
,I/wpa_supplicant( 3834): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3834): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2462 MHz)
I/wpa_supplicant( 3834): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3510): [1,449,063,235,489 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3510): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@e060db9 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3510): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3510): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3510): setDetailed state send new extra info
,D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3510): mCursor = null
,I/MusicStore(12017): Database version: 104
,D/ResourcesManager(12017): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(12017): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12017): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12017): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread(12017): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12017): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21366c5f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12017): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12017): GMSCore installation verified
,I/ConfigStore(12017): Config Database version: 1
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3510): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3510): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3510): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3834): Associated with C0.AA.48
,D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3510): mCursor = null
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3510): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3510): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3510): getStreamVolume 3 index 0
,I/jxcore-log(11856): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11856): 
,I/jxcore-log(11856): my name is : samsung-SM-N910C_PT8958
I/jxcore-log(11856): 
I/MediaRouter(12017): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/wpa_supplicant( 3834): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3510): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3510): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3510): mCursor = null
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12042): MountEmulatedStorage()
I/libpersona(12042): KNOX_SDCARD checking this for 10002
E/Zygote  (12042): v2
I/libpersona(12042): KNOX_SDCARD not a persona
,I/SELinux (12042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12042): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12042 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3510): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/jxcore-log(11856): attempting to connect to test coordinator
I/jxcore-log(11856): 
I/jxcore-log(11856): check test folder
I/jxcore-log(11856): 
I/art     ( 2879): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 700us total 10.756ms
I/jxcore-log(11856): found test : ./testFindPeers.js
I/jxcore-log(11856): 
,I/NetworkMonitor(12017): type=WIFI subType= reason=null isConnected=false
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 277us total 8.566ms
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3834): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/jxcore-log(11856): found test : ./testReConnect.js
I/jxcore-log(11856): 
E/WifiStateMachine( 3510): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3510): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/TimaKeyStoreProvider(12042): TimaSignature is unavailable
I/wpa_supplicant( 3834): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/ActivityThread(12042): Added TimaKeyStore provider
,I/wpa_supplicant( 3834): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/ActivityManager( 3510): Killing 11233:com.android.mms/u0a52 (adj 15): bgCount ##31
I/wpa_supplicant( 3834): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3834): Blacklist: Clear (temp) 
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 370us total 9.013ms
,E/lowmemorykiller( 2830): Error writing /proc/11233/oom_score_adj; errno=22
,E/WifiStateMachine( 3510): Network connection established
,D/WifiNative-HAL( 3510): callSECApiVoid - ID [50]
E/WifiStateMachine( 3510): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3510): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3510): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3510): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3510): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3510): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log(11856): found test : ./testSendData.js
I/jxcore-log(11856): 
D/ConnectivityService( 3510): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3510): updateNetworkInfo()
D/ConnectivityService( 3510): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ResourcesManager(12042): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3510): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3510): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3510): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3510): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2847): Setting iface cfg
,E/WifiStateMachine( 3510): Start Dhcp Watchdog 2
D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3510): mCursor = null
,E/WifiStateMachine( 3510): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3510): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/jxcore-log(11856): Test app app.js loaded
I/jxcore-log(11856): 
,I/ActivityManager( 3510): Killing 11257:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/lowmemorykiller( 2830): Error writing /proc/11257/oom_score_adj; errno=22
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/Choreographer(11856): Skipped 98 frames!  The application may be doing too much work on its main thread.
,E/Zygote  (12062): MountEmulatedStorage()
I/libpersona(12062): KNOX_SDCARD checking this for 1000
E/Zygote  (12062): v2
I/libpersona(12062): KNOX_SDCARD not a persona
,I/SELinux (12062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/chromium(11856): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SELinux (12062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12062 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/chromium(11856): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/CountryDetector( 3510): No listener is left
,D/TimaKeyStoreProvider(12062): TimaSignature is unavailable
,D/ActivityThread(12062): Added TimaKeyStore provider
,D/ResourcesManager(12062): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(12062): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3510): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3510): do suspend false
,D/SecContentProvider2( 3510): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3510): mCursor = null
D/WifiP2pService( 3510): InactiveState{ what=143375 }
D/WifiP2pService( 3510): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT(12062): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12062): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12062): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12062): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12078): MountEmulatedStorage()
E/Zygote  (12078): v2
I/libpersona(12078): KNOX_SDCARD checking this for 10012
I/libpersona(12078): KNOX_SDCARD not a persona
,I/SELinux (12078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12078): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12078 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12078): TimaSignature is unavailable
,D/ActivityThread(12078): Added TimaKeyStore provider
,D/ResourcesManager(12078): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3510): Killing 11274:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,I/FOTA_Client(12078): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12078): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12078): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12094): MountEmulatedStorage()
E/Zygote  (12094): v2
I/libpersona(12094): KNOX_SDCARD checking this for 10021
I/libpersona(12094): KNOX_SDCARD not a persona
,I/SELinux (12094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12094 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3510): Killing 11289:com.wsomacp/u0a28 (adj 15): bgCount ##31
,E/lowmemorykiller( 2830): Error writing /proc/11289/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12094): TimaSignature is unavailable
,D/ActivityThread(12094): Added TimaKeyStore provider
,D/ResourcesManager(12094): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12094): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 14:33:56 GMT+01:00 2015
,I/KLMS-2.4.521: (12094): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12094): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12094): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12094): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12094): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12094): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/dhcpcd  (12110): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/KLMS-2.4.521: (12094): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/dhcpcd  (12110): version 5.5.6 starting
,I/KLMS-2.4.521: (12094): StateImplV2(): networkChangeListener().END
,E/dhcpcd  (12110): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  (12111): MountEmulatedStorage()
I/libpersona(12111): KNOX_SDCARD checking this for 10038
E/Zygote  (12111): v2
I/libpersona(12111): KNOX_SDCARD not a persona
I/SELinux (12111): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12111): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12111): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12111 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12094): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3510): Killing 11306:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12111): TimaSignature is unavailable
,D/ActivityThread(12111): Added TimaKeyStore provider
,D/ResourcesManager(12111): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/dhcpcd  (12110): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12110): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12110): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12110): bssid match
I/dhcpcd  (12110): wlan0: rebinding lease of 192.168.1.113
,I/SO_AGENT(12111): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12132): MountEmulatedStorage()
E/Zygote  (12132): v2
I/libpersona(12132): KNOX_SDCARD checking this for 1000
I/libpersona(12132): KNOX_SDCARD not a persona
,I/SELinux (12132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12132): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/lowmemorykiller( 2830): Error writing /proc/11326/oom_score_adj; errno=22
I/ActivityManager( 3510): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3510): Killing 11326:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12132): TimaSignature is unavailable
,D/ActivityThread(12132): Added TimaKeyStore provider
,D/ResourcesManager(12132): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12152): MountEmulatedStorage()
I/libpersona(12152): KNOX_SDCARD checking this for 10039
E/Zygote  (12152): v2
I/libpersona(12152): KNOX_SDCARD not a persona
I/SELinux (12152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3510): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12152 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12152): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Killing 10927:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
E/lowmemorykiller( 2830): Error writing /proc/10927/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12152): TimaSignature is unavailable
,D/ActivityThread(12152): Added TimaKeyStore provider
,D/ResourcesManager(12152): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12152): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12152): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12152): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,D/SPPClientService(12152): PushLog.txt file is not deleted.
D/SPPClientService(12152): PushLog.txt file is not deleted.
D/SPPClientService(12152): ============PushLog. stop!
,E/Zygote  (12169): MountEmulatedStorage()
E/Zygote  (12169): v2
I/libpersona(12169): KNOX_SDCARD checking this for 10045
I/libpersona(12169): KNOX_SDCARD not a persona
,I/SELinux (12169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3510): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12169 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12169): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Killing 11361:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/SPPClientService(12152): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider(12169): TimaSignature is unavailable
,D/ActivityThread(12169): Added TimaKeyStore provider
,D/ResourcesManager(12169): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/SA      (12169): [SSP] onCreated
,I/SA      (12169): [TPM] There is no property file
,I/SA      (12169): [SCU] isHaveSA() - false
,I/SA      (12169): [TPM] getModelProperty : null
I/SA      (12169): [TPM] getCSCProperty : null
,I/SA      (12169): [DM] init START
,I/SA      (12169): [DM] This device is not a Vodafone
,I/SA      (12169): checkReactivationActive for LOLLIPOP
,I/SA      (12169): checkReactivationActive for reactiveActive
I/SA      (12169): setSupportRL : true
I/SA      (12169): [SCU] isHaveSA() - false
I/SA      (12169): support phone number id : false
,I/SA      (12169): [DM] init END
I/SA      (12169): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12169): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12169): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12169): [SLFUCHKMGR] constructor called
,I/SA      (12169): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12169): [OR] == isSIMCardReady false ==
,I/SA      (12169): [SCU] == networkStateCheck == false
I/SA      (12169): [OR] onReceive END
,I/ActivityManager( 3510): Killing 11342:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12190): MountEmulatedStorage()
E/Zygote  (12190): v2
I/libpersona(12190): KNOX_SDCARD checking this for 10067
I/libpersona(12190): KNOX_SDCARD not a persona
,I/SELinux (12190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12190 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12190): TimaSignature is unavailable
,D/ActivityThread(12190): Added TimaKeyStore provider
,D/ResourcesManager(12190): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12190): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12190): Other Intent
,I/ActivityManager( 3510): Killing 11408:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/accuweather( 5101): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5101): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5101): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5101): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5101): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5101): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5101): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12206): MountEmulatedStorage()
E/Zygote  (12206): v2
I/libpersona(12206): KNOX_SDCARD checking this for 1000
I/libpersona(12206): KNOX_SDCARD not a persona
,I/SELinux (12206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12206): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12206 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12206): TimaSignature is unavailable
,D/ActivityThread(12206): Added TimaKeyStore provider
,D/ResourcesManager(12206): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12206): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12206): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12206): premStatus:2
,I/KnoxUsageLogPro(12206): isEulaShown : false
I/KnoxUsageLogPro(12206): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12221): MountEmulatedStorage()
E/Zygote  (12221): v2
I/libpersona(12221): KNOX_SDCARD checking this for 10090
I/libpersona(12221): KNOX_SDCARD not a persona
,I/SELinux (12221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12221): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12221 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3510): Killing 11426:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12221): TimaSignature is unavailable
,D/ActivityThread(12221): Added TimaKeyStore provider
,D/ResourcesManager(12221): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12237): MountEmulatedStorage()
E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD checking this for 10127
I/libpersona(12237): KNOX_SDCARD not a persona
,I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3510): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12237 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Killing 11442:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8746(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 472us total 10.602ms
,D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
,D/ActivityThread(12237): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 539us total 8.903ms
,D/ResourcesManager(12237): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 251us total 8.049ms
,D/KeyguardWallpaperUpdator(12237): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12237): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12237): stopCheckCategoryVersion
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12254): MountEmulatedStorage()
E/Zygote  (12254): v2
I/libpersona(12254): KNOX_SDCARD checking this for 10136
I/libpersona(12254): KNOX_SDCARD not a persona
,I/SELinux (12254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3510): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12254 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12254): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Killing 11458:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12254): TimaSignature is unavailable
,D/ActivityThread(12254): Added TimaKeyStore provider
,D/ResourcesManager(12254): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12254): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12254): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12254): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12254): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12254): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12254): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12254): Loading: webviewchromium
,I/LibraryLoader(12254): Time to load native libraries: 3 ms (timestamps 9577-9580)
,I/LibraryLoader(12254): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12254): Binding Chromium to main looper Looper (main, tid 1) {26ff6f7b}
,I/LibraryLoader(12254): Expected native library version number "",actual native library version number ""
,I/chromium(12254): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12254): Initializing chromium process, renderers=0
,W/art     (12254): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12254): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid(12254): Requires BLUETOOTH permission
,I/chromium(12254): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12254): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12254): Starting up...
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12322): MountEmulatedStorage()
E/Zygote  (12322): v2
I/libpersona(12322): KNOX_SDCARD checking this for 10150
I/libpersona(12322): KNOX_SDCARD not a persona
,I/SELinux (12322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12322 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3510): Killing 11510:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12322): TimaSignature is unavailable
,D/ActivityThread(12322): Added TimaKeyStore provider
,D/ResourcesManager(12322): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12322): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12322): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12322): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12322): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12322): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12322): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12338): MountEmulatedStorage()
E/Zygote  (12338): v2
I/libpersona(12338): KNOX_SDCARD checking this for 10178
I/libpersona(12338): KNOX_SDCARD not a persona
,I/SELinux (12338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3510): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12338 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (12338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Killing 11527:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12338): TimaSignature is unavailable
,D/ActivityThread(12338): Added TimaKeyStore provider
,D/ResourcesManager(12338): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12338): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12338): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12338): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12338): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12338): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12338): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3510): exchangeData() failure , invalid userId
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12361): MountEmulatedStorage()
E/Zygote  (12361): v2
I/libpersona(12361): KNOX_SDCARD checking this for 10082
I/libpersona(12361): KNOX_SDCARD not a persona
,I/SELinux (12361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12361): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3510): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12361 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12361): TimaSignature is unavailable
,D/ActivityThread(12361): Added TimaKeyStore provider
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12361): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12361): onCreate
D/BadgeProvider(12361): DatabaseHelper
,E/Zygote  (12377): MountEmulatedStorage()
I/libpersona(12377): KNOX_SDCARD checking this for 1000
E/Zygote  (12377): v2
I/libpersona(12377): KNOX_SDCARD not a persona
,I/SELinux (12377): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12377): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12377): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12377 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3510): Killing 11561:com.facebook.system/u0a10 (adj 13): bgCount ##31
,I/ActivityManager( 3510): Killing 11545:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##32
,D/TimaKeyStoreProvider(12377): TimaSignature is unavailable
,D/ActivityThread(12377): Added TimaKeyStore provider
,D/ResourcesManager(12377): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3510): Killing 11603:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,E/JavaBinder( 3510): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3510): Exception when sending broadcast to ComponentInfo{com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.networkstatereceiver.NetworkStateReceiver}
W/BroadcastQueue( 3510): android.os.TransactionTooLargeException
W/BroadcastQueue( 3510): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3510): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3510): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3510): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3510): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3510): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3510): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3510): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3510): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12395): MountEmulatedStorage()
I/libpersona(12395): KNOX_SDCARD checking this for 10013
E/Zygote  (12395): v2
I/libpersona(12395): KNOX_SDCARD not a persona
I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
I/SELinux (12395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3510): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12395 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12395): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 3510): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider(12395): TimaSignature is unavailable
,D/ActivityThread(12395): Added TimaKeyStore provider
I/art     ( 3510): Explicit concurrent mark sweep GC freed 56125(2MB) AllocSpace objects, 2(80KB) LOS objects, 24% free, 49MB/65MB, paused 2.465ms total 87.334ms
,D/ResourcesManager(12395): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/BadgeProvider(12361): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12361): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12361): sendNotify, [notify] : null
D/BadgeProvider(12361): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12361): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12361): update, [UpdateCount] : 1
,D/Launcher.Model( 4003): reloadBadges entered.
,I/dhcpcd  (12110): wlan0: acknowledged 192.168.1.113 from 192.168.1.1
,I/ActivityManager( 3510): Killing 11393:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,E/lowmemorykiller( 2830): Error writing /proc/11393/oom_score_adj; errno=22
,I/iu.Environment( 7002): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 7002): num queued entries: 0
,I/iu.UploadsManager( 7002): num updated entries: 0
I/iu.SyncManager( 7002): NEXT; no task
,D/ChimeraCfgMgr( 7002): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Hs20UtilService( 4104): Starting #10
I/dhcpcd  (12110): wlan0: leased 192.168.1.113 for 86400 seconds
,I/Hs20UtilService( 4104): Message received 5007
,D/NearbySettings( 8947): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8947): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8947): MountReceiver.onReceive - Set preference state off
E/WifiStateMachine( 3510): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
V/NearbySettings( 8947): MountReceiver.mPrefHandler - 7002
E/WifiStateMachine( 3510): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/SignOutReceiver(11491): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3510): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3510): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3510): do suspend true
,D/WifiP2pService( 3510): InactiveState{ what=143375 }
D/WifiP2pService( 3510): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3510): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3510): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3510): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3510): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3510): Not connected state, yet.
E/WifiStateMachine( 3510): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth,
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3510): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine( 3510): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3510): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3510): callSECApiInt - ID [210]
,E/WifiStateMachine( 3510): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3510): updateNetworkInfo()
,D/ConnectivityService( 3510): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,D/ConnectivityService( 3510): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3510): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3510): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3510): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3510): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3510): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3510): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3510): Now, connected state.
E/WifiStateMachine( 3510): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3510): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3510): evaluateTrafficStatsPolling
,D/ConnectivityService( 3510): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 3510): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 3692): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 3510): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3510): Unexpected mtu value: 0, wlan0
,V/        ( 2847): QcRouteController
I/WifiTrafficPoller( 3510): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3510): callSECApiVoid - ID [212]
E/WifiStateMachine( 3510): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 3510): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3510): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,I/Hs20UtilService( 4104): Starting #11
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
I/Hs20UtilService( 4104): Message received 5007
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/NearbySettings( 8947): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8947): MountReceiver.onReceive - Keep current state
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(11491): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 4104): Starting #12
,I/Hs20UtilService( 4104): Message received 5007
,V/        ( 2847): QcRouteController
,D/NearbySettings( 8947): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8947): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8947): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8947): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8947): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8947): MountReceiver.mPrefHandler - 7002
,V/        ( 2847): QcRouteController
,I/SignOutReceiver(11491): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2847): QcRouteController
,V/        ( 2847): QcRouteController
,I/Hs20UtilService( 4104): Starting #13
,I/Hs20UtilService( 4104): Message received 5007
,D/NearbySettings( 8947): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8947): MountReceiver.onReceive - Keep current state
,V/        ( 2847): QcRouteController
,I/WifiStateMachine( 3510): callSECApi what=220
D/WifiStateMachine( 3510): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11491): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3510): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3510): LTETest block dns file not exists
,E/ConnectivityService( 3510): updateNetworkInfo()
D/ConnectivityService( 3510): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3510): updateNetworkInfo()
D/ConnectivityService( 3510): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3510): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3510): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3510):    accepting network in place of null
,I/System.out( 3510): (HTTPLog)-Static: isSBSettingEnabled false
,D/TelephonyNetworkFactory( 3980): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 1000
,E/CSLegacyTypeTracker( 3510): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3510): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3510): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3510): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity( 3510): Not allowed due to - mEnabled false
,D/ConnectivityService( 3510): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,I/SurfaceFlinger( 2852): id=15 createSurf (1x1),1 flag=4, Uoast
,D/ConnectivityManager.CallbackHandler( 7002): CM callback handler got msg 524290
,D/Tethering( 3510): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3510): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3510): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
,V/NetworkStats( 3510): updateIfacesLocked()
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
V/NetworkStats( 3510): performPollLocked(flags=0x1)
,D/SmartBondingService( 3510): getNetworkEnabled : wifi : true mobile : false
,D/NetworkStatsFactory( 3510): UpdateStatsForKnox
,D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
V/NetworkStats( 3510): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/PowerManagerService( 3510): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3510
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
,V/NetworkStats( 3510): performPollLocked() took 6ms
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/NtpTrustedTime( 3510): currentTimeMillis() cache hit
D/mali_winsys( 3692): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3692): updateDataNetType()
D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/System.out( 3510): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 13:33:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449063238002], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449063237979]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3510): Validated
,D/ConnectivityService( 3510): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3510): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3510): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3510): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524290
,D/ConnectivityService( 3510): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 7002): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3692): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 3692): updateDataNetType()
,D/StatusBar.NetworkController( 3692): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 3692): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3692): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3692): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3510): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3510): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3510): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3510): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3510): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3510): getSBEnabled() enabled =false
,D/SmartBondingService( 3510): getSBEnabled() enabled =false
,D/SmartBondingService( 3510): getSBEnabled() enabled =false
,D/SmartBondingService( 3510): getNetworkEnabled : wifi : true mobile : false
,I/NetworkMonitor(12017): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 6406): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6406): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/GpsLocationProvider( 3510): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil(12001): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12001): sales region : global
I/PCWCLIENTTRACE_PushUtil(12001): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12001): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12062): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12062): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12078): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12078): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12078): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12094): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 14:33:58 GMT+01:00 2015
,I/KLMS-2.4.521: (12094): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12094): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12094): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12094): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12094): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12094): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12094): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(12111): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12094): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12094): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12094): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12094): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12094): KLMSIntentService(): onDestroy()
,E/SPPClientService(12152): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12169): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12169): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12169): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12169): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12169): [OR] == isSIMCardReady false ==
,I/SA      (12169): [SCU] == networkStateCheck == true
,I/SA      (12169): [DM] getCountryCodeFromCSC : PL
I/SA      (12169): isChinaCountryCode : false
I/SA      (12169): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12169): [OR] == networkStateCheck true ==
,I/SA      (12169): [OR] GetMyCountryZoneTask
I/SA      (12169): [OR] onReceive END
,I/SA      (12169): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12169): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12169): [SSP] query invoked
,I/SCloudBackupReceiver(12190): Other Intent
,I/SA      (12169): [TPMU] GetMccFromDB : null
I/SA      (12169): [SCU] getMccFromPreferece mcc = 260
I/SA      (12169): [TPM] isNoProxy(default) : true
,D/accuweather( 5101): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3781): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5101): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5101): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5101): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5101): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5101): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5101): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12206): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12206): premStatus:2
,I/KnoxUsageLogPro(12206): isEulaShown : false
I/KnoxUsageLogPro(12206): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12237): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12237): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12237): stopCheckCategoryVersion
,D/QuickConnect(12322): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12322): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12322): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,D/RCPManagerService( 3510): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate(12395): notifyNetworkActivated
,D/ConnectivityService( 3510): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ContextImpl(12395): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3510): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/hcjo    (12395): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12395): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12395): exit::IDLE
D/InitializeManagerStateMachine(12395): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12395): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12395): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12395): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12395): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12395): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12395): entry::SUCCESS
D/hcjo    (12395): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12395): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12395): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12395): exit::SUCCESS
D/InitializeManagerStateMachine(12395): entry::IDLE
,I/iu.Environment( 7002): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 7002): num queued entries: 0
,I/iu.UploadsManager( 7002): num updated entries: 0
,I/iu.SyncManager( 7002): NEXT; no task
,D/ChimeraCfgMgr( 7002): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 7002): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 4167): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4167): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10014
,V/GLSActivity( 4167): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4167): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      (12169): [RC New] Execute method=[GET] start
,I/SA      (12169): [RC New] Security=[true]
,I/System.out(12169): Thread-1695(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12169): Thread-1695(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12169): Thread-1695(ApacheHTTPLog):isShipBuild true
I/System.out(12169): Thread-1695(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10045
,W/ProcessCpuTracker( 3510): Skipping unknown process pid 12507
,I/SA      (12169): [RC New] [v2liruge] api execute + 881
I/SA      (12169): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12169): AsyncTask #1 calls detatch()
,I/SA      (12169): [TPMU] getNetworkMcc : 
,I/SA      (12169): [SCU] saveMccToPreferece Start
I/SA      (12169): [SCU] RegionMCC : 260
I/SA      (12169): [SSP] query invoked
,I/SA      (12169): [TPMU] GetMccFromDB : null
I/SA      (12169): [SCU] getMccFromPreferece mcc = 260
I/SA      (12169): [SCU] saveMccToPreferece End
,I/SA      (12169): [RC New] executeRequest [v2liruge] end. 910
I/SA      (12169): [RC New] Execute end
,I/SA      (12169): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12169): [OR] GetMyCountryZoneTask Success
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.feed.abtest.GeneratedNewsFeedCacheSyncExperiment@32fcd4b6 occurred when no user was logged in
,V/AlarmManager( 3510): waitForAlarm result :8
,W/art     (11957): Suspending all threads took: 10.557ms
,E/WifiStateMachine( 3510): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3510): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService( 3510): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2847): QcRouteController
,D/SmartBondingService( 3510): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3510): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
,D/SmartBondingService( 3510): getSBEnabled() enabled =false
D/SmartBondingService( 3510): getSBEnabled() enabled =false
,V/        ( 2847): QcRouteController
,W/NetworkManagementService( 3510): route cmd failed: 
W/NetworkManagementService( 3510): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3510): '
W/NetworkManagementService( 3510): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3510): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3510): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3510): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3510): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3510): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3510): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3510): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3510): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3510): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 7002): CM callback handler got msg 524295
D/ConnectivityService( 3510): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3692): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 7002): CM callback handler got msg 524295
,I/dhcpcd  (12110): wlan0: sending IPv6 Router Solicitation
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.common.network.GeneratedActiveNetworkOffUiThreadExperiment@39a2ecb5 occurred when no user was logged in
,W/BroadcastQueue( 3510): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{c586016 u0 ReceiverList{1f6fc131 11957 com.facebook.katana/10114/u0 remote:244fd9d8}}
,W/BroadcastQueue( 3510): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{c586016 u0 ReceiverList{1f6fc131 11957 com.facebook.katana/10114/u0 remote:244fd9d8}}
,V/MediaPlayerService( 2860): Create new media retriever from pid 11957
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.widget.tiles.annotations.ProfilePictureDiskCacheSizeExperiment@2702eefa occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.imagepipeline.abtest.GeneratedDecodeFileDescriptorExperiment@106c1cab occurred when no user was logged in
,I/jxcore-log(11856): BLE supported!!
I/jxcore-log(11856): 
,D/WearableService( 4649): callingUid 10014, callindPid: 4649
,D/ResourcesManager(12017): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(12017): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(12017): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12017): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12017): Conditions not met for autocaching.
I/MusicLeanback(12017): Stop autocaching.
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12017): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12017): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12017): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@39e65004 that was originally bound here
E/ActivityThread(12017): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@39e65004 that was originally bound here
E/ActivityThread(12017): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12017): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12017): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12017): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12017): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12017): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12017): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12017): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12017): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12017): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12017): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12017): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12017): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12017): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12017): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12017): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12017): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12017): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12017): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12017): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12017): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12017): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12017): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12017): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.messaging.abtest.GeneratedLauncherBadgeDataSourceExperiment@36d2e447 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.search.abtest.GeneratedSearchNullStateQuickExperiment@ec8b958 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.search.abtest.GeneratedSearchNullStateNearbyPlaceTipQuickExperiment@25ffeab1 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.video.abtest.VideoCacheConfigExperiment@dbc1304 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.video.abtest.VideoBufferManagerExperiment@3e889b3 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.video.abtest.VideoBufferManagerExperiment@3e889b3 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.video.abtest.VideoCacheConfigExperiment@dbc1304 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.video.abtest.VideoDirectPlayExperiment@37695b70 occurred when no user was logged in
,W/fb4a(:<default>):VideoPerformanceTracking(11957): Error reading from storage, clearing accumulated vard
W/fb4a(:<default>):VideoPerformanceTracking(11957): java.io.EOFException
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at libcore.io.Streams.readFully(Streams.java:83)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.io.DataInputStream.readInt(DataInputStream.java:103)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at com.facebook.video.analytics.VideoPerformanceTracking.a(recovery_file:402)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at com.facebook.video.analytics.VideoPerformanceTracking$2.a(recovery_file:363)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at com.facebook.video.analytics.TimedMicroStorage$1.run(replayed:87)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at com.facebook.common.executors.ConstrainedExecutorService$Worker.run(manual:178)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_logging_level:77)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_state:42)
W/fb4a(:<default>):VideoPerformanceTracking(11957): 	at java.lang.Thread.run(Thread.java:818)
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.push.mqtt.adaptive.GeneratedAdaptiveConfigurationExperiment@b2745a3 occurred when no user was logged in
,I/WifiStateMachine( 3510): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3510): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@fe691ba occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@356ee86b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.classpreloader.abtests.ClassPreloaderQuickExperiment@2f60bedf occurred when no user was logged in
,W/BroadcastQueue( 3510): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{17065f02 u0 ReceiverList{2fa3f84d 11957 com.facebook.katana/10114/u0 remote:12bc4be4}}
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.friendsharing.souvenirs.abtest.GeneratedSouvenirProductionExperiment@31f5aba8 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.NetworkPrioritizationBacktestExperiment@34cde5a7 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@3a23bdfd occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.QueueRandomDelayQuickExperiment@20e93543 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LimitLowPriorityRequestsQuickExperiment@65847c0 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.AlwaysRetryQuickExperiment@17f33cf9 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.notifications.abtest.AppBadgeHoldoutExperiment@dfe29f occurred when no user was logged in
,I/SurfaceFlinger( 2852): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2852): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3510): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3510) eventTime = 154176
,D/PowerManagerService( 3510): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3510 (0x0)
D/PowerManagerService( 3510): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3510, ws=WorkSource{10060}) (elapsedTime=3469)
,D/SSRM:n  ( 3510): SIOP:: AP = 280, PST = 273, CUR = 53
,D/BadgeProvider(12361): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(12361): sendNotify, [notify] : null
D/BadgeProvider(12361): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(12361): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12361): update, [UpdateCount] : 1
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,D/Launcher.Model( 4003): reloadBadges entered.
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.search.abtest.SearchQRCodePromoExperiment@341937c6 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.search.abtest.PostSearchQuickExperiment@6df4387 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.search.abtest.SearchQuickExperiment@3d7bfedd occurred when no user was logged in
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11957): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11957): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): error in step local_db_read
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String com.facebook.auth.viewercontext.ViewerContext.a()' on a null object reference
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.cache.GraphQLDiskCacheImpl.d(see_first_state:851)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.cache.GraphQLDiskCacheImpl.b(see_first_state:865)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.DefaultCacheProcessor.a(video_list_description:63)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.RunnerHelper.b(video_android_autoplay_if_cached:65)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.CacheReadRunner.b(video_data_source:116)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.CacheReadRunner.run(video_data_source:287)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_logging_level:77)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_spec_display:327)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_state:42)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.lang.Thread.run(Thread.java:818)
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.GeneratedUDPPrimingAutoQuickExperiment@1c38fd11 occurred when no user was logged in
,E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): error in step network
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): com.facebook.http.protocol.AuthTokenNullException: auth token is null, user logged out?
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.http.protocol.SingleMethodRunnerImpl.a(stop_pri:533)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.http.protocol.SingleMethodRunnerImpl.a(stop_pri:336)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.http.protocol.SingleMethodRunnerImpl.b(stop_pri:296)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.http.protocol.AbstractSingleMethodRunner.a(stop_extra:43)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.RunnerHelper.a(video_android_autoplay_if_cached:94)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.CacheReadRunner.b(video_data_source:172)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.graphql.executor.CacheReadRunner.run(video_data_source:287)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_logging_level:77)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_spec_display:327)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_state:42)
E/fb4a(:<default>):GraphQLQueryAnalyticsEventImpl(11957): 	at java.lang.Thread.run(Thread.java:818)
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerProxyQuickExperiment@2d851e76 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerHttpQuickExperiment@363a1c77 occurred when no user was logged in
,W/fb4a(:<default>):CacheReadRunner(11957): Exception during graphql executor query
W/fb4a(:<default>):CacheReadRunner(11957): com.facebook.http.protocol.AuthTokenNullException: auth token is null, user logged out?
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.http.protocol.SingleMethodRunnerImpl.a(stop_pri:533)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.http.protocol.SingleMethodRunnerImpl.a(stop_pri:336)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.http.protocol.SingleMethodRunnerImpl.b(stop_pri:296)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.http.protocol.AbstractSingleMethodRunner.a(stop_extra:43)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.graphql.executor.RunnerHelper.a(video_android_autoplay_if_cached:94)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.graphql.executor.CacheReadRunner.b(video_data_source:172)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.graphql.executor.CacheReadRunner.run(video_data_source:287)
W/fb4a(:<default>):CacheReadRunner(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_logging_level:77)
W/fb4a(:<default>):CacheReadRunner(11957): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/fb4a(:<default>):CacheReadRunner(11957): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_spec_display:327)
W/fb4a(:<default>):CacheReadRunner(11957): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/fb4a(:<default>):CacheReadRunner(11957): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/fb4a(:<default>):CacheReadRunner(11957): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_state:42)
W/fb4a(:<default>):CacheReadRunner(11957): 	at java.lang.Thread.run(Thread.java:818)
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.zero.abtest.PreviewModeExperiment@187d680b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerPingTcpRetransmissionQuickExperiment@355bd750 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.DNSReachabilityQuickExperiment@b953d49 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerRequestSchedulingQuickExperiment@16ad864e occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerHeV4PrefQuickExperiment@3522236f occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerSocketBufferQuickExperiment@1d2f187c occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.GatewayPingQuickExperiment@326b6505 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.PacketDefragmentationExperiment@175fb95a occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.NetworkInfoCollectorQuickExperiment@13d7878b occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.HpackQuickExperiment@3e934068 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerConnectionManagementQuickExperiment@3ac24c81 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerHTTP2QuickExperiment@24d01126 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.LigerTCPConnReuseQuickExperiment@3b351167 occurred when no user was logged in
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:-87, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-43
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.Liger2gEmpathyDogfoodQuickExperiment@18df2ac2 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.PersistentDNSCacheQuickExperiment@2a1880d3 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.Liger2gEmpathyDogfoodQuickExperiment@18df2ac2 occurred when no user was logged in
,I/GAV4    (12254): Thread[GAThread,5,main]: No campaign data found.
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.PersistentDNSCacheQuickExperiment@2a1880d3 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.TracerouteQuickExperiment@2f6fa13c occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl(11957): Exposure of experiment com.facebook.http.qe.TracerouteQuickExperiment@2f6fa13c occurred when no user was logged in
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10114
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10114
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope(11957): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PackageManager( 3510): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PCWCLIENTTRACE_SYSTEMReceiver(12001): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(12001): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(12001): ================================================
,I/CSTORAGE(12001):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12001): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12001): [GetString-S]
E/art     (12001): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(12001): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(12001): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12001): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(12001): sales region : global
I/PCWCLIENTTRACE_PushUtil(12001): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12001): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12110): wlan0: sending IPv6 Router Solicitation
,W/ProcessCpuTracker( 3510): Skipping unknown process pid 12619
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/dhcpcd  (12110): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12110): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12395): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12395): exit::IDLE
D/PreloadUpdateManagerStateMachine(12395): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12395): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (12395): RestApi Request Add : 2307
,I/System.out(12395): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12395): (HTTPLog)-Static: isShipBuild true
I/System.out(12395): (HTTPLog)-Thread-1745-237166288: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12395): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10013
,I/System.out(12395): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12395): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12395, getuid(): 10013
,I/qtaguid (12395): Untagging socket 26
,D/hcjo    (12395): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (12395): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(12395): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine(12395): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12395): entry::REQ_UPDATE_CHECK
,I/Volley  (12395): RestApi Request Add : 2315
,I/System.out(12395): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(12395): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid (12395): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12395, getuid(): 10013
,E/Watchdog( 3510): !@Sync 5
,I/qtaguid (12395): Untagging socket -1
,I/qtaguid (12395): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (12395): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger(12395): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine(12395): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(12395): exit::REQ_UPDATE_CHECK
,D/PreloadUpdateManagerStateMachine(12395): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12395): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12395): entry::FINISH,
,D/PreloadUpdateManagerStateMachine(12395): exit::FINISH
D/PreloadUpdateManagerStateMachine(12395): entry::IDLE
,D/SSRM:n  ( 3510): SIOP:: AP = 270, PST = 272, CUR = -87
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3510): [PWL] Off : 75s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 260, PST = 272, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/ClearcutLoggerApiImpl( 4649): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3510): SIOP:: AP = 260, PST = 270, CUR = 35
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 6
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 266, CUR = 46
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3510): [PWL] Off : 105s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 263, CUR = 46
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 261, CUR = 45,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 7
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 260, CUR = 41
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,V/AlarmManager( 3510): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 140s ago
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 259, CUR = 39
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 257, CUR = 39
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 8
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 256, CUR = 37
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 255, CUR = 34
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,V/AlarmManager( 3510): waitForAlarm result :8
,I/PowerManagerService( 3510): [PWL] Off : 180s ago
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 254, CUR = 32
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 9
,D/SSRM:n  ( 3510): SIOP:: AP = 250, PST = 253, CUR = 32
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 251, CUR = 31
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 250, CUR = 30
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 10
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 249, CUR = 30
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 225s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 247, CUR = 31
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 246, CUR = 29
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3510): stay LED for fully charged
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 11
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 246, CUR = 29
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 245, CUR = 27
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 245, CUR = 26
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3510): [PWL] Off : 275s ago
,D/TimaService( 3510): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3510): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3510): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3510): initializing...
,I/TLC_TIMA_PKM_initialize( 3510): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3510): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3510): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3510): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3510): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 3510): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3510): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3510): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3510): device_id = 0x0
,I/TZ: mc_tlc_communication( 3510): tlc_open() was called
I/TZ: mc_tlc_communication( 3510): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3510): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3510): Opening the session
,I/TZ: mc_tlc_communication( 3510): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3510): Trustlet response is completed
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 12
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 244, CUR = 28
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 244, CUR = 26
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 243, CUR = 27
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 13
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 243, CUR = 27
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 242, CUR = 25
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 330s ago
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 242, CUR = 24
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 14
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 241, CUR = 23
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 241, CUR = 22
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,V/AlarmManager( 3510): waitForAlarm result :8
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 241, CUR = 22
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 15
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 21,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 390s ago
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 16
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 21
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 17
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 21,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 455s ago
,E/Watchdog( 3510): !@Sync 18
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 18
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 19
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 19
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 20,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 18
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 525s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3510): Killing 11661:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged,
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 21
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 16
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3510): stay LED for fully charged
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3510): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3510): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3510): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 3510): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 3510): !@Sync 22
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 19,
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 600s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 23
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 24
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15,
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 17
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 25
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 680s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 14
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3510): !@Sync 26
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15,
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 16
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 27
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 15
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 14
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 13
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 28
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 13
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 765s ago
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 13
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 12
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 29
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 13
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 12
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,V/AlarmManager( 3510): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/LightsService( 3510): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3510): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3510): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 7002): Aggregate from 1449061962065 (log), 1449061962065 (data)
,I/GoogleURLConnFactory( 4167): Using platform SSLCertificateSocketFactory
,I/Sensors ( 3510): #>LightSensor r=33 g=33 b=29 c=73 atime=238 again=64 lux=11.000000
,D/LightsService( 3510): [SvcLED]  onSensorChanged::light value = 11
I/Sensors ( 3510): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3510): unregisterListener ::   
,D/lights  ( 3510): led_pattern : 5 +
,D/lights  ( 3510): led_pattern : 5 -
D/LightsService( 3510): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/art     ( 3510): Explicit concurrent mark sweep GC freed 89652(7MB) AllocSpace objects, 230(3MB) LOS objects, 24% free, 49MB/65MB, paused 2.188ms total 161.925ms
,I/System.out( 4167): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 503 for uid 10014
,I/System.out( 4167): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4167): Tagging socket 62 with tag 1000120300000000{268440067,0} uid -1, pid: 4167, getuid(): 10014
,I/qtaguid ( 4167): Tagging socket 66 with tag 1000120300000000{268440067,0} uid -1, pid: 4167, getuid(): 10014
,W/PhenotypeConfigurator( 4167): Server returned 404
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 12,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 30
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 11
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3510): waitForAlarm result :8
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 31
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 240, CUR = 11
,I/PowerManagerService( 3510): [PWL] Off : 855s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 239, CUR = 12
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 239, CUR = 13
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/TimaService( 3510): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3510): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3510): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 32
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 240, PST = 239, CUR = 12
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 238, CUR = 11,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 238, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 33
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 238, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 237, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 237, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3510): !@Sync 34
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 236, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3510): [PWL] Off : 950s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 236, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 236, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,E/Watchdog( 3510): !@Sync 35
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 235, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 235, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 235, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 36
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 234, CUR = 8
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 234, CUR = 8
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 234, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 37
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 233, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 233, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3510): [PWL] Off : 1050s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 233, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 38
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 232, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 232, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 232, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 39
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 231, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 231, CUR = 11
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 231, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/UsageStatsService( 3510): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3510): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3510): Updating Usage Statistics in DB @ 1449064298618
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
,W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3510): ::getAppControlDB: Exception to create DB
W/System.err( 3510): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3510): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3510): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3510): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3510): Done Updating Usage Statistics in DB @ 1449064298695
,E/Watchdog( 3510): !@Sync 40
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 10
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3510): stay LED for fully charged
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 41
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/PowerManagerService( 3510): [PWL] Off : 1155s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 9
,D/TimaService( 3510): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3510): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 3510): TimaServiceHandler.handleMessage what =1,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 3510): !@Sync 42
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 8
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 43
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 9
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 44
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 1265s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 45
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called,
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 46
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 47
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5,
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3510): stay LED for fully charged
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 48
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 1380s ago
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 49
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 50
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 51
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/TimaService( 3510): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3510): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3510): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3510): !@Sync 52
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/PowerManagerService( 3510): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 53
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 54
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
D/BatteryService( 3510): stay LED for fully charged
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3510): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 55
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 56
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3510): [PWL] Off : 1625s ago
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 57
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 58
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 59
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true,
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3510): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
D/LightsService( 3510): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3510): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/SensorManager( 3510): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,V/AlarmManager( 3510): OOI=Alarm{82fac6c type 0 when 1449066687144 com.google.android.gms}
,D/NetworkStatsFactory( 3510): UpdateStatsForKnox
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3510): #>LightSensor r=28 g=27 b=24 c=57 atime=238 again=64 lux=8.000000
,D/LightsService( 3510): [SvcLED]  onSensorChanged::light value = 8
I/Sensors ( 3510): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3510): unregisterListener ::   
,D/LightsService( 3510): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 60
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,V/AlarmManager( 3510): waitForAlarm result :8
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called,
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 61
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,I/PowerManagerService( 3510): [PWL] Off : 1755s ago
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/TimaService( 3510): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3510): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3510): TimaServiceHandler.handleMessage what =1,
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3510): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3510): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 3510): !@Sync 62
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/BatteryService( 3510): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 63
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,E/Watchdog( 3510): !@Sync 64
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3510): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3510): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3510): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3510): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3510): stay LED for fully charged
,I/MotionRecognitionService( 3510): Plugged
,I/MotionRecognitionService( 3510): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5678): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5678): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(11856): DBG, CoordinatorConnector connect_error called
I/jxcore-log(11856): 
D/AndroidRuntime(14003): 
D/AndroidRuntime(14003): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(14003): CheckJNI is OFF
D/AndroidRuntime(14003): readGMSProperty: start
D/AndroidRuntime(14003): readGMSProperty: already setted!!
D/AndroidRuntime(14003): readGMSProperty: end
D/AndroidRuntime(14003): addProductProperty: start
E/AffinityControl(14003): AffinityControl: registerfunction enter
D/AndroidRuntime(14003): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 3510): START PACKAGE DELETE: observer{173900341}
D/PackageManager( 3510): pkg{<packageName>}
D/PackageManager( 3510): user{0}
D/PackageManager( 3510): caller{2000}
D/PackageManager( 3510): flags{3}
D/PersonaManagerService( 3510): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3510): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3510): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3510): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3510): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3510): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3510): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3510): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3510): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3510): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3510): !@killApplicatoin: 10443, uninstall pkg
I/ActivityManager( 3510): Force stopping com.test.thalitest appid=10443 user=-1: uninstall pkg
I/ActivityManager( 3510): Killing 11856:com.test.thalitest/u0a443 (adj 0): stop com.test.thalitest
I/ActivityManager( 3510): Killing 12169:com.osp.app.signin/u0a45 (adj 13): empty for 1805s
I/ActivityManager( 3510): Killing 12132:com.policydm/1000 (adj 13): empty for 1805s
I/ActivityManager( 3510): Killing 12111:com.sec.android.soagent/u0a38 (adj 13): empty for 1806s
I/ActivityManager( 3510): Killing 12094:com.samsung.klmsagent/u0a21 (adj 13): empty for 1806s
I/ActivityManager( 3510): Killing 12078:com.sec.android.fotaclient/u0a12 (adj 13): empty for 1806s
I/ActivityManager( 3510): Killing 12062:com.sec.android.diagmonagent/1000 (adj 13): empty for 1806s
I/ActivityManager( 3510): Killing 12042:com.sec.android.cloudagent/u0a2 (adj 13): empty for 1806s
I/ActivityManager( 3510): Killing 12001:com.sec.pcw.device/1000 (adj 13): empty for 1806s
I/ActivityManager( 3510): Killing 11491:com.samsung.android.snote/u0a160 (adj 15): empty for 1806s
I/ActivityManager( 3510): Killing 8947:com.android.settings/1000 (adj 15): empty for 1806s
I/ActivityManager( 3510): Killing 12361:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1807s
I/ActivityManager( 3510): Killing 10511:com.android.vending/u0a31 (adj 15): empty for 1833s
I/ActivityManager( 3510): Killing 11004:com.android.defcontainer/u0a5 (adj 15): empty for 1842s
I/ActivityManager( 3510): Killing 11642:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): empty for 1851s
I/ActivityManager( 3510): Killing 11677:com.android.calendar/u0a164 (adj 15): empty for 1851s
I/ActivityManager( 3510):   Force finishing activity ActivityRecord{32309a2d u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3510): mDVFSHelper.acquire()
W/PackageSettings( 3510): Skipping PackageSetting{253d976d com.example.hello/10436} due to missing metadata
D/WifiService( 3510): Client connection lost with reason: 4
I/WindowState( 3510): WIN DEATH: Window{3009195b u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 2852): id=14 Removed NainActivit (5/8)
I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
D/WifiService( 3510): Client connection lost with reason: 4
I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 3510): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3510): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3510): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3510): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 3510): Force stopping com.test.thalitest appid=10443 user=0: pkg removed
I/ActivityManager( 3510):   Force finishing activity ActivityRecord{32309a2d u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3510): Duplicate finish request for ActivityRecord{32309a2d u0 com.test.thalitest/.MainActivity t26 f}
I/art     ( 4041): Explicit concurrent mark sweep GC freed 31181(1929KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.278ms total 41.833ms
I/art     ( 9149): Explicit concurrent mark sweep GC freed 23689(1404KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.187ms total 51.528ms
W/libprocessgroup( 3510): failed to open /acct/uid_10021/pid_12094/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_1000/pid_12132/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10005/pid_11004/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10164/pid_11677/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10038/pid_12111/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10160/pid_11491/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_1000/pid_12062/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_1000/pid_8947/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10002/pid_12042/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10045/pid_12169/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_1000/pid_12001/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10012/pid_12078/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10031/pid_10511/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10022/pid_11642/cgroup.procs: No such file or directory
W/libprocessgroup( 3510): failed to open /acct/uid_10082/pid_12361/cgroup.procs: No such file or directory
I/DBG_DM  ( 6406): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/ProcessStatsService( 3510): Prepared write state in 10ms
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
I/ProcessStatsService( 3510): Prepared write state in 14ms
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/ProcessStatsService( 3510): Prepared write state in 12ms
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6406): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 7
I/ProcessStatsService( 3510): Prepared write state in 12ms
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 6406): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/ProcessStatsService( 3510): Prepared write state in 15ms
I/ProcessStatsService( 3510): Prepared write state in 13ms
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/ProcessStatsService( 3510): Prepared write state in 10ms
D/SecContentProvider2( 3510): uri = 14 selection = getSealedState
D/SecContentProvider2( 3510): mCursor = null
D/ApplicationPolicy( 3510): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3510): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
I/art     ( 3510): Explicit concurrent mark sweep GC freed 84457(9MB) AllocSpace objects, 326(5MB) LOS objects, 24% free, 49MB/65MB, paused 2.128ms total 173.586ms
I/art     ( 3510): WaitForGcToComplete blocked for 100.971ms for cause Explicit
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/ProcessStatsService( 3510): Prepared write state in 22ms
I/DBG_DM  ( 6406): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6406): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6406): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6406): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6406): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader( 3510): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 4469): mOCRHelper is null
W/GeofencerStateMachine( 4649): Ignoring removeGeofence because network location is disabled.
W/BroadcastQueue( 3510): Skipping deliver [background] BroadcastRecord{2414603b u0 android.intent.action.PACKAGE_REMOVED} to ReceiverList{43b6923 11642 com.sec.android.widgetapp.locationwidget/10022/u0 remote:35b64252}: filter unregistered
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
W/ResourceType( 5404): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5404): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
E/Zygote  (14022): MountEmulatedStorage()
E/Zygote  (14022): v2
I/libpersona(14022): KNOX_SDCARD checking this for 10063
I/libpersona(14022): KNOX_SDCARD not a persona
I/SELinux (14022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3510): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=14022 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3510): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/SELinux (14022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (14022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/ProcessStatsService( 3510): Prepared write state in 12ms
D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ProcessStatsService( 3510): Prepared write state in 22ms
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/ProcessStatsService( 3510): Prepared write state in 11ms
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/ProcessStatsService( 3510): Prepared write state in 11ms
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/TimaKeyStoreProvider(14022): TimaSignature is unavailable
D/ActivityThread(14022): Added TimaKeyStore provider
D/ResourcesManager( 3510): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/ProcessStatsService( 3510): Prepared write state in 13ms
D/ActivityManager( 3510): post active user change for 0
D/KnoxTimeoutHandler( 3510): postActiveUserChange for user 0
D/SecContentProvider2( 3510): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3510): mCursor = null
I/DBG_DM  ( 6406): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/art     ( 3510): Explicit concurrent mark sweep GC freed 7316(418KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 5.849ms total 152.033ms
D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/ProcessStatsService( 3510): Prepared write state in 8ms
D/ResourcesManager(14022): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
I/SurfaceFlinger( 2852): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
I/ProcessStatsService( 3510): Prepared write state in 7ms
D/StatusBarManagerService( 3510): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3510): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3510): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3510): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3510): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3510): setHoveringSpenCustomIcon IconType is same.1
D/InputMethodManagerService( 3510): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/ProcessStatsService( 3510): Prepared write state in 14ms
D/VRSetupWizardStub/PackageIntentReceiver(14022): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(14022): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(14022): packagename:com.test.thalitest
W/InputMethodManagerService( 3510): Got RemoteException sending setActive(false) notification to pid 11856 uid 10443
W/ContextImpl( 3510): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ProcessStatsService( 3510): Prepared write state in 13ms
I/ProcessStatsService( 3510): Prepared write state in 7ms
I/ProcessStatsService( 3510): Prepared write state in 18ms
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
I/ProcessStatsService( 3510): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-48-09.bin
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/Zygote  (14041): MountEmulatedStorage()
E/Zygote  (14041): v2
I/libpersona(14041): KNOX_SDCARD checking this for 10021
I/libpersona(14041): KNOX_SDCARD not a persona
I/SELinux (14041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (14041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=14041 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/Timeline( 6406): Timeline: Activity_idle id: android.os.BinderProxy@61a5fe5 time:1958137
I/ActivityManager( 3510): Killing 12190:com.samsung.android.scloud.backup/u0a67 (adj 15): empty for 1806s
V/ActivityThread( 6406): updateVisibility : ActivityRecord{1d594a48 token=android.os.BinderProxy@61a5fe5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/RegisteredServicesCache( 3970): empty dynamic service
W/ActivityManager( 3510): mDVFSHelper.release()
I/Timeline( 3510): Timeline: Activity_windows_visible id: ActivityRecord{3915cade u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1958161
D/TimaKeyStoreProvider(14041): TimaSignature is unavailable
D/ActivityThread(14041): Added TimaKeyStore provider
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(14041): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/PackageManager( 3510): delete codoeFile: 
I/AASAUninstall( 3510):  com.test.thalitest not target!
D/PackageManager( 3510): result of delete: 1{173900341}
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/AndroidRuntime(14003): Shutting down VM
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/KLMS-2.4.521: (14041): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 15:04:05 GMT+01:00 2015
W/libprocessgroup( 3510): failed to open /acct/uid_10067/pid_12190/cgroup.procs: No such file or directory
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/KLMS-2.4.521: (14041): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3510): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/splitIntent( 3510): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (14041): KLMSIntentService(): onCreate()
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
I/KLMS-2.4.521: (14041): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.521: (14041): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/EnterpriseDeviceManagerService( 3510): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3510): Admin package name: com.google.android.gms
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.521: (14041): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (14041): KLMSIntentService(): PACKAGE_REMOVED
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/KLMS-2.4.521: (14041): KLMSIntentService(): listeningToPackageRemoved().START
E/Zygote  (14057): MountEmulatedStorage()
E/Zygote  (14057): v2
I/libpersona(14057): KNOX_SDCARD checking this for 10106
I/libpersona(14057): KNOX_SDCARD not a persona
I/SELinux (14057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/KLMS-2.4.521: (14041): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/SELinux (14057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (14057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=14057 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3510): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
W/Resources( 3510): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/TimaKeyStoreProvider(14057): TimaSignature is unavailable
D/ActivityThread(14057): Added TimaKeyStore provider
D/RCPManager(12206):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/RCPManagerService( 3510):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3510): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources( 3510): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  (14072): MountEmulatedStorage()
I/libpersona(14072): KNOX_SDCARD checking this for 10160
E/Zygote  (14072): v2
I/libpersona(14072): KNOX_SDCARD not a persona
I/SELinux (14072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (14072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3510): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=14072 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(14072): TimaSignature is unavailable
D/ActivityThread(14072): Added TimaKeyStore provider
E/Zygote  (14087): MountEmulatedStorage()
I/libpersona(14087): KNOX_SDCARD checking this for 10050
E/Zygote  (14087): v2
I/libpersona(14087): KNOX_SDCARD not a persona
I/SELinux (14087): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14087): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/KLMS-2.4.521: (14041): KLMSIntentService(): listeningToPackageRemoved().END
E/SELinux (14087): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(14057): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
I/ActivityManager( 3510): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=14087 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
I/art     ( 2879): Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.375ms total 23.406ms
I/KLMS-2.4.521: (14041): KLMSIntentService(): onDestroy()
D/elm:14491(14057): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(14057): ELMEngine.ELMEngine( context ).
D/elm:14491(14057): MDMBridge.setEnterpriseBridge()
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/TimaKeyStoreProvider(14087): TimaSignature is unavailable
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ActivityThread(14087): Added TimaKeyStore provider
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 858us total 17.428ms
D/ResourcesManager(14072): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/SSRM:n  ( 3510): SIOP:: AP = 230, PST = 230, CUR = 4
W/ResourcesManager(14072): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(14072): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(14072): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 451us total 14.269ms
E/Zygote  (14102): MountEmulatedStorage()
E/Zygote  (14102): v2
I/libpersona(14102): KNOX_SDCARD checking this for 10101
I/libpersona(14102): KNOX_SDCARD not a persona
I/SELinux (14102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3510): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=14102 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (14102): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/elm:14491(14057): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(14057): ElmAgentService : onCreate()
D/elm:14491(14057): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/ActivityManager( 3510): Killing 12221:com.android.chrome/u0a90 (adj 15): empty for 1806s
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3510): checkUser: useridlist=null, currentuser=0
D/elm:14491(14057): MainReceiver.listeningToPackageRemoved()
D/TimaKeyStoreProvider(14102): TimaSignature is unavailable
D/elm:14491(14057): MDMBridge.getInstance()
D/elm:14491(14057): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(14087): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ActivityThread(14102): Added TimaKeyStore provider
W/ResourcesManager(14087): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(14087): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(14087): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/elm:14491(14057): MDMBridge.getAllLicenseInfoFromSDK()
W/ResourcesManager(14087): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(14087): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(14087): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(14087): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(14087): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  (14118): MountEmulatedStorage()
E/Zygote  (14118): v2
I/libpersona(14118): KNOX_SDCARD checking this for 10019
I/libpersona(14118): KNOX_SDCARD not a persona
I/SELinux (14118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3510): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=14118 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (14118): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 3510): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3510): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources( 3510): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3510): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3510): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/Resources( 3510): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
